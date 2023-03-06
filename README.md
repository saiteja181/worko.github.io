# worko.github.io
Microsoft Windows [Version 10.0.22000.1219]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Divya sri>cd OneDrive\Desktop\mine-2

C:\Users\Divya sri\OneDrive\Desktop\mine-2>cd ts-ui-master

C:\Users\Divya sri\OneDrive\Desktop\mine-2\ts-ui-master>npm start

> telar-social-engine@0.7.0 start
> npm-run-all -p watch-css start-js


> telar-social-engine@0.7.0 start-js
> craco start


> telar-social-engine@0.7.0 watch-css
> npm run build-css && sass src/styles/app.scss src/styles/app.css --watch


> telar-social-engine@0.7.0 build-css
> sass src/styles/app.scss src/styles/app.css

Sass is watching for changes. Press Ctrl-C to stop.

(node:14344) [DEP_WEBPACK_DEV_SERVER_ON_AFTER_SETUP_MIDDLEWARE] DeprecationWarning: 'onAfterSetupMiddleware' option is deprecated. Please use the 'setupMiddlewares' option.
(Use `node --trace-deprecation ...` to show where the warning was created)
(node:14344) [DEP_WEBPACK_DEV_SERVER_ON_BEFORE_SETUP_MIDDLEWARE] DeprecationWarning: 'onBeforeSetupMiddleware' option is deprecated. Please use the 'setupMiddlewares' option.
Starting the development server...
Compiled successfully!

You can now view telar-social-engine in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://192.168.200.48:3000

Note that the development build is not optimized.
To create a production build, use yarn build.

webpack compiled successfully
Files successfully emitted, waiting for typecheck results...
Issues checking in progress...
No issues found.
^C^CERROR: "watch-css" exited with 3221225786.

C:\Users\Divya sri\OneDrive\Desktop\mine-2\ts-ui-master>
C:\Users\Divya sri\OneDrive\Desktop\mine-2\ts-ui-master>npm start

> telar-social-engine@0.7.0 start
> npm-run-all -p watch-css start-js


> telar-social-engine@0.7.0 start-js
> craco start


> telar-social-engine@0.7.0 watch-css
> npm run build-css && sass src/styles/app.scss src/styles/app.css --watch


> telar-social-engine@0.7.0 build-css
> sass src/styles/app.scss src/styles/app.css

Sass is watching for changes. Press Ctrl-C to stop.

(node:15684) [DEP_WEBPACK_DEV_SERVER_ON_AFTER_SETUP_MIDDLEWARE] DeprecationWarning: 'onAfterSetupMiddleware' option is deprecated. Please use the 'setupMiddlewares' option.
(Use `node --trace-deprecation ...` to show where the warning was created)
(node:15684) [DEP_WEBPACK_DEV_SERVER_ON_BEFORE_SETUP_MIDDLEWARE] DeprecationWarning: 'onBeforeSetupMiddleware' option is deprecated. Please use the 'setupMiddlewares' option.
Starting the development server...
Compiled successfully!

You can now view telar-social-engine in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://192.168.200.48:3000

Note that the development build is not optimized.
To create a production build, use yarn build.

webpack compiled successfully
Files successfully emitted, waiting for typecheck results...
Issues checking in progress...
Compiling...
Compiled with warnings.

[eslint]
src\redux\actions\serverRequestStatusType.ts
  Line 2:5:  'Sent' is defined but never used      no-unused-vars
  Line 3:5:  'NoAction' is defined but never used  no-unused-vars
  Line 4:5:  'OK' is defined but never used        no-unused-vars
  Line 5:5:  'Error' is defined but never used     no-unused-vars

src\redux\reducers\users\userGetters.ts
  Line 3:28:  'state' is defined but never used   no-unused-vars
  Line 3:55:  'userId' is defined but never used  no-unused-vars

Search for the keywords to learn more about each warning.
To ignore, add // eslint-disable-next-line to the line before.

WARNING in [eslint]
src\redux\actions\serverRequestStatusType.ts
  Line 2:5:  'Sent' is defined but never used      no-unused-vars
  Line 3:5:  'NoAction' is defined but never used  no-unused-vars
  Line 4:5:  'OK' is defined but never used        no-unused-vars
  Line 5:5:  'Error' is defined but never used     no-unused-vars

src\redux\reducers\users\userGetters.ts
  Line 3:28:  'state' is defined but never used   no-unused-vars
  Line 3:55:  'userId' is defined but never used  no-unused-vars

webpack compiled with 1 warning
Files successfully emitted, waiting for typecheck results...
Issues checking in progress...
No issues found.

commands -used:- npm start

why previously not loaded : since i am making requests to load pages on same ports parallely so its not loaded i think 
