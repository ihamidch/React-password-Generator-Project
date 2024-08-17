this react password generator project
we use  usecallback  hook in this for preventing uncessery re-rending

The useCallback hook in React helps you save a function so it doesn't change unless needed. It prevents React from creating the function again every time the component updates. This is useful for keeping your app fast, especially when giving functions to child components, as it stops them from re-rendering unnecessarily