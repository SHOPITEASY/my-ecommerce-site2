# my-ecommerce-site2
# My Ecommerce Site

A minimal e-commerce platform with client-side HTML/CSS/JS and Supabase backend.

## Features

- Browse products on the homepage (index.html)
- Customer signup and login (signup.html, login.html) powered by Supabase Auth
- Add items to a cart (cart.html) with fake "Pay M-Pesa" integration
- Admin page to add new products (admin.html)

## Technologies

- HTML/CSS/JavaScript
- [Supabase](https://supabase.io) (database and authentication)
- LocalStorage for simple cart functionality

## Setup

1. Clone the repository and open `index.html` in your browser.
2. Set up a database table called `products` in Supabase with at least columns: `id`, `name`, `price`, `image`.
3. Create a Supabase project; copy your project URL and public anon key into `supabase.js`.
4. (Optional) Replace the M-Pesa integration in `cart.html` with your real payment API.

## File Structure

```plaintext
my-ecommerce-site/
├── index.html
├── login.html
├── signup.html
├── cart.html
├── admin.html
├── style.css
├── supabase.js
└── README.md
```

---

**Replace `SUPABASE_URL` and `SUPABASE_KEY` in `supabase.js` with your real credentials before deploying!**
