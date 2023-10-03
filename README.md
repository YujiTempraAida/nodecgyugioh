# nodecgyugioh
set database in nodecg root assets directory
https://github.com/Wildric-Auric/YuGiOh-Database
./assets/YuGiOh-Database-main/

# NodeCG Bundle Template

This is an unofficial [NodeCG](http://github.com/nodecg/nodecg) bundle template based on TypeScript, React, Vite originated from RTA in Japan Layouts.  

## Local development

Start the development build server/watcher

```sh
npm install
npm run dev
```
## How to use
1. change name from "nodecgbundletemplate" to your bundle name
   1.  directory name
   2.  name in package.json
   3.  src/extension/nodecg.d.ts
2. write your schemas
3. set your RaplicantMap in src/nodecg/replicants.d.ts
4. develop as you like in src directory
   1. modify MessageMap in src/nodecg/messages.d.ts as you create new messages
