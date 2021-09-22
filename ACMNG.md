## ACMNG-01
## Added styled components babel plugin

Installed `babel-plugin-styled-components` plugin.
Added plugin into babel-loader.


## ACMNG-02
## Babel loader version bumped to 8.2.2

This may not be really needed in the future,
but build preflight check complained about mixed versions.

Modify `package.json` and bump `"babel-loader": "8.2.2"`


## ACMNG-03
## Removed TS setup verification

Original scripts modify tsconfig.json on execution.
Comment out `verifyTypeScriptSetup` in `start.js`, `build.js` and `test.js` scripts.


## ACMNG-04
## Path alias support

Added path aliases to `webpack.config.js`


## ACMNG-05
## Better error logs

Added stats into `webpack.config.js`
Added "Build Error Info" into `build.js`


## ACMNG-06
## Fixed broken hot reload

Added ENV option to override protocol `WDS_SOCKET_PROTOCOL` in `webpackHotDevClient.js`
Added ENV option to override protocol `WDS_SOCKET_PROTOCOL` in `env.js`
Package `react-dev-utils` renamed and published as `accomango-react-dev-utils`.
Updated reference in `accomango-react-scripts`, so it uses new `accomango-react-dev-utils`.


## ACMNG-07
## Added graphql loader for webpack

Installed `graphql-tag` package.
Added loader into `webpack.config.js`.
