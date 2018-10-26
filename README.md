1. yarn (or npm) install
2. building TS works without error in any of these ways
  * `npm run build`
  * `./node_modules/.bin/tsc`
  * In VScode, use the build task
3. In vscode, Rename index.ts to index2.ts and watch TS fail to find modules it hould be able to find. Need to 'reload' vscode to fix.
