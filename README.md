# COST-IT Mobile

🏗️ **COST-IT** — A Full-Stack E-Commerce Marketplace for the Construction Industry.

COST-IT is a digital-first construction commerce platform built in Flutter that empowers suppliers, contractors, and individual buyers to seamlessly buy, sell, and procure construction materials, heavy equipment, and professional services in one trusted ecosystem.

---

## 📁 Project Architecture (Portfolio Showcase)

> **Note:** To respect company confidentiality and intellectual property, proprietary business logic and internal credentials have been omitted from this public repository. The complete directory tree, modular feature structure, and `.dart` file layout are preserved to showcase the application's architecture and engineering contributions.

```text
lib/
├── app/                  # Root application setup, theme configuration & splash orchestration
├── components/           # Reusable navigation shells, drawers & shared UI components
├── constants/            # Application-wide design tokens, constants & asset paths
├── extensions/           # Dart & Flutter convenience extensions
├── feature/              # Feature-first modular architecture
│   ├── account/          # User profile, saved addresses & location management
│   ├── auth/             # Authentication, Google/Apple Sign-In, phone & OTP verification
│   ├── billing/          # Subscription plans, billing tiers & plan feature gating
│   ├── chat/             # Buyer-vendor real-time messaging & permission gates
│   ├── location/         # Geolocation services, address resolution & state selection
│   ├── notifications/    # In-app & push notification management
│   ├── products/         # Construction marketplace catalog, categories & special offers
│   ├── settings/         # User preferences, security & app settings
│   └── vendor/           # Vendor storefront, product listings, discounts & PDP management
├── route/                # Centralized routing & navigation configuration
├── Screens/              # Core application & onboarding screens
├── shared/               # Shared search bar, networking & utility widgets
└── widgets/              # Common atomic design widgets
```

---

## 🛠️ Tech Stack & Key Capabilities

- **Framework:** Flutter (Dart `^3.9.0`)
- **State Management:** Riverpod (`flutter_riverpod`)
- **Networking & Storage:** `dio`, `http`, `hive`, `shared_preferences`
- **Authentication:** OAuth (`google_sign_in`, `sign_in_with_apple`), Phone & OTP Verification (`pinput`, `intl_phone_field`)
- **Location & Maps:** `geolocator`, `geocoding`, multi-address management
- **UI & Animations:** `flutter_screenutil`, `lottie`, `shimmer`, `flutter_staggered_animations`, `flutter_staggered_grid_view`, custom `Satoshi` typography
