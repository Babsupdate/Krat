# Krat

**Digital Karakata for Africa** — Pan-African supply chain marketplace.

Buy, sell, and ship across Nigeria and beyond. B2B wholesale. B2C retail. One platform.

[Live App](#) | [API Docs](#) | [Report Bug](https://github.com/Babsupdate/krat/issues)

---

## What Is Krat?

Krat modernizes traditional African commerce. "Karakata" in Yoruba means buying and selling—we're building the digital version.

**For Buyers:**
- Browse cloth, electronics, and imported goods
- Real-time pricing from verified sellers
- Secure escrow. Ship anywhere.
- Filter by price, location, seller rating

**For Sellers:**
- List products in minutes
- Reach buyers across regions
- 10% commission. Keep 90%.
- Seller-managed logistics. Full control.

---

## How It Works

1. **List** — Seller uploads product with size, weight, price
2. **Match** — Buyers find products by location/category
3. **Negotiate** — Offer/accept pricing (B2B) or fixed pricing (B2C)
4. **Escrow** — Payment locked until delivery
5. **Ship** — Seller arranges logistics. Real-time GPS tracking.
6. **Release** — Escrow unlocked. Both parties rate.

---

## Current Status

- **Phase 1 (Oct–Nov 2026):** Nigeria launch (cloth + electronics)
- **Phase 2:** Regional expansion (West Africa)
- **Phase 3:** Cross-border supply (Yiwu, Guangzhou, Shenzhen)

---

## Tech Stack

**Backend:** Rust + Axum + SQLx + Tokio  
**Database:** PostgreSQL (Neon)  
**Cache:** Redis (Upstash)  
**Web:** Next.js 14 + TypeScript + Tailwind  
**Mobile:** React Native CLI  
**Payments:** Kernal (NIP rails) + Paystack escrow  
**Logistics:** Google Maps API + seller integrations  

---

## Key Features

- ✅ GPS-verified listings (location radius filtering)
- ✅ Three-rail delivery (Local / Regional / National)
- ✅ Escrow-backed payments (full refund guarantee)
- ✅ Seller reputation system
- ✅ Real-time order tracking
- ✅ Bulk pricing for wholesalers
- ✅ Multi-language support (English, Yoruba)
- 🔜 Mystery Box gamification (deferred)
- 🔜 AI price suggestions

---

## Getting Started

### For Developers

```bash
git clone https://github.com/Babsupdate/krat.git
cd krat

# Backend
cd backend
cargo build
cargo run

# Web
cd web
npm install
npm run dev

# Mobile
cd mobile
npm install
npx react-native run-android
