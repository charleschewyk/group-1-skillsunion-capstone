### Guide Notes
Please clone the following branches to test the UI + localhost server:
Frontend UI: https://github.com/liewkm/group-1-skillsunion-capstone/tree/cp-postgres
Server (localhost:5000): https://github.com/liewkm/group-1-skillsunion-capstone/tree/leslie

DATABASE_URL=postgres://hkbyciuwlhdmdv:0465196b7f8069a6be2314a1266b8d6d1fa9abe261f351a378c4ea95089548e0@ec2-107-22-238-112.compute-1.amazonaws.com:5432/d925mld72inqtj

Instruction: 
`/client <= run from terminal mock react`
`/server/src <= run from terminal mock backend`

Insert 2 files into server folder:

`.env` file in `/server`
`serviceAccKey.json` in `/server/config/`


- Copy ExpenseTrackerApp/api/expenses-api-postgres.js --> `expenses-api.js`
- Copy `.env` file (above thread) into server/
- Open terminal 1:
    - `cd server`
    - `npm install`
    - `npm start`
- Open terminal 2:
    - `cd ExpenseTrackerApp`
    - `npm install`
    - `expo start`

Windows & Expo
When error exists in Window Development platforms, Expo cannot run. 
Use the following to set permissions

```
Set-ExecutionPolicy -ExecutionPolicy Unrestricted
4:54
react-native start --reset-cache
```