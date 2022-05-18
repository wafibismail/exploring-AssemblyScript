Installation steps with npm

```
cd exploring-AssemblyScript
npm init
npm install --save-dev assemblyscript
npx asinit .
```

Build, test, test... No need to run all...:

```
npm run asbuild
npm run test
npm start
```

Note:
- edit & add files in assembly/ and tests/
- tweak asconfig.json as needed
- experiment with excluding certain files as not all are needed. *asinit* will recover any deleted files in case needed