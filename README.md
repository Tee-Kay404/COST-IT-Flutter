<p align="center">
  <img src="screenshots/logo.png" alt="COST-IT Logo" width="280"/>
</p>

<h1 align="center">COST-IT Mobile</h1>

<p align="center">
  <strong>🏗️ A Full-Stack E-Commerce Marketplace Built for the Construction Industry</strong>
</p>

COST-IT is a digital-first construction commerce platform built in **Flutter** that empowers suppliers, contractors, and individual buyers to seamlessly buy, sell, and procure construction materials, heavy machinery, tools, and professional services in one trusted ecosystem.

---

## 📱 App Screenshots

### 1. Onboarding, Authentication & Account Management
| Onboarding & Guest Entry | Multi-Step Sign Up | OAuth & Email Login | User Profile & Verification |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/00_onboarding_welcome.jpg" width="200" alt="Onboarding Welcome"/> | <img src="screenshots/00c_signup_screen.jpg" width="200" alt="Create Account Screen"/> | <img src="screenshots/00b_login_screen.jpg" width="200" alt="Welcome Back Login"/> | <img src="screenshots/07_user_profile.jpg" width="200" alt="User Profile"/> |
| *Animated hero onboarding with frosted glass CTA & guest mode* | *Step-by-step registration with Apple & Google OAuth* | *Credential login with persistent session & password recovery* | *Profile management with email & phone verification badges* |

### 2. Marketplace Discovery, Search & Verified Listings
| Explore & Special Offers | Search & Trending Tags | Trending Construction Feed | Verified Vendor Listings |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/01_explore_offers.jpg" width="200" alt="Explore & Special Offers"/> | <img src="screenshots/02b_search_and_trending.jpg" width="200" alt="Search & Trending on Cost-It"/> | <img src="screenshots/02_marketplace_trending.jpg" width="200" alt="Trending Marketplace Feed"/> | <img src="screenshots/02c_verified_vendor_grid.jpg" width="200" alt="Verified Vendor Grid"/> |
| *Location-aware home feed, promotional deals & category navigation* | *Recent search history, trending construction tags & category counts* | *Staggered grid feed for materials, timber & heavy equipment* | *Category-tagged product cards with verified vendor badges* |

### 3. Product Details, Vendor Listing & Real-Time Messaging
| Product Detail & Vendor Inquiry | List an Item & Location Sheet | Chat Permission Gate | In-App Vendor Messaging |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/03_product_detail.jpg" width="200" alt="Product Detail Page"/> | <img src="screenshots/04_vendor_list_item.jpg" width="200" alt="Vendor Listing & Location Selection"/> | <img src="screenshots/05_chat_permissions.jpg" width="200" alt="Chat Permission Gate"/> | <img src="screenshots/06_messages_view.jpg" width="200" alt="Messages View"/> |
| *Multi-photo gallery, instant WhatsApp/call actions & quick-inquiry chips* | *Vendor listing workflow with saved address & custom location selector* | *Contextual permission onboarding for camera, voice notes & contacts* | *Real-time buyer-vendor price negotiation & contact invitations* |

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
- **Networking & Local Persistence:** `dio`, `http`, `hive`, `shared_preferences`
- **Authentication:** OAuth (`google_sign_in`, `sign_in_with_apple`), Phone & OTP Verification (`pinput`, `intl_phone_field`)
- **Location & Address Management:** `geolocator`, `geocoding`, multi-address profiles (`Home`, `Work/Office/Store`)
- **UI & Animations:** `flutter_screenutil`, `lottie`, `shimmer`, `flutter_staggered_animations`, `flutter_staggered_grid_view`, custom `Satoshi` typography
