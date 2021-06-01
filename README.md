# redux-toolkit
This is a basic project based on redux-toolkit.
Two different states i.e counter state and authentication state has been managed by redux-toolkit.
Redux Toolkit is a package which makes the use of redux a lot simpler.
It brings a concept of "SLICES" for managing different states independently and very easily.
With redux-toolkit we don't have to explicitly define the TYPE in DISPATCH function which minimises the error that we can make while checking for the TYPE in reducer 
function in case of redux.
It allows us to change the state in a mutable way while in redux we were not be able to do so. However, behind the scenes redux-toolkit manages the state immutably.
