# BookDiverse

**BookDiverse** is a student demo project built for learning and practicing frontend web development. This is an e-commerce platform concept for buying and selling books online.

---

## ⚠️ Important Notice

**This is a demonstration project for educational purposes only.**

- **DO NOT** enter real passwords, email addresses, or payment information
- **NO** real transactions are processed
- **NO** personal data is collected or stored
- All functionality is frontend-only with no backend integration

---

## 📖 Project Overview

BookDiverse is a multi-page website showcasing a modern online bookstore interface. The project demonstrates key frontend development skills including responsive design, form handling, navigation flows, and consistent UI/UX patterns.

### Purpose

This project was created to:
- Practice HTML5 semantic markup
- Develop CSS styling and layout skills
- Implement responsive design using Bootstrap framework
- Create consistent navigation and footer components across multiple pages
- Build user flows for authentication, shopping, and vendor management

---

## 📄 Pages Included

### Customer Pages
- **index.html** - Landing page with hero section and book categories
- **homepage.html** - Main home page with featured books and bookstores
- **login.html** - User login page
- **signup.html** - User registration page
- **forgotpassword.html** - Password recovery request
- **verification.html** - PIN verification page
- **newpassword.html** - New password creation
- **passwordresetsuccess.html** - Password reset confirmation
- **bookdescription.html** - Individual book details page
- **bookstoredetail.html** - Bookstore information and available books
- **shoppingcart.html** - Shopping cart with item management
- **checkout.html** - Checkout step 1 (cart review and address)
- **checkout2.html** - Checkout step 2 (billing details)
- **ordercomplete.html** - Order confirmation page
- **userprofile.html** - User profile and account information

### Vendor Pages
- **vendorsignup.html** - Vendor registration form
- **vendordescription.html** - Vendor store description setup
- **vendordashboard.html** - Vendor analytics and order management dashboard

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling and layouts
- **Bootstrap 5.3.8** - Responsive grid system and components
- **Google Fonts** - Raleway font family for typography
- **Responsive Design** - Mobile-first approach with breakpoints

---

## 🚀 How to Run

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- No server or installation required

### Steps

1. **Download or Clone the Project**
   ```
   Download the project folder or clone it to your local machine
   ```

2. **Navigate to the Project Folder**
   ```
   Open the project directory in your file explorer
   ```

3. **Open in Browser**
   - Double-click on `index.html` to open the landing page
   - OR right-click any HTML file and select "Open with" → your preferred browser
   - OR use a local development server (e.g., VS Code Live Server extension)

4. **Navigate Between Pages**
   - Use the navigation menu to explore different pages
   - Click links and buttons to experience the user flows

---

## 📁 Project Structure

```
project/
│
├── index.html                    # Landing page (entry point)
├── homepage.html                 # Main home page
├── login.html                    # Login page
├── signup.html                   # Sign up page
├── forgotpassword.html           # Forgot password
├── verification.html             # Verification page
├── newpassword.html              # New password page
├── passwordresetsuccess.html     # Password reset success
├── bookdescription.html          # Book details
├── bookstoredetail.html          # Bookstore details
├── shoppingcart.html             # Shopping cart
├── checkout.html                 # Checkout step 1
├── checkout2.html                # Checkout step 2
├── ordercomplete.html            # Order complete
├── userprofile.html              # User profile
├── vendorsignup.html             # Vendor signup
├── vendordescription.html        # Vendor description
├── vendordashboard.html          # Vendor dashboard
├── project-note.txt              # Project notes
├── README.md                     # This file
│
└── assets/
    ├── css/                      # Stylesheets
    │   ├── nav.css              # Navigation bar styles
    │   ├── footer.css           # Footer styles
    │   ├── homepage.css         # Homepage styles
    │   ├── landingpage.css      # Landing page styles
    │   ├── bookdescription.css  # Book description styles
    │   ├── shoppingcart.css     # Shopping cart styles
    │   ├── checkout.css         # Checkout styles
    │   └── ...                  # Other page-specific styles
    │
    └── images/                   # Image assets
        ├── shared/              # Shared images (logos, icons)
        ├── homepagepic/         # Homepage images
        ├── landingpagepic/      # Landing page images
        ├── bookstoredetail/     # Bookstore detail images
        ├── bkdescription/       # Book description images
        └── buyerprofilepics/    # Profile pictures
```

---

## ✨ Features

### Design & UI
- **Responsive Layout** - Works on desktop, tablet, and mobile devices
- **Consistent Navigation** - Reusable navbar component across pages
- **Unified Footer** - Shared footer with links and social media icons
- **Modern Color Scheme** - Pink/coral accent colors (#f06d82, #f3687f)

### User Flows
- **Authentication Flow** - Login → Signup → Forgot Password → Verification → New Password → Success
- **Shopping Flow** - Browse → Book Details → Add to Cart → Checkout (2 steps) → Order Complete
- **Vendor Flow** - Vendor Signup → Description → Dashboard

### Components
- Book cards with images and pricing
- Category browsing sections
- Featured bookstores display
- Shopping cart with quantity controls
- Multi-step checkout process
- Vendor analytics dashboard

---

## 🎨 Color Palette

- **Primary Pink**: `#f06d82`, `#f3687f`
- **Text Dark**: `#000000`
- **Text Light**: `#ffffff`
- **Backgrounds**: White, light grays, pink accents

---

## 📱 Responsive Breakpoints

The project uses Bootstrap's standard breakpoints:
- **xs**: < 576px (Mobile)
- **sm**: ≥ 576px (Small tablets)
- **md**: ≥ 768px (Tablets)
- **lg**: ≥ 992px (Desktops)
- **xl**: ≥ 1200px (Large desktops)

---

## 🔗 External Dependencies

All dependencies are loaded via CDN (no installation required):

- **Bootstrap 5.3.8**
  - CSS: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css`
  - JS: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js`

- **Google Fonts - Raleway**
  - `https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap`

---

## 📝 Notes for Developers

1. **Shared CSS Files**: `nav.css` and `footer.css` are reused across multiple pages for consistency
2. **Bootstrap Integration**: The project uses Bootstrap's grid system and utility classes extensively
3. **Image Paths**: All images are referenced relatively from the `assets/images/` directory
4. **No JavaScript Logic**: This is a static frontend demo with no client-side scripting (except Bootstrap's JS)
5. **Form Actions**: Forms do not submit data anywhere - they are for demonstration only

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

- ✅ HTML5 semantic elements and structure
- ✅ CSS3 styling, flexbox, and custom properties
- ✅ Bootstrap framework for rapid UI development
- ✅ Responsive web design principles
- ✅ Component reusability (nav, footer)
- ✅ User experience flows and page transitions
- ✅ Form design and input validation (UI only)
- ✅ Multi-page website organization

---

## 📜 License & Credits

**BookDiverse** is a student project created for educational purposes.

- **Author**: Paul Olutunmbi (DevHumble3)
- **Year**: 2025
- **Status**: Demo/Portfolio Project
- **Usage**: Free to reference for learning purposes

**Disclaimer**: This project is not affiliated with any real bookstore or e-commerce platform. All content, including book titles, prices, and store names, is fictional and used solely for demonstration purposes.

---

## 🙏 Acknowledgments

- **Bootstrap Team** - For the excellent CSS framework
- **Google Fonts** - For the Raleway typeface
- **Unsplash** - For placeholder images (where applicable)

---

## 📞 Support

This is a static demo project with no active support. For educational reference only.

---

**Remember: This is a demonstration project. Do not enter real personal information, passwords, or payment details.**
