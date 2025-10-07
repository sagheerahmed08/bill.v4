# Bill.v4 - Digital Billing System for Dress Shops

[![Deployed on GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-blue)](https://sagheerahmed08.github.io/bill.v4/)
[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-6.3.5-646CFF?logo=vite)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.3.3-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)

## 📖 Project Description

Bill.v4 is a modern, full-featured digital billing web application specifically designed for dress shops and retail businesses. The application provides an intuitive interface for managing all aspects of retail operations including product inventory, customer management, invoice generation, sales tracking, and shop settings. Built with modern web technologies, it offers a seamless experience for streamlining retail business operations.

### Key Highlights
- **Modern UI/UX**: Clean, responsive interface built with React and TailwindCSS
- **Real-time Data**: Powered by Supabase for instant data synchronization
- **Print-Ready Invoices**: Generate professional invoices with print functionality
- **Dashboard Analytics**: Comprehensive overview of sales and business metrics
- **Mobile Responsive**: Works seamlessly across all devices

## 🚀 Tech Stack

### Frontend Framework
- **React 18.2.0** - Modern UI library for building interactive interfaces
- **React Router DOM 6.16.0** - Client-side routing
- **React DOM 18.2.0** - DOM-specific methods

### Styling & Design
- **TailwindCSS 3.3.3** - Utility-first CSS framework
- **PostCSS 8.4.31** - CSS transformations
- **Autoprefixer 10.4.16** - Vendor prefix automation
- **Framer Motion 10.16.4** - Animation library
- **Lucide React 0.285.0** - Icon library
- **Tailwind Merge 1.14.0** - Merge utility classes
- **Tailwindcss Animate 1.0.7** - Animation utilities

### UI Components
- **Radix UI** - Unstyled, accessible component library
  - Alert Dialog, Avatar, Checkbox, Dialog
  - Dropdown Menu, Label, Radio Group
  - Slider, Slot, Tabs, Toast
- **Class Variance Authority 0.7.0** - Component variant management

### Backend & Database
- **Supabase 2.39.0** - Backend-as-a-Service (PostgreSQL database, Authentication, Real-time subscriptions)

### Build Tools & Development
- **Vite 6.3.5** - Next-generation frontend build tool
- **@vitejs/plugin-react 4.0.3** - React plugin for Vite
- **ESLint 8.57.1** - Code linting
- **Terser 5.39.0** - JavaScript minification

### Utilities
- **UUID 9.0.1** - Unique identifier generation
- **React to Print 2.14.15** - Print functionality
- **clsx 2.0.0** - Conditional class names

## 📁 File Structure

```
bill.v4/
│
├── .github/
│   └── workflows/          # GitHub Actions workflows for CI/CD
│       └── deploy.yml      # Deployment configuration
│
├── node_modules/           # Project dependencies (auto-generated)
│
├── public/                 # Static assets
│   ├── images/            # Image files
│   └── favicon.ico        # Site favicon
│
├── src/                   # Source code directory
│   ├── components/        # React components
│   │   ├── ui/           # Reusable UI components
│   │   ├── layout/       # Layout components
│   │   ├── dashboard/    # Dashboard-specific components
│   │   ├── billing/      # Billing and invoice components
│   │   └── forms/        # Form components
│   │
│   ├── contexts/         # React Context providers
│   │   ├── AuthContext.jsx
│   │   └── DataContext.jsx
│   │
│   ├── hooks/            # Custom React hooks
│   │   ├── useAuth.js
│   │   └── useData.js
│   │
│   ├── lib/              # Library configurations
│   │   └── supabase.js   # Supabase client setup
│   │
│   ├── utils/            # Utility functions
│   │   ├── helpers.js    # Helper functions
│   │   └── formatters.js # Data formatting utilities
│   │
│   ├── edit_sale/        # Sale editing functionality
│   │
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # Application entry point
│   └── index.css         # Global styles
│
├── .gitignore            # Git ignore configuration
├── index.html            # HTML entry point
├── package.json          # Project dependencies and scripts
├── package-lock.json     # Locked dependency versions
├── postcss.config.js     # PostCSS configuration
├── tailwind.config.js    # TailwindCSS configuration
├── vite.config.js        # Vite build configuration
└── README.md             # Project documentation (this file)
```

## 🛠️ Installation and Setup

### Prerequisites
- **Node.js** (v16 or higher recommended)
- **npm** (v8 or higher) or **yarn**
- **Git**

### Step 1: Clone the Repository
```bash
git clone https://github.com/sagheerahmed08/bill.v4.git
cd bill.v4
```

### Step 2: Install Dependencies
```bash
npm install
```

Or using yarn:
```bash
yarn install
```

### Step 3: Environment Configuration
Create a `.env` file in the root directory and add your Supabase credentials:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Step 4: Run the Development Server
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## 📝 Development Commands

### Start Development Server
Runs the app in development mode with hot module replacement:
```bash
npm run dev
```

### Build for Production
Creates an optimized production build in the `dist/` directory:
```bash
npm run build
```

### Preview Production Build
Locally preview the production build:
```bash
npm run preview
```

### Lint Code
Run ESLint to check code quality:
```bash
npm run lint
```

## 💻 Usage Instructions

### Getting Started

1. **Access the Application**
   - Visit the deployed app at: https://sagheerahmed08.github.io/bill.v4/
   - Or run locally using `npm run dev`

2. **Initial Setup**
   - Configure your shop settings (name, address, contact information)
   - Set up your product catalog
   - Add customer information

3. **Creating Bills/Invoices**
   - Navigate to the billing section
   - Select or add customer details
   - Add products to the invoice
   - Calculate totals automatically
   - Generate and print invoice

4. **Managing Products**
   - Add new products with details (name, price, quantity)
   - Edit existing products
   - Track inventory levels
   - Organize by categories

5. **Customer Management**
   - Add new customers with contact information
   - View customer purchase history
   - Manage customer profiles

6. **Sales Tracking**
   - View sales dashboard
   - Analyze sales trends
   - Generate sales reports
   - Track revenue over time

### Navigation
- **Dashboard**: Overview of business metrics and recent activity
- **Billing**: Create new invoices and manage billing
- **Products**: Manage product inventory
- **Customers**: Customer database management
- **Sales**: View and analyze sales history
- **Settings**: Configure shop and application settings

## ✨ Sample Features

### 1. **Dashboard**
   - Real-time sales statistics
   - Recent transactions overview
   - Revenue charts and analytics
   - Quick access to common actions

### 2. **Billing System**
   - Dynamic invoice generation
   - Auto-calculation of totals, taxes, and discounts
   - Print-ready invoice format
   - Customer selection and management
   - Product search and quick add

### 3. **Product Management**
   - Add/Edit/Delete products
   - Product categorization
   - Inventory tracking
   - Price management
   - Product search and filtering

### 4. **Customer Database**
   - Customer profile management
   - Purchase history tracking
   - Contact information storage
   - Search and filter customers

### 5. **Sales History**
   - Comprehensive sales records
   - Date-range filtering
   - Invoice editing capabilities
   - Sales analytics and reports
   - Export functionality

### 6. **Shop Settings**
   - Business information configuration
   - Invoice template customization
   - Tax rate settings
   - User preferences

### 7. **Responsive Design**
   - Mobile-friendly interface
   - Tablet optimization
   - Desktop full-feature experience

### 8. **Print Functionality**
   - Professional invoice printing
   - Customizable print layout
   - Browser print dialog integration

## 🤝 Contribution Guidelines

### How to Contribute

We welcome contributions from the community! Here's how you can help:

1. **Fork the Repository**
   ```bash
   # Click the 'Fork' button on GitHub
   git clone https://github.com/YOUR_USERNAME/bill.v4.git
   cd bill.v4
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
   
   Use descriptive branch names:
   - `feature/add-export-functionality`
   - `bugfix/invoice-calculation-error`
   - `enhancement/improve-dashboard-ui`

3. **Make Your Changes**
   - Write clean, readable code
   - Follow the existing code style
   - Add comments where necessary
   - Test your changes thoroughly

4. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Add: description of your changes"
   ```
   
   Commit message conventions:
   - `Add:` for new features
   - `Fix:` for bug fixes
   - `Update:` for updates to existing features
   - `Refactor:` for code refactoring
   - `Docs:` for documentation changes

5. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request**
   - Go to the original repository on GitHub
   - Click "New Pull Request"
   - Select your fork and branch
   - Provide a clear description of your changes
   - Reference any related issues

### Code Standards

- **JavaScript/React**: Follow ES6+ standards
- **Styling**: Use TailwindCSS utility classes
- **Components**: Create reusable, modular components
- **Naming**: Use descriptive variable and function names
- **Comments**: Add JSDoc comments for functions

### Testing Guidelines

- Test all new features thoroughly
- Ensure existing functionality isn't broken
- Test on different screen sizes (mobile, tablet, desktop)
- Verify print functionality works correctly

### Reporting Issues

Found a bug or have a suggestion?
1. Check if the issue already exists
2. Create a new issue with:
   - Clear, descriptive title
   - Steps to reproduce (for bugs)
   - Expected vs actual behavior
   - Screenshots if applicable
   - Your environment details (browser, OS)

### Code Review Process

- All PRs require review before merging
- Address review comments promptly
- Keep PRs focused on a single feature/fix
- Update documentation as needed

## 📄 License

This project is private and proprietary. All rights reserved.

## 👨‍💻 Author

**Sagheer Ahmed**
- GitHub: [@sagheerahmed08](https://github.com/sagheerahmed08)
- Project Link: [https://github.com/sagheerahmed08/bill.v4](https://github.com/sagheerahmed08/bill.v4)
- Live Demo: [https://sagheerahmed08.github.io/bill.v4/](https://sagheerahmed08.github.io/bill.v4/)

## 🙏 Acknowledgments

- Built with [React](https://reactjs.org/)
- Styled with [TailwindCSS](https://tailwindcss.com/)
- Powered by [Supabase](https://supabase.com/)
- UI Components from [Radix UI](https://www.radix-ui.com/)
- Icons from [Lucide](https://lucide.dev/)

---

**Note**: For any questions or support, please open an issue on GitHub.

**Last Updated**: October 2025
