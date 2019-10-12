<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [useFirebase][1]
    -   [Examples][2]

## useFirebase

-   **See: [http://docs.react-redux-firebase.com/history/v3.0.0/docs/api/useFirebase.html][3]**

### Examples

_Basic_

```javascript
import { useFirebase } from 'react-redux-firebase'

function AddData() {
  const firebase = useFirebase()

  function addTodo() {
    const exampleTodo = { done: false, text: 'Sample' }
    return firebase.push('todos', exampleTodo)
  }

  return (
    <div>
      <button onClick={addTodo}>
        Add Sample Todo
      </button>
    </div>
  )
}
```

Returns **[object][4]** Extended Firebase instance

[1]: #usefirebase

[2]: #examples

[3]: http://docs.react-redux-firebase.com/history/v3.0.0/docs/api/useFirebase.html

[4]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object