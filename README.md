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

### Marketplace Discovery & Product Details
| Explore & Special Offers | Trending Construction Feed | Product Detail & Vendor Inquiry |
| :---: | :---: | :---: |
| <img src="screenshots/01_explore_offers.jpg" width="250" alt="Explore & Special Offers"/> | <img src="screenshots/02_marketplace_trending.jpg" width="250" alt="Trending Marketplace Feed"/> | <img src="screenshots/03_product_detail.jpg" width="250" alt="Product Detail Page"/> |
| *Location-aware home feed, promotional deals & category navigation* | *Staggered grid feed for materials, timber & heavy equipment* | *Multi-photo gallery, instant WhatsApp/call actions & quick-inquiry chips* |

### Vendor Listing, Messaging & User Profile
| List an Item & Location Sheet | Chat Permission Onboarding | In-App Messaging | User Profile & Verification |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/04_vendor_list_item.jpg" width="200" alt="Vendor Listing & Location Selection"/> | <img src="screenshots/05_chat_permissions.jpg" width="200" alt="Chat Permission Gate"/> | <img src="screenshots/06_messages_view.jpg" width="200" alt="Messages View"/> | <img src="screenshots/07_user_profile.jpg" width="200" alt="User Profile"/> |
| *Vendor listing workflow with saved address & custom location selector* | *Contextual permission gate for camera, voice notes & contacts* | *Real-time buyer-vendor negotiation & contact invitations* | *Account management with email & phone verification status* |

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
