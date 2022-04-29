# @jest/reporters@28 tsc poc

```console
npm install
```

```console
npm build
```

```typescript
> build
> tsc

node_modules/@jest/reporters/build/index.d.ts:12:28 - error TS7016: Could not find a declaration file for module '@jest/types/build/Config'. '/node_modules/@jest/types/build/Config.js' implicitly has an 'any' type.
   If the '@jest/types' package actually exposes this module, try adding a new declaration (.d.ts) file containing `declare module '@jest/types/build/Config';`

 12 import {GlobalConfig} from '@jest/types/build/Config';
                               ~~~~~~~~~~~~~~~~~~~~~~~~~~

 node_modules/@jest/reporters/build/index.d.ts:13:29 - error TS7016: Could not find a declaration file for module '@jest/types/build/Config'. '/node_modules/@jest/types/build/Config.js' implicitly has an 'any' type.
   If the '@jest/types' package actually exposes this module, try adding a new declaration (.d.ts) file containing `declare module '@jest/types/build/Config';`

 13 import {ProjectConfig} from '@jest/types/build/Config';
                                ~~~~~~~~~~~~~~~~~~~~~~~~~~


 Found 2 errors in the same file, starting at: node_modules/@jest/reporters/build/index.d.ts:12
```
