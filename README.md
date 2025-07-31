# eCommerce Website

A modern, full-stack eCommerce website I built using the PERN stack (PostgreSQL, Express, React, Node.js). This project showcases a complete online shopping platform with advanced features, secure payment processing, and responsive design.

![Desktop](/website-demo-image/desktop.png)
![Mobile](/website-demo-image/mobile.png)
![Showcase1](/website-demo-image/1.png)
![Showcase2](/website-demo-image/2.png)

## Tech Stack

**Frontend:**
- Next.js 14 with TypeScript
- React 18 with Redux Toolkit
- Tailwind CSS for styling
- Framer Motion for animations
- Stripe integration for payments

**Backend:**
- Node.js with Express
- TypeScript
- PostgreSQL database
- JWT authentication
- Nodemailer for emails
- Google OAuth integration

## Features

### eCommerce Features
- **Categories & Subcategories:** Well-organized categories and subcategories for easy navigation.
- **Products:** Detailed product pages with options for different sizes and colors.
- **Payment Gateway:** Integrated with individual products and cart for secure transactions. ( Stripe )
- **Wishlist:** Option to save favorite products.
- **Special Deals:** Exclusive deals displayed on the homepage.
- **Banners:** Eye-catching banners to highlight promotions.
- **Responsive Design:** Modern and mobile-friendly layout.
- **Quantity Purchase:** Ability to purchase multiple quantities of a product.
- **Homepage Algorithms:** Various algorithms to display products dynamically on the homepage.
- **Filtering & Sorting:** Advanced filtering and sorting options on search and category pages.
- **JWT Session:** Secure user sessions with JWT.
- **Encrypted Passwords:** Enhanced security with password encryption.
- **OAuth Support:** Easy registration and sign-in with OAuth.
- **Payment on Delivery:** Option to pay upon delivery.
- **Order Tracking:** Track orders with a detailed orders page.
- **Order Summary:** Comprehensive order summary page.
- **Custom Checkout:** Tailored checkout experience.
- **Review System:** Post, delete, and edit reviews with a dedicated reviews page.
- **Dynamic Routing:** Smooth navigation with dynamic routing.
- **Product Quickview:** Quickly view product details and add to cart or go to the product page.
- **Active Review & Rating Calculation:** Backend will update variables required for algorithms to work properly, actively calculate rating's & frontend required parameters.

### Other Pages
- **Category Specific Page:** Detailed pages for each category.
- **Subcategory Page:** Dedicated pages for subcategories.
- **Blog:** Informative blog section.
- **Contact Page:** Easy-to-use contact form.
- **Services Page:** Overview of offered services.
- **About Us:** Information about the company.
- **Privacy Policy:** Details on data privacy.
- **Secure Payment Page:** Information on secure payment methods.
- **Terms and Conditions:** Detailed terms and conditions.
- **Refund and Cancellation Policy:** Policies on refunds and cancellations.

## Getting Started

### Prerequisites

Before running this application, make sure you have the following installed:
- Node.js (v18 or higher)
- PostgreSQL (v12 or higher)
- npm or yarn package manager

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/zakeenkhan/E-commerce_main.git
2. Navigate to the project directory:
   ```sh
   cd E-Commerce
3. Install dependencies for the server:
   ```sh
   cd Server & npm install
4. Install dependencies for the client:
   ```sh
   cd ../Client & npm install
5. Set up environment variables in a .env file for both server and client.

## Running the Application (Development)

1. Start the Server:
   ```sh
   cd Server & npm run dev
2. Start the client:
    ```sh
   cd Client & npm run dev

## Setting Up PostgreSQL Tables

1. Create a Database named 'ecommerce'.
2. Restore the Database using ecommerce.sql with Given SQL File.
3. Make sure PostgreSQL server is Running, Set up Environment Variables and done.

## Project Structure

```
E-Commerce/
├── Client/                 # Next.js frontend application
│   ├── app/               # Next.js 14 app directory
│   ├── components/        # Reusable React components
│   ├── controllers/       # Frontend logic controllers
│   ├── features/          # Redux slices and features
│   └── public/           # Static assets
├── Server/                # Node.js backend API
│   ├── controller/        # API controllers
│   ├── data/             # Database configuration
│   ├── middleware/       # Express middleware
│   ├── routes/           # API routes
│   ├── utils/            # Utility functions
│   └── validators/       # Input validation
├── website-demo-image/    # Demo screenshots
└── ecommerce.sql         # Database schema
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the LICENSE file for details.



## Environment Variables

### Client Environment Variables

- **BACKEND_URL** (Cors Requirement)
- **AUTH_KEY** (Authorization key for Secure Frontend & Backend Communication)
- **JWT_KEY** (JWT Key for Decryption and encryption)
- **NEXT_PUBLIC_FRONTEND_GOOGLE_CLIENT_ID** (Google Client ID For OAuth)
- **NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY** (Stripe Key for payment Gateway)
- **NEXT_PUBLIC_DOMAIN** (**Optional*** Frontend URL)

### Server Environment Variables

- **FRONTEND_SERVER_ORIGIN** (Frontend Server URL)
- **DB_USER** (Database UserName)
- **DB_PASS** (Database Password)
- **DB_HOST** (Database HostName)
- **DB_PORT** (Database Port)
- **DB_NAME** (Database Name)
- **SMTP_USER** (SMTP UserName (email) )
- **SMTP_SUPPORT** (Customer Support Email for Contact)
- **SMTP_HOST** (SMTP HostName)
- **SMTP_SENDERNAME** (SMTP Sender)
- **SMTP_PASS** (SMTP Password)
- **JWT_ENCRYPTION_KEY** (Key for secure encryption and decryption)
- **JWT_AUTH_KEY** (Authorization key for Secure Frontend & Backend Communication)
- **GOOGLE_CLIENT_ID** (Google Client ID for OAuth)
- **GOOGLE_CLIENT_SECRET** (Google Client Secret for OAuth)
- **STRIPE_PUBLISHABLE_KEY** (Stripe Key for Payment Gateway)
