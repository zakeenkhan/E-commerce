# eCommerce Website

A modern, full-stack eCommerce website built using the PERN stack (PostgreSQL, Express, React, Node.js). This project demonstrates a complete online shopping platform with advanced features, secure payment processing, and responsive design.

## 🚀 Live Demo

**[View Live Demo](https://harman-ecommerce.vercel.app/)**

Experience the full functionality of this eCommerce platform with our live demonstration.

![Desktop](/website-demo-image/desktop.png)
![Mobile](/website-demo-image/mobile.png)
![Showcase1](/website-demo-image/1.png)
![Showcase2](/website-demo-image/2.png)

## 🛠️ Tech Stack

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

## ✨ Features

### Core eCommerce Functionality
- **Product Catalog:** Organized categories and subcategories with detailed product pages
- **Shopping Cart & Wishlist:** Full cart functionality with wishlist management
- **Secure Payments:** Stripe integration with multiple payment options including cash on delivery
- **User Authentication:** JWT-based sessions with Google OAuth support
- **Order Management:** Complete order tracking and management system
- **Review System:** Customer reviews with rating calculations
- **Search & Filter:** Advanced product filtering and sorting capabilities
- **Responsive Design:** Mobile-first approach with modern UI/UX

### Additional Features
- Real-time deal notifications
- Dynamic homepage algorithms
- Product quick-view functionality
- Comprehensive admin dashboard
- Email notifications
- Multi-language support ready
- SEO optimized

## 📄 Additional Pages
- Category and subcategory pages
- Blog section
- Contact form
- Services overview
- About us
- Privacy policy
- Terms and conditions
- Refund policy

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- PostgreSQL (v12 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/zakeenkhan/E-commerce_main.git
   ```

2. Navigate to the project directory:
   ```bash
   cd E-Commerce
   ```

3. Install server dependencies:
   ```bash
   cd Server && npm install
   ```

4. Install client dependencies:
   ```bash
   cd ../Client && npm install
   ```

5. Configure environment variables (see Environment Variables section below)

### Development Setup

1. Start the backend server:
   ```bash
   cd Server && npm run dev
   ```

2. Start the frontend application:
   ```bash
   cd Client && npm run dev
   ```

### Database Setup

1. Create a PostgreSQL database named 'ecommerce'
2. Import the database schema using the provided `ecommerce.sql` file
3. Ensure PostgreSQL server is running and environment variables are configured


## 🔧 Environment Variables

### Client (.env.local)
```env
BACKEND_URL=your_backend_url
AUTH_KEY=your_auth_key
JWT_KEY=your_jwt_key
NEXT_PUBLIC_FRONTEND_GOOGLE_CLIENT_ID=your_google_client_id
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_key
NEXT_PUBLIC_DOMAIN=your_frontend_url
```

### Server (.env)
```env
FRONTEND_SERVER_ORIGIN=your_frontend_url
DB_USER=your_db_username
DB_PASS=your_db_password
DB_HOST=your_db_host
DB_PORT=your_db_port
DB_NAME=your_db_name
SMTP_USER=your_smtp_email
SMTP_SUPPORT=your_support_email
SMTP_HOST=your_smtp_host
SMTP_SENDERNAME=your_sender_name
SMTP_PASS=your_smtp_password
JWT_ENCRYPTION_KEY=your_jwt_encryption_key
JWT_AUTH_KEY=your_jwt_auth_key
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
STRIPE_PUBLISHABLE_KEY=your_stripe_key
```

## 📝 License

This project is licensed under the MIT License. See the LICENSE file for details.

## 👨‍💻 Author

**Made with ❤️ by [Zakeen Khan](https://github.com/zakeenkhan)**

---

*This project showcases modern web development practices and serves as a comprehensive example of a full-stack eCommerce solution.*

