<p align="center">
  <img src="screenshots/logo.png" alt="COST-IT Logo" width="280"/>
</p>

<h1 align="center">COST-IT Mobile</h1>

<p align="center">
  <strong>🏗️ A Full-Stack E-Commerce Marketplace Built for the Construction Industry</strong>
</p>

COST-IT is a digital-first construction commerce platform built in **Flutter** that empowers suppliers, contractors, and individual buyers to seamlessly buy, sell, and procure construction materials, heavy machinery, tools, and professional services in one trusted ecosystem — with full **Light & Dark Mode** support.

---

## 📱 App Screenshots

### 1. Onboarding, Authentication & Account Recovery
| Onboarding & Guest Entry | Email & Phone Login | Google OAuth Sign-In (Dark) | Identity & Password Recovery |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/01_onboarding_welcome.jpg" width="200" alt="Onboarding Welcome"/> | <img src="screenshots/02_login_light.jpg" width="200" alt="Welcome Back Login"/> | <img src="screenshots/03_google_signin_dark.jpg" width="200" alt="Google OAuth Sign-In"/> | <img src="screenshots/04_reset_password.jpg" width="200" alt="Reset Password"/> |
| *Animated hero onboarding with frosted glass CTA & guest mode* | *Unified email/phone login with Apple & Google OAuth* | *One-tap Google Sign-In flow in Dark Mode* | *Multi-channel (Email / Phone) identity verification* |

### 2. Marketplace Discovery, Search & Personalized Feeds (Light Mode)
| Explore & Special Offers | Search & Trending Tags | Trending Construction Grid | Personalized "For You" Feed |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/05_explore_light.jpg" width="200" alt="Explore & Special Offers"/> | <img src="screenshots/06_search_trending.jpg" width="200" alt="Search & Trending on Cost-It"/> | <img src="screenshots/07_trending_grid_light.jpg" width="200" alt="Trending Marketplace Feed"/> | <img src="screenshots/08_for_you_feed_light.jpg" width="200" alt="For You Marketplace Feed"/> |
| *Location-aware home feed, promotional deals & category navigation* | *Recent search history, trending construction tags & category counts* | *Staggered grid feed for materials, timber & heavy equipment* | *Curated horizontal list cards with bulk pricing indicators* |

### 3. Dark Mode Experience & Product Details
| Explore Feed (Dark Mode) | Category Filtering (Dark Mode) | Product Detail & Quick Deal | Vendor Actions & Reporting |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/09_explore_dark.jpg" width="200" alt="Explore Dark Mode"/> | <img src="screenshots/10_all_categories_dark.jpg" width="200" alt="All Categories Dark Mode"/> | <img src="screenshots/11_product_detail_deal_dark.jpg" width="200" alt="Product Detail Dark Mode"/> | <img src="screenshots/12_vendor_actions_dark.jpg" width="200" alt="Vendor Actions Sheet Dark Mode"/> |
| *Full adaptive Dark Mode across home & special offers* | *Filterable category chips & product grid in Dark Mode* | *Multi-photo PDP with promotional deal banner & vendor contact CTAs* | *Contextual bottom sheet to share, follow vendor, or report listings* |

### 4. Vendor Listing, Messaging, Profile & Settings
| List an Item & Location Sheet | In-App Vendor Messaging | My Profile & Vendor Hub | Security, Alerts & Theme Settings |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/13_vendor_list_location.jpg" width="200" alt="Vendor Listing & Location Selection"/> | <img src="screenshots/14_messages_view.jpg" width="200" alt="In-App Vendor Messaging"/> | <img src="screenshots/15_my_profile_dark.jpg" width="200" alt="My Profile Dark Mode"/> | <img src="screenshots/16_settings_dark.jpg" width="200" alt="Settings Dark Mode"/> |
| *Vendor listing workflow with saved address & custom location selector* | *Real-time buyer-vendor price negotiation & contact invitations* | *Account hub with saved products, recently viewed & vendor dashboard* | *2FA security, push/email/SMS alerts & Light/Dark theme switcher* |

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
- **UI, Theming & Animations:** Adaptive Light/Dark Theme, `flutter_screenutil`, `lottie`, `shimmer`, `flutter_staggered_animations`, `flutter_staggered_grid_view`, custom `Satoshi` typography
