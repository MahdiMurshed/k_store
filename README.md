# K Store

## To run the project:

```bash
cd frontend
npm install
npm run dev 
```

```bash
cd ../backend
npm install
npm run dev 
```

## Description

### Homepage
![home page](https://github.com/Toufiqul/k_store/blob/main/frontend/src/assets/home_page.png)

* You can add a product to your cart by pressing the "Add" button and the current cart price will be updated accordingly.
* After that you can click checkout button and you will be taken to the stripe payment page.

![stripe payment page](https://github.com/Toufiqul/k_store/blob/main/frontend/src/assets/stripe_payment_page.png)

* Upon a successful payment you will be taken to the success page.
![success page](https://github.com/Toufiqul/k_store/blob/main/frontend/src/assets/success_page.png)

* Failing that, the cancel page awaits
![cancel page](https://github.com/Toufiqul/k_store/blob/main/frontend/src/assets/cancel_page.png)

## Tech Stack
* Tailwind CSS
* React.js
* Express.js
* Vite
