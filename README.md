
To reproduce the bug


Clone this repository and install dependencies with `npm install`

then run at the root of the project

`./node_modules/.bin/stylelint "./**/*.scss"  --config .stylelintrc`

Results include some errors from some bootsrap files inside `node_modules` which shouldn't have to
