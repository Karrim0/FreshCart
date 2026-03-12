# React + Vite + TypeScript Project

A modern web application scaffold built with React, Vite, TypeScript, Tailwind CSS, React Router, Axios, TanStack React Query, Zustand, and shadcn/ui components.

## Project Structure

```
src/
├── components/          # Reusable React components
│   ├── layout/         # Layout components (Navbar, Footer)
│   ├── products/       # Product-related components
│   ├── shared/         # Shared utility components
│   └── ui/             # shadcn/ui components
├── hooks/              # Custom React hooks
├── pages/              # Page components
├── stores/             # Zustand state management
├── i18n/              # Internationalization
├── lib/               # Utility functions and API setup
├── types/             # TypeScript type definitions
├── App.tsx            # Main App component
├── main.tsx           # Application entry point
└── index.css          # Global styles
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- pnpm (or npm/yarn)

### Installation

1. Install dependencies:
```bash
pnpm install
```

2. Start the development server:
```bash
pnpm dev
```

3. Build for production:
```bash
pnpm build
```

4. Preview production build:
```bash
pnpm preview
```

## Tech Stack

- **React 18** - UI library
- **Vite** - Build tool and dev server
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Axios** - HTTP client
- **TanStack React Query** - Server state management
- **Zustand** - Client state management
- **shadcn/ui** - Component library

## File Structure

This is a placeholder project structure. Each file contains minimal exports and is ready for implementation:

- Components use functional components with TypeScript
- Hooks export empty functions (ready for implementation)
- Pages are minimal placeholder components
- Stores use Zustand for state management
- API client is configured with Axios
- i18n folder is ready for translation setup

## Development Tips

1. **Components**: Add UI logic in `components/` directory
2. **State Management**: Use Zustand stores in `stores/` for global state
3. **Data Fetching**: Use React Query hooks with the configured API client
4. **Styling**: Tailwind CSS classes are available globally
5. **Routing**: Configure routes in `App.tsx` using React Router

## License

MIT

```
FreshCart
├─ app
│  ├─ globals.css
│  └─ layout.tsx
├─ components
│  ├─ theme-provider.tsx
│  └─ ui
│     ├─ accordion.tsx
│     ├─ alert-dialog.tsx
│     ├─ alert.tsx
│     ├─ aspect-ratio.tsx
│     ├─ avatar.tsx
│     ├─ badge.tsx
│     ├─ breadcrumb.tsx
│     ├─ button-group.tsx
│     ├─ button.tsx
│     ├─ calendar.tsx
│     ├─ card.tsx
│     ├─ carousel.tsx
│     ├─ chart.tsx
│     ├─ checkbox.tsx
│     ├─ collapsible.tsx
│     ├─ command.tsx
│     ├─ context-menu.tsx
│     ├─ dialog.tsx
│     ├─ drawer.tsx
│     ├─ dropdown-menu.tsx
│     ├─ empty.tsx
│     ├─ field.tsx
│     ├─ form.tsx
│     ├─ hover-card.tsx
│     ├─ input-group.tsx
│     ├─ input-otp.tsx
│     ├─ input.tsx
│     ├─ item.tsx
│     ├─ kbd.tsx
│     ├─ label.tsx
│     ├─ menubar.tsx
│     ├─ navigation-menu.tsx
│     ├─ pagination.tsx
│     ├─ popover.tsx
│     ├─ progress.tsx
│     ├─ radio-group.tsx
│     ├─ resizable.tsx
│     ├─ scroll-area.tsx
│     ├─ select.tsx
│     ├─ separator.tsx
│     ├─ sheet.tsx
│     ├─ sidebar.tsx
│     ├─ skeleton.tsx
│     ├─ slider.tsx
│     ├─ sonner.tsx
│     ├─ spinner.tsx
│     ├─ switch.tsx
│     ├─ table.tsx
│     ├─ tabs.tsx
│     ├─ textarea.tsx
│     ├─ toast.tsx
│     ├─ toaster.tsx
│     ├─ toggle-group.tsx
│     ├─ toggle.tsx
│     ├─ tooltip.tsx
│     ├─ use-mobile.tsx
│     └─ use-toast.ts
├─ components.json
├─ hooks
│  ├─ use-mobile.ts
│  └─ use-toast.ts
├─ index.html
├─ lib
│  └─ utils.ts
├─ next.config.mjs
├─ package.json
├─ pnpm-lock.yaml
├─ postcss.config.js
├─ postcss.config.mjs
├─ public
│  ├─ apple-icon.png
│  ├─ icon-dark-32x32.png
│  ├─ icon-light-32x32.png
│  ├─ icon.svg
│  ├─ placeholder-logo.png
│  ├─ placeholder-logo.svg
│  ├─ placeholder-user.jpg
│  ├─ placeholder.jpg
│  └─ placeholder.svg
├─ README.md
├─ src
│  ├─ App.tsx
│  ├─ components
│  │  ├─ layout
│  │  │  ├─ Footer.tsx
│  │  │  └─ Navbar.tsx
│  │  ├─ NavLink.tsx
│  │  ├─ products
│  │  │  ├─ ProductCard.tsx
│  │  │  └─ ProductGrid.tsx
│  │  ├─ shared
│  │  │  ├─ EmptyState.tsx
│  │  │  ├─ LoadingSkeleton.tsx
│  │  │  ├─ PaginationControls.tsx
│  │  │  ├─ ProtectedRoute.tsx
│  │  │  ├─ QuantitySelector.tsx
│  │  │  └─ RatingStars.tsx
│  │  └─ ui
│  │     └─ Button.tsx
│  ├─ hooks
│  │  ├─ useAddresses.ts
│  │  ├─ useAuth.ts
│  │  ├─ useCart.ts
│  │  ├─ useOrders.ts
│  │  ├─ useProducts.ts
│  │  ├─ useReviews.ts
│  │  └─ useWishlist.ts
│  ├─ i18n
│  │  ├─ I18nProvider.tsx
│  │  └─ translations.ts
│  ├─ index.css
│  ├─ lib
│  │  ├─ api.ts
│  │  ├─ endpoints.ts
│  │  └─ utils.ts
│  ├─ main.tsx
│  ├─ pages
│  │  ├─ AccountPage.tsx
│  │  ├─ AddressesPage.tsx
│  │  ├─ BrandsPage.tsx
│  │  ├─ CartPage.tsx
│  │  ├─ CategoriesPage.tsx
│  │  ├─ CheckoutPage.tsx
│  │  ├─ ForgotPasswordPage.tsx
│  │  ├─ HomePage.tsx
│  │  ├─ LoginPage.tsx
│  │  ├─ NotFound.tsx
│  │  ├─ OrdersPage.tsx
│  │  ├─ ProductDetailPage.tsx
│  │  ├─ ProductsPage.tsx
│  │  ├─ RegisterPage.tsx
│  │  └─ WishlistPage.tsx
│  ├─ stores
│  │  └─ authStore.ts
│  └─ types
│     └─ api.ts
├─ styles
│  └─ globals.css
├─ tailwind.config.ts
├─ tsconfig.json
└─ vite.config.ts

```