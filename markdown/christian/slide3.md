#### SETTERS:

```JSX
class Counter extends React.Component {
    // ... constructor
    decrement() {
        this.setState(prevState => (
                prevState <= 0 
                ? 0 
                : ({ count: prevState.count - 1 })
            )
        );
    }

    increment() {
        this.setState(prevState => (
                { count: prevState.count + 1 }
            )
        );
    }
    // ... render
}
```