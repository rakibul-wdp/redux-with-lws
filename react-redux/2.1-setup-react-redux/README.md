# Setup react-redux

### Installation and setup Actions

- Create action types and export it. Action type will be feature name wise.
- Create actions by using action types and value. Basically it's a function and it return type and payload.

# Creating Reducers

### Define our business logics

- Create counterReducer function with switch statement. This function take tow parameter like initialState anc action. Reducer function is immutably done.

# Creating Store

### Providing store to React Application

- Create store in redux root. Import createStore and pass counterReducer in it.
- Import Provider from react-redux and wrap whole app with Provider and also pass store within it.

# Connect API

### mapStateToProps() and mapDispatchToProps()

- Higher Order Component
- What they actually do?
- A Higher-order Component is a function that takes a component as parameter and return a new component.
- `const NewComponent = HOC(OriginalComponent)`

# Redux hooks - useSelector()

### Simplify Redux & replace connect API

# Redux hooks - useDispatch()

### Simplify dispatching actions to Redux

- useDispatch for dispatch.

# Redux combineReducers()

### Modularize Redux reducers for better maintainability

# Own props with connect API

### Accessing component own props

# Redux Middleware Concept

### Creating custom logger for Redux store

# Adding multiple Middleware

### Adding third party Middleware in our app

# Debugging Redux Application

### Installing Redux Devtools extension
