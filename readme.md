with "@material-table/core": "~4.3.44"

```powershell
date; npm install; date; npm run build --if-present; date;

Thursday, October 27, 2022 7:46:52 PM
npm ERR! code ERESOLVE
npm ERR! ERESOLVE unable to resolve dependency tree
npm ERR!
npm ERR! While resolving: twoonethree@0.1.0
npm ERR! Found: react@16.14.0
npm ERR! node_modules/react
npm ERR!   react@"^16.8.6" from the root project
npm ERR!
npm ERR! Could not resolve dependency:
npm ERR! peer react@">=17.0.0" from @material-table/core@4.3.45
npm ERR! node_modules/@material-table/core
npm ERR!   @material-table/core@"~4.3.44" from the root project
npm ERR!
npm ERR! Fix the upstream dependency conflict, or retry
npm ERR! this command with --force, or --legacy-peer-deps
npm ERR! to accept an incorrect (and potentially broken) dependency resolution.
npm ERR!
npm ERR! See C:\Users\[redacted]\scoop\persist\nodejs-lts\cache\eresolve-report.txt for a full report.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\[redacted]\scoop\persist\nodejs-lts\cache\_logs\2022-10-28T00_46_58_402Z-debug-0.log
Thursday, October 27, 2022 7:47:03 PM

> twoonethree@0.1.0 build
> react-scripts build

'react-scripts' is not recognized as an internal or external command,
operable program or batch file.
Thursday, October 27, 2022 7:47:05 PM
```

with "@material-table/core": "^4.3.44",

```powershell
date; npm install; date; npm run build --if-present; date;

Thursday, October 27, 2022 7:50:50 PM
npm ERR! code ERESOLVE
npm ERR! ERESOLVE unable to resolve dependency tree
npm ERR!
npm ERR! While resolving: twoonethree@0.1.0
npm ERR! Found: react@16.14.0
npm ERR! node_modules/react
npm ERR!   react@"^16.8.6" from the root project
npm ERR!
npm ERR! Could not resolve dependency:
npm ERR! peer react@">=17.0.0" from @material-table/core@4.3.45
npm ERR! node_modules/@material-table/core
npm ERR!   @material-table/core@"^4.3.44" from the root project
npm ERR!
npm ERR! Fix the upstream dependency conflict, or retry
npm ERR! this command with --force, or --legacy-peer-deps
npm ERR! to accept an incorrect (and potentially broken) dependency resolution.
npm ERR!
npm ERR! See C:\Users\[redacted]\scoop\persist\nodejs-lts\cache\eresolve-report.txt for a full report.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\[redacted]\scoop\persist\nodejs-lts\cache\_logs\2022-10-28T00_50_51_763Z-debug-0.log
Thursday, October 27, 2022 7:50:52 PM

> twoonethree@0.1.0 build
> react-scripts build

'react-scripts' is not recognized as an internal or external command,
operable program or batch file.
Thursday, October 27, 2022 7:50:53 PM
```

looks good with 

```powershell
 date; npm install; date; npm run build --if-present; date;

Thursday, October 27, 2022 7:53:13 PM
npm WARN deprecated stable@0.1.8: Modern JS already guarantees Array#sort() is a stable sort, so this library is deprecated. See the compatibility table on MDN: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort#browser_compatibility
npm WARN deprecated w3c-hr-time@1.0.2: Use your platform's native performance.now() and performance.timeOrigin.
npm WARN deprecated uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm WARN deprecated svgo@1.3.2: This SVGO version is no longer supported. Upgrade to v2.x.x.
npm WARN deprecated @react-forked/dnd@14.0.2: This package found a new home and has moved to a new organization. You should install @hello-pangea/dnd instead to have access to the latest version of this library. For more details: https://dev.to/100terres/whats-up-with-rfd-578a

added 1467 packages, and audited 1468 packages in 4m

217 packages are looking for funding
  run `npm fund` for details

6 high severity vulnerabilities

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
Thursday, October 27, 2022 7:56:47 PM

> twoonethree@0.1.0 build
> react-scripts build

Creating an optimized production build...
Compiled successfully.

File sizes after gzip:

  3.2 kB  build\static\js\main.b575fed6.js

The project was built assuming it is hosted at /.
You can control this with the homepage field in your package.json.

The build folder is ready to be deployed.
You may serve it with a static server:

  npm install -g serve
  serve -s build

Find out more about deployment here:

  https://cra.link/deployment

Thursday, October 27, 2022 7:57:26 PM

```