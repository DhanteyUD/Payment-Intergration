# Payment Intergration with Node.
Payment Integration With Node, Express, Request and Paystack API

## Setup

* Create a <a href='https://dashboard.paystack.com/#/signup'>paystack account</a>
* Copy and update the secret key in `config/paystack.js`
* Install dependencies. Just run
<code>npm install</code>
from the root of the directory structure.
* Run the app
<code>node app</code>

> NB: Your `.env` file should look something like this:
```
DB_STRING=...
PAYSTACK_SECRET=...
PAYSTACK_BASE_URL=https://api.paystack.co
```

