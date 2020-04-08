# Test-Hashing
Checking how hashing works

**Start By -**  
"npm install"   
"npm run dev"

const bcrypt = require('bcrypt')
const saltRounds = 10

Is the way to require it. Bcrypt is what i'm using. 

It does take some code and turn it into aa string of characters.

compaire the hash to a plan text passowrd and its the same it will return 'true' or 'false'