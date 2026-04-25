# APEX Tip Me Link

**A simple, customizable web page to accept tips via Stripe.** 

Ideal for creators, freelancers, and anyone needing a quick 'donate' button without complex e-commerce. Users can set their name, description, and profile picture. Integrated with Stripe Checkout for secure payments.

**Features:**
- Customizable name, description, and profile image.
- Simple tip amount input.
- Secure payments powered by Stripe Checkout.
- Minimalist, responsive design.

**Setup:**
1. Replace `pk_test_TYooMQauvdEDq54NiTgbpRQN` with your Stripe publishable key in `index.html`.
2. Implement a backend endpoint (`/create-checkout-session`) to create Stripe Checkout Sessions (e.g., using Vercel Serverless Functions). This endpoint should accept an amount and description, and return a `sessionId`.

Enjoy a streamlined way to get paid for your passion!
