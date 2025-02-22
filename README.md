# React Native FlatList: TypeError: undefined is not an object (evaluating 'item.property')

This repository demonstrates a common error encountered when using the `FlatList` component in React Native.  The error, `TypeError: undefined is not an object (evaluating 'item.property')`, arises from attempting to access properties of the `item` prop within the `renderItem` function before the component has fully mounted and populated the data.

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a corrected version that ensures data is available before access.