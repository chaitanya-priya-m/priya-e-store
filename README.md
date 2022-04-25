# priya e-store a ECommerce Website

## Run Locally


### 1. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/e-commerce  

### 2. Run Backend and Frontend

```
$ npm install
$ npm run start:server
open new terminal
$ npm run start:client
```

### 3. Seed Users and Products

- Run this on chrome: http://localhost:5000/api/users/seed
- It returns admin email and password
- Run this on chrome: http://localhost:5000/api/products/seed
- It creates 6 sample products

### 4. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin