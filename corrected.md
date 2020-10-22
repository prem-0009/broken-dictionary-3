1. Cannot find module 'http-errors'.<br>
   `npm install`

2. mongoose is not defined at....models/word.js:3:20 <br>
   `const mongoose = require('mongoose');`

3. TypeError: cannot read property 'push' of undefined at.....at object....<br>routes/Words/wordRoutes.js:13:8<br>
   >  `added () in line 1 after Router`<br>

   `const router = require('express').Router();`

4. ReferenceError: getUpdateWord is not defined at object...Words/wordRoutes.js:24:31<br>
   >`added getUpdatedWord in `<br>

   `const {  getAllWords,  getSingleWord,  getUpdateWord,  getAddWord,  addWord,`<br>  `updateWord,  deleteWord } = require('./controllers/wordController');`<br>

5. ReferenceError: route is not defined.....at..Words/wordsRoutes.js:33:18<br>
   >`added r in route`<br>

   `module.exports = router;`

6. app.js:17.connect(env.MONGODB_URI,  <br>
   ReferenceError: env is not defined ...at app.js:15:12 <br>
   >`added`<br>
   `require('dotenv').config();`<br>
   `created .env file in the root folder`<br>

   >`MONGODB_URI=mongodb://localhost/dictionary-3   in .env `<br>

   >`added  'process' here--mongoose.connect(process.env.MONGODB_URI,`

7. ReferenceError: app is not defined at app.js:27:1
   >`added`<br>
   `const app = express()`

8. While trying to access--`http://localhost:3000/api/v1/words/get-words`<br>
   TypeError: res.json is not a function at wordController.js:9:27<br>
   >`  getAllWords: (res, req) => {`<br>

   >`res is before req`<br>

9. While trying to access single-word--`http://localhost:3000/api/v1/words/single-word/%205f90b5b7d5b5ec686dd99c82`<br>
    >Error:`{"confirmation":"fail","message":"Server Error","err":{"stringValue":"\" 5f90b5b7d5b5ec686dd99c82\"","kind":"ObjectId","value":" 5f90b5b7d5b5ec686dd99c82","path":"_id","reason":{}}}`<br>

   > `removed the spacing before the id`

10. while trying to update a word--`http://localhost:3000/v1/words/update/5f90b5b7d5b5ec686dd99c82`<br>
    >Not Found 404<br>

    >