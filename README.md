# React useEffect Hook with Empty Dependency Array
This example demonstrates a common mistake in using the React `useEffect` hook:  using an empty dependency array `[]`.  The `useEffect` hook, with an empty dependency array, only runs once after the component mounts.  In this case, the log statement only executes once after initial render, and not whenever the count changes.

The solution corrects this by correctly adding the `count` variable into the dependency array.