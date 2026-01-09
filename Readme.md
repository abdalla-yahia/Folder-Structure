📂 Project Structure
This project follows a Modular Architecture pattern to ensure scalability, maintainability, and clear separation of concerns. Below is a detailed map of the directory structure.

🌳 Directory Tree
```
src/
├── App.ts                 # Main Application entry component
├── index.ts               # Project bootstrap file
│   
├── 📁 Assets/             # Static assets
│   ├── 📁 Audios/         # Sound files
│   ├── 📁 Icons/          # SVG and icon files
│   ├── 📁 Images/         # Graphic assets (JPG, PNG, etc.)
│   └── 📁 Jsons/          # Static JSON data files
│
├── 📁 Layouts/            # Global page layouts
│   ├── 📁 Footer/         # Global Footer component & styles
│   └── 📁 Header/         # Global Header component & styles
│
├── 📁 Modules/            # Core business logic (Feature-based modules)
│   ├── 📁 Auth/           # Authentication module (Login, Register, etc.)
│   ├── 📁 Branches/       # Branch management
│   ├── 📁 Cash/           # Cash & Treasury management
│   ├── 📁 Coupons/        # Discount & Coupon system
│   ├── 📁 Customers/      # Customer management
│   ├── 📁 Inventory/      # Warehouse & Stock management
│   ├── 📁 Pos/            # Point of Sale interface
│   ├── 📁 Purchases/      # Procurement & Purchase orders
│   ├── 📁 Sales/          # Sales tracking & Invoices
│   ├── 📁 Users/          # System users & Permissions
│   └── ... (Other modules follow the same internal structure below)
│       │
│       ├── index.ts       # Module entry point
│       ├── 📁 Components/ # Module-specific components
│       ├── 📁 Hooks/      # Custom hooks for this module
│       ├── 📁 Interfaces/ # TypeScript types and interfaces
│       ├── 📁 Pages/      # View components (Screens)
│       ├── 📁 Router/     # Module internal routing
│       ├── 📁 Services/   # API calls specific to this module
│       ├── 📁 Store/      # State management (Actions & Slices)
│       └── 📁 Validation/ # Form validation schemas (Yup/Zod)
│
├── 📁 Routers/            # Global routing configuration
│
├── 📁 Services/           # Shared API clients and base configurations
│
├── 📁 Shared/             # Global reusable resources
│   ├── 📁 Components/     # Complex shared components (e.g., Main-Table)
│   ├── 📁 Constants/      # Global constants and ENUMs
│   ├── 📁 Hooks/          # Global utility hooks
│   ├── 📁 Ui/             # Atomic UI components (Buttons, Loaders, etc.)
│   └── 📁 Utils/          # Helper functions and formatting utilities
│
├── 📁 Store/              # Global state management (Redux/Toolkit)
│   ├── Store.ts           # Root store configuration
│   ├── 📁 Actions/        # Global actions
│   └── 📁 Slices/         # Global state slices
│
├── 📁 Styles/             # Global CSS and theming
└── 📁 Validators/         # Global validation rules
```

Edit To Test in Branch Test2 (1)
Edit To Test in Branch Test2 (2)