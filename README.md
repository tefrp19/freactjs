模仿React用于学习的简易前端框架FReact

# Usage

```jsx
import {useState} from "freact";

function Counter() {
    const [count, setCount] = useState(0);
    return (
        <>
            <h1>{count}</h1>
            <button onClick={() => setCount(count + 1)}>
                add
            </button>
        </>
    );
}

const App = <Counter/>
freact.render(<App/>, document.getElementById('root'));
```

参考文章：[build your own React](https://pomb.us/build-your-own-react/)

