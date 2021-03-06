# Description

A DRY library to facilitate the scaffolding of React-Redux-Thunk APPs.
It ships a ready to work project structure, with general purpose Actions and Reducers. All wired with Redux, Thunk, Bootstrap and LESS.


## Stack:

- React
- Redux
- Thunk
- Axios
- LESS


# INSTRUCTIONS

1. Install Dependencies:

   > yarn add axios react-router-dom reactstrap bootstrap redux react-redux redux-thunk
   > yarn add react-logger redux-devtools-extension redux-logger dotenv --dev

2. Start the React APP:

   > In the root directory run: _yarn start_

3. Run `less-watch-compiler`

   > In the root directory run: _less-watch-compiler src/less src/precss index.less_

4. Run `Auto-prefixer`
   > In the root directory run: _npx postcss src/precss/index.css --useautoprefixer -d src/css/ -w_
