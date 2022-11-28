# MoneyHouse (Backend Repositery)
Developed Using MERN Stack <br/>
MoneyHouse - it involves a group of people where each person contributes a certain amount of money towards a pool of funds On a Monthly Basis and the Pool amount is collected. 
A Reverse auction happens among the members to grant this pool Amount to any of the members in the group. 
This Auction occurs for those members who have not taken the pool once and other benefited members have to pay their contribution every time.



## # Local Setup
### 1) Clone this Repo 
git clone https://github.com/priteshyadav444/api-moneyhouse.git
### 2) Create .env file provide all the importent key like for payment gatway, databases and other keys
**MongoDB URI SECRET_KEY For Encryption**
-   MONGO_URI = XXXXXXXXXXXXXXXXXX
-   SECRET_KEY = XXXXXXXXXXXXXXXXXXXX

**Nodemailer Credential**
-   NODEMAILER_USER = XXXXXXXXXXXXXXXXXX
-   NODEMAILER_PASS = XXXXXXXXXXXXXXXXXX 

**Paytm Payment Gateway Credential**
-   MERCHANT_ID = XXXXXXXXXXXXXXXXXX
-   MERCHANT_KEY = XXXXXXXXXXXXXXXXXX 
-   CALLBACKURL = https://moneyhouse-in.herokuapp.com 
-   DBKEY = XXXXXXXXXXXXXXXXXX

### 3) Install Modules ( Backend)
      cd backend-folder
      npm install
  
### 4) Start Backend using following command
  *npm run dev*
  ```javascript
    package.json File
      "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "server": "nodemon server.js",
        "start": "nodemon server.js"
      }

```
