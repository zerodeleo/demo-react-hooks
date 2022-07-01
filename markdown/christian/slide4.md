#### CLASS COMPONENT - RENDER:

```JSX
class Counter extends React.Component {
    // ... constructor
    // ... setters
    
    render() {
        return (
            <div>
                <button onClick={e => this.decrement(e)}>-</button>
                <button onClick={e => this.increment(e)}>-</button>
            </div>
        );
    }
}
```