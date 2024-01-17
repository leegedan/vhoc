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

方便设置组件默认props，业务组件更好用。 顺便水个包。
