# 🍰 Sweet Treats - Artisan Bakery Website

A fully functional e-commerce bakery website with admin panel built using HTML, CSS, and JavaScript.

![Sweet Treats](https://images.unsplash.com/photo-1517433670267-08bbd4be890f?q=80&w=1200&auto=format&fit=crop)

## ✨ Features

### 🛍️ Customer Features
- Browse products with **search & filter** functionality
- **Shopping cart** with localStorage persistence
- **Coupon code system** (6 active coupons)
- **User authentication** (Register/Login)
- **Review system** with admin approval
- **Responsive design** for all devices
- Smooth animations and modern UI

### 👨‍💼 Admin Features
- **Dashboard** with real-time statistics
- **Product Management** (Add/Edit/Delete)
- **Order Management** with customer details
- **Customer Management** with order history
- **Review Management** (Approve/Reject)
- **Sales Analytics** with Chart.js
- **Store Settings** configuration

## 🎟️ Coupon Codes

Try these codes at checkout:
- `WELCOME10` - 10% off for all customers
- `SWEET20` - 20% off for all customers
- `BULK20` - 20% off on 5+ items
- `SAVE50` - ₹50 flat discount

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/henilraiyani7/sweet-treats.git
   cd sweet-treats
   ```

2. **Open in browser**
   ```bash
   # Simply open html/index.html in your browser
   # Or use Live Server in VS Code
   ```

3. **Admin Panel**
   ```bash
   # Open html/admin-panel.html
   ```

## 📁 Project Structure

```
SweetTreats/
├── html/                    # All HTML pages
│   ├── index.html          # Homepage
│   ├── menu.html           # Product catalog
│   ├── shop.html           # Shopping page
│   ├── about.html          # About page
│   ├── contact.html        # Contact page
│   └── admin-panel.html    # Admin dashboard
├── css/                     # Stylesheets
│   ├── style.css           # Main styles
│   └── admin-style.css     # Admin styles
├── js/                      # JavaScript files
│   ├── script.js           # Main functionality
│   ├── auth.js             # Authentication
│   ├── products.js         # Product management
│   ├── reviews.js          # Review system
│   └── admin-script.js     # Admin operations
├── docs/                    # Documentation
└── README.md               # This file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox & Grid
- **JavaScript (ES6+)** - Vanilla JS, no frameworks
- **Bootstrap 5.3.0** - UI components & responsive design
- **Font Awesome 6.4.0** - Icons
- **LocalStorage API** - Data persistence
- **Chart.js** - Analytics charts

## 💾 Data Storage

All data is stored in browser's localStorage:

| Key | Description |
|-----|-------------|
| `bakery_users` | Registered users |
| `bakery_current_user` | Active session |
| `bakery_products` | Product catalog |
| `bakery_cart` | Shopping cart items |
| `bakery_orders` | Customer orders |
| `bakery_reviews` | Customer reviews |

## 📱 Pages Overview

| Page | Description |
|------|-------------|
| **index.html** | Homepage with hero, features, testimonials |
| **menu.html** | Complete product catalog with filters |
| **shop.html** | Shopping page with popular items |
| **about.html** | About the bakery |
| **contact.html** | Contact form & information |
| **admin-panel.html** | Complete admin dashboard |

## 🧪 Testing

Test files are included:
- `test-cart.html` - Cart functionality
- `test-products.html` - Product loading
- `test-reviews.html` - Review system
- `test-validation.html` - Form validation

## 📖 Documentation

Detailed documentation available in `/docs`:
- Implementation guides
- Feature documentation
- Testing instructions
- User flow diagrams

## 🔒 Security Notes

⚠️ **Important**: This is a demonstration project.

**Current Implementation:**
- Passwords stored in plain text (localStorage)
- No backend server
- Client-side validation only

**For Production:**
- [ ] Implement password hashing (bcrypt)
- [ ] Add backend API (Node.js/Express)
- [ ] Server-side validation
- [ ] Use HTTPS
- [ ] Implement CSRF protection
- [ ] Add rate limiting
- [ ] Use secure session management (JWT)

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 🚀 Deployment

### GitHub Pages
1. Go to repository Settings
2. Navigate to Pages section
3. Select `main` branch
4. Click Save
5. Your site will be live at `https://henilraiyani7.github.io/sweet-treats/html/index.html`

### Netlify
1. Drag & drop the project folder to Netlify
2. Set publish directory to `html`
3. Deploy!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Your Name**
- GitHub: [@henilraiyani7](https://github.com/henilraiyani7)
- LinkedIn: [Henil Raiyani](https://linkedin.com/in/henilraiyani)

## 🙏 Acknowledgments

- Images from [Unsplash](https://unsplash.com)
- Icons from [Font Awesome](https://fontawesome.com)
- Fonts from [Google Fonts](https://fonts.google.com)

## 📧 Contact

For any queries, reach out at: henilraiyani7.email@example.com

---

⭐ **Star this repo if you find it helpful!**

Made with ❤️ by [Henil Raiyani]
