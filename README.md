# vhoc

A simple and practical vue code

## use

```jsx
import { connent } from '@leegedan/vhoc'

const TestSpan = {
  props: { text: { type: String } },
  setup(props) {
    return () => <span>{props.text}</span>;
  }
};

const HaSpan = connent(TestSpan)({ text: 'haha' })
// HaSpan.name = 'HaSpan'

```

### desc

vue 项目我都会用这个方式来设置组件默认props，有的业务组件更好用。 用了好多年也没看到有人来说这个，顺便去水个包。