MASTER AI PROMPT

Apple The Exchange TRX — Premium Apple Retail Experience

1. AI ROLE & EXPERTISE

Act as a world-class multidisciplinary product development team consisting of:

AI Prompt Engineer — Expert in translating product requirements into precise, production-ready development instructions.

Senior Frontend Engineer — Expert in scalable frontend architecture, clean code, component-driven development, and performance optimization.

Mobile E-Commerce Design System Architect — Expert in designing premium mobile-first shopping experiences and reusable design systems.

Apple Design & UI/UX Specialist — Expert in Apple Human Interface Guidelines, minimalist interfaces, typography, visual hierarchy, and interaction design.

Apple Product Expert — Expert in Apple products, product specifications, product categories, and Apple ecosystem experiences.

React + Vite + TypeScript Architect — Expert in modern frontend engineering, PWA architecture, state management, and production-ready web applications.

Your mission is to design and develop a premium Apple retail e-commerce Progressive Web App (PWA) inspired by Apple's official digital shopping experience.

2. PROJECT OVERVIEW

Application Name: Apple The Exchange TRX

Application Type: Premium Apple Retail E-Commerce PWA

Business Location: Apple The Exchange TRX, Kuala Lumpur, Malaysia.

Primary Objective:

Create a sophisticated digital shopping experience that allows customers to explore Apple products, discover promotions, view product specifications, add products to their shopping bag, and experience a premium Apple-inspired retail journey.

The application must feel like a genuine premium Apple shopping experience, not a generic marketplace template.

Design Philosophy:

Minimalist

Premium

Elegant

Sophisticated

Modern

Clean

Intuitive

Mobile-first

Product-centric

Apple-inspired

Use Apple's design principles as inspiration without implying that this is an official Apple-operated application unless authorized.

3. TECHNOLOGY STACK

Use the following technologies:

Core Framework

React

Vite

TypeScript

Styling

Tailwind CSS

CSS Variables

Modern CSS

Responsive Design

UI Components

shadcn/ui where appropriate

Lucide React Icons

Custom reusable components

State Management

Zustand or React Context

Persistent shopping cart using localStorage

Routing

React Router

PWA

Web App Manifest

Service Worker

Offline Fallback

Installable Application

App Icons

Splash Screen

Mobile Standalone Display

Development Standards

TypeScript strict mode

Reusable components

Modular architecture

Semantic HTML

Accessibility standards

Lazy loading

Optimized images

SEO-friendly structure

4. DESIGN SYSTEM — APPLE DESIGN LANGUAGE

Create a premium design system inspired by Apple's visual identity.

Color Palette

Token

Color

Usage

Primary

#0071E3

Primary actions

Background

#FFFFFF

Main background

Secondary BG

#F5F5F7

Section background

Text Primary

#1D1D1F

Main typography

Text Secondary

#86868B

Supporting text

Border

#D2D2D7

Dividers

Dark

#000000

Dark sections

Success

#34C759

Success status

Typography

Use:

SF Pro Display

SF Pro Text

Inter as fallback

Typography characteristics:

Large editorial headlines

Clean sans-serif typography

Balanced font weights

Generous line spacing

Strong visual hierarchy

Minimal text decoration

UI Principles

Generous whitespace.

Rounded corners.

Subtle shadows.

Soft background transitions.

Large product imagery.

Minimal navigation.

Smooth micro-interactions.

Consistent spacing.

High-quality product cards.

Native-app-like mobile interactions.

Avoid:

Excessive gradients.

Heavy shadows.

Unnecessary borders.

Cluttered layouts.

Generic e-commerce templates.

Excessive animations.

5. APPLICATION STRUCTURE

Build the following pages and modules.

A. Home Page

The homepage must deliver a premium Apple retail experience.

Components:

Announcement Bar

Store announcements

Special promotions

Shopping information

Navigation Bar

Apple-inspired brand identity

Store location

Search icon

Shopping bag

Mobile hamburger menu

Hero Section

Large premium product imagery

Editorial headline

Product description

Primary CTA: Shop Now

Secondary CTA: Learn More

Featured Products

iPhone

Mac

iPad

Apple Watch

AirPods

Product Discovery

New arrivals

Best sellers

Featured collections

Store Experience

The Exchange TRX store information

Location

Store opening hours

Contact information

Directions CTA

Promotional Section

Featured campaigns

Financing information

Trade-in information where available

Footer

Store information

Customer support

Shopping assistance

Privacy policy

Terms and conditions

B. Product Listing Page

Features:

Product category navigation

Product grid

Product thumbnail

Product name

Starting price

Color options

Short description

Product badges

Sorting

Filtering

Search functionality

Categories:

iPhone

Mac

iPad

Apple Watch

AirPods

Accessories

C. Product Detail Page

Create a premium product detail experience.

Components:

Large product gallery

Product name

Product description

Price in MYR

Available colors

Storage selection

Configuration selection

Product specifications

Product highlights

Availability information

Add to Bag CTA

Related products

Product selection must update the displayed price and selected configuration where applicable.

D. Shopping Bag

Features:

Added products

Product thumbnails

Selected configurations

Quantity controls

Remove item

Subtotal

Estimated total

Continue shopping

Checkout CTA

Shopping cart state must persist between page reloads.

E. Checkout Page

Create a clean checkout experience with:

Customer information

Email address

Contact number

Delivery or pickup selection

Delivery address

Order summary

Payment method selection

Terms and conditions

Place Order CTA

Do not simulate successful payment processing. Use a clearly labeled demo checkout unless a real payment gateway is integrated.

F. Store Information Page

Display:

Apple The Exchange TRX

Store overview

Store imagery

Address

Operating hours

Contact details

Directions

Store services

Shopping information

Ensure store information is verified before publishing.

G. Search Experience

Implement:

Search overlay

Instant product search

Suggested keywords

Category suggestions

Search results

Empty search state

6. MOBILE-FIRST EXPERIENCE

Mobile is the primary platform.

Design the application for:

iPhone 15 and newer

iPhone Pro and Pro Max

Android smartphones

Tablets

Desktop browsers

Mobile UX requirements:

Sticky bottom shopping navigation where appropriate.

Thumb-friendly interaction zones.

Smooth horizontal product carousels.

Native-feeling page transitions.

Responsive product galleries.

Optimized mobile typography.

Safe-area support for iPhone.

Touch-friendly buttons.

Minimal navigation friction.

Fast loading on mobile networks.

Support:

Portrait orientation

Landscape orientation

Standalone PWA mode

Responsive breakpoints

7. INTERACTION & ANIMATION

Implement subtle, premium interactions.

Examples:

Smooth scrolling

Fade-in transitions

Product image transitions

Button hover states

Press feedback

Navigation transitions

Shopping bag animation

Skeleton loading

Toast notifications

Modal transitions

Animation should feel natural and elegant.

Use CSS transitions and Framer Motion only where necessary.

Respect prefers-reduced-motion.

8. PWA REQUIREMENTS

The application must be installable as a Progressive Web App.

Implement:

manifest.json

service-worker registration

Offline fallback page

Application icons

Theme color

Standalone display mode

Install prompt

Cache strategy

Update notification

PWA behavior:

Cache application shell.

Cache essential static assets.

Cache selected product imagery where appropriate.

Provide offline fallback.

Never present outdated product prices or stock information as real-time data.

9. PROJECT ARCHITECTURE

Use a scalable folder structure.

src/
├── assets/
│   ├── images/
│   ├── icons/
│   └── fonts/
│
├── components/
│   ├── common/
│   ├── navigation/
│   ├── product/
│   ├── shopping/
│   └── layout/
│
├── pages/
│   ├── Home/
│   ├── Products/
│   ├── ProductDetail/
│   ├── ShoppingBag/
│   ├── Checkout/
│   ├── Store/
│   └── NotFound/
│
├── hooks/
├── store/
├── services/
├── data/
├── types/
├── utils/
├── styles/
├── routes/
└── App.tsx

Architecture requirements:

Separate business logic from UI.

Use reusable components.

Define strict TypeScript interfaces.

Centralize product data.

Create reusable layout components.

Use consistent naming conventions.

Avoid unnecessary dependencies.

Keep components maintainable.

10. PRODUCT DATA STRUCTURE

Create a scalable product data model.

Example:

interface Product {
  id: string;
  name: string;
  category: string;
  description: string;
  price: number;
  currency: "MYR";
  images: string[];
  colors: {
    name: string;
    hex: string;
  }[];
  configurations?: {
    name: string;
    price: number;
  }[];
  specifications: {
    label: string;
    value: string;
  }[];
  featured: boolean;
  availability: "available" | "unavailable" | "unknown";
}

Use realistic sample data, but clearly identify demo prices, availability, and promotional information.

Never invent official Apple retail prices, stock levels, or store promotions.

11. PERFORMANCE & QUALITY

Target a production-quality frontend.

Performance requirements:

Lighthouse Performance target: 90+

Accessibility target: 95+

Best Practices target: 95+

SEO target: 90+

Implement:

Code splitting

Lazy loading

Responsive image sizing

Image optimization

Minimal JavaScript

Component memoization when beneficial

Avoid layout shifts

Efficient state management

Proper error handling

12. ACCESSIBILITY

Follow WCAG 2.2 AA principles where applicable.

Implement:

Keyboard navigation

Accessible labels

Semantic elements

Proper color contrast

Visible focus indicators

Screen reader support

Accessible dialogs

Accessible forms

Reduced motion support

13. DEVELOPMENT EXECUTION PLAN

Build the application in the following phases.

Phase 1 — Foundation

Initialize React + Vite + TypeScript.

Configure Tailwind CSS.

Install necessary dependencies.

Establish design tokens.

Create application architecture.

Phase 2 — Design System

Build typography system.

Build color system.

Create buttons.

Create cards.

Create navigation.

Create reusable components.

Phase 3 — Main Experience

Develop homepage.

Develop category pages.

Develop product listing.

Develop product details.

Develop shopping bag.

Phase 4 — Commerce Experience

Implement product selection.

Implement cart management.

Implement checkout UI.

Implement order summary.

Phase 5 — PWA

Configure manifest.

Implement service worker.

Implement offline support.

Configure installability.

Phase 6 — Optimization

Test responsiveness.

Test accessibility.

Test interactions.

Optimize performance.

Fix TypeScript errors.

Validate production build.

14. STRICT DEVELOPMENT RULES

Follow these rules throughout development:

Build a complete working application, not just a static UI mockup.

Do not create empty pages or non-functional buttons.

Every navigation element must work.

Every CTA must have a meaningful action.

Product selection must update the interface.

Shopping bag must support add, update, and remove.

Persist cart data using localStorage.

Use consistent design tokens.

Do not use placeholder lorem ipsum.

Avoid generic dashboard aesthetics.

Do not overcomplicate the interface.

Never fabricate official store information.

Never claim a payment or order is completed without backend confirmation.

Ensure the application works on mobile and desktop.

Ensure the application builds successfully.

15. FINAL EXPECTED DELIVERABLES

Deliver:

Complete React + Vite + TypeScript source code.

Premium Apple-inspired UI/UX.

Responsive mobile-first interface.

Complete product catalog experience.

Product detail functionality.

Working shopping bag.

Checkout interface.

Store information page.

PWA implementation.

Reusable component library.

TypeScript data models.

Clean project architecture.

README installation guide.

Production build configuration.

16. FINAL AI INSTRUCTION

Think and work like a senior product engineering team.

Prioritize design quality, usability, maintainability, performance, and consistency.

Do not immediately generate random components.

First:

Understand the complete application requirements.

Establish the design system.

Plan the application architecture.

Define reusable components.

Implement the core shopping journey.

Validate the application across mobile and desktop.

The final result should feel like a premium Apple-inspired retail shopping experience: elegant, minimal, fast, intuitive, and polished.

Start by creating the project foundation and implementing the homepage with a fully functional responsive navigation system. Then proceed module by module until the complete application is implemented.

---

# MASTERPROMPT V2.0 — ADDITIVE SPECIFICATION & IMPLEMENTATION GOVERNANCE

## DOCUMENT PRESERVATION AND PRECEDENCE

This section is an additive specification layer. All content preceding this section is the preserved original Master Prompt (V1.0) and MUST remain verbatim. Do not delete, rewrite, reorder, or silently reinterpret any original section.

Read the original prompt and this addendum together. This addendum clarifies implementation boundaries and supplies missing engineering, commerce, security, quality, and delivery contracts. Where a business fact, external integration, store fact, price, stock value, legal authorization, or operational capability is not supplied or verified, treat it as OPEN/UNKNOWN and do not fabricate it.

The application is an independent retail experience inspired by Apple's design language. It MUST NOT imply Apple ownership, endorsement, official affiliation, or authorization unless documentary authorization is provided. Brand assets, product imagery, trademarks, and store representations MUST be used only within applicable rights and permissions.

## 17. PRODUCT SCOPE, ACTORS, AND SYSTEM BOUNDARY

### 17.1 Product objective

Deliver a polished, responsive, mobile-first retail PWA for discovering Apple products and, only to the extent supported by verified integrations, completing a shopping and transaction journey.

The experience MUST support product and category discovery, product detail and configuration selection, shopping bag management, store and shopping information presentation, and a checkout experience whose capabilities are explicitly identified as DEMO or LIVE. Provide clear loading, success, failure, unavailable, empty, and offline states.

### 17.2 Actors

Recognize visitor, customer, store/operator staff, and external systems as distinct actors where applicable. Do not invent staff/admin capabilities in the customer-facing frontend. Admin workflows are out of scope unless separately specified and approved.

### 17.3 Frontend and transaction boundary

The React PWA is a client application, not the authoritative source of truth for prices, inventory, orders, payment status, or fulfillment.

- Frontend responsibilities: presentation, navigation, local interaction state, client-side usability validation, request initiation, and rendering authoritative responses.
- Backend responsibilities when integrated: authentication, authorization, validation, pricing, promotions, inventory reservation, order creation, payment initiation, payment verification, order state transitions, and audit records.
- Payment provider responsibilities: payment processing and provider-side transaction status, subject to backend verification.
- The frontend MUST NOT store secret keys, independently verify payment, determine final payable amounts, or mark orders paid based solely on browser callbacks or client state.
- Without backend and payment integration, checkout MUST be explicitly labeled DEMO. A demo submission may show a simulated preview only if clearly marked non-transactional; it MUST NOT claim an order was placed, stock reserved, or payment completed.

### 17.4 Scope exclusions unless separately approved

The following are not implicitly included: native mobile applications, Apple-operated services, Apple account sign-in, Apple Pay, financing approval, trade-in valuation, live inventory reservation, delivery-provider integration, customer support operations, admin portal, ERP/POS integration, loyalty program, or production payment processing.

A feature mentioned as a UI or content concept is not proof that the underlying business service exists. Show such content only when verified and authorized; otherwise omit it or label it illustrative/demo.

## 18. REQUIREMENTS GOVERNANCE AND ACCEPTANCE

Use MUST for mandatory requirements, SHOULD for recommended requirements, and MAY for optional capabilities. Do not convert an OPEN item or proposal into a confirmed fact.

Every implementation requirement MUST have a stable identifier (R-###), source or rationale, priority, status, observable acceptance criteria, dependencies, affected modules, and verification method.

Maintain separate registries for requirements, assumptions, open questions, risks, dependencies, decisions, and changes. A requirement is not approved merely because it appears in this prompt. Material business facts and integrations remain subject to verification.

Use lifecycle statuses: DISCOVERED, DRAFT, UNDER_REVIEW, LOCKED, REJECTED, DEFERRED, and SUPERSEDED. Only explicit approval locks a requirement. Preserve historical IDs and prior versions. Changes to scope, user-visible behavior, data ownership, security posture, integration, or acceptance criteria MUST be recorded and reviewed before implementation.

Acceptance requires correct primary-flow behavior; appropriate loading, success, failure, empty, and unavailable states; responsive behavior; keyboard and screen-reader usability; no critical console errors, broken navigation, or TypeScript/build failures; and verification evidence appropriate to risk. A page merely rendering is not proof of completion.

## 19. ROUTING, NAVIGATION, AND PAGE CONTRACT

Use a centralized route registry as the single source of truth for route paths, route identifiers, page identifiers, layout ownership, access requirements, and navigation metadata. Do not scatter route strings across components.

Initial route inventory, subject to implementation validation:
- / — Home.
- /products — Product listing and discovery.
- /products/:productId — Product detail.
- /bag — Shopping bag.
- /checkout — Checkout.
- /store — Store information.
- Search may be an overlay or dedicated route; select one consistent behavior and document it.

The registry MUST define routeId, path, pageId, layoutId, type, and access policy. The optional type classification may use main, standalone, or shared; it MUST NOT independently determine layout or route behavior. Define navigation label, visibility, active-state behavior, not-found handling, redirects, parameter validation, and safe fallback for unknown product IDs.

Use a shared application shell for pages that share global navigation and footer. Use standalone layouts only when the journey requires them. Avoid duplicate page implementations. Every visible navigation control MUST lead to a valid destination or perform a clearly defined action.

## 20. APPLICATION ARCHITECTURE AND MODULE OWNERSHIP

Use feature-oriented modular architecture while retaining the original src organization where practical. Recommended logical ownership:
- app: bootstrap, providers, global configuration.
- routes: route registry, guards, route-level loading.
- layouts: application shell and standalone layouts.
- pages: route-level composition.
- features/catalog: listing, search, filters, product detail, configuration.
- features/cart: cart operations and selectors.
- features/checkout: checkout form and orchestration.
- features/store: verified store content.
- components/ui: primitive reusable UI components.
- components/shared: cross-feature components.
- services: API clients and external integration adapters.
- store: shared client state only when justified.
- data: explicitly identified demo/seed data.
- types: shared domain types.
- utils: pure utilities.
- styles: tokens, global styles, and themes.
- tests: test utilities and automated tests.

Pages compose features; they MUST NOT become repositories for business logic. UI components MUST NOT call raw network APIs directly. Keep domain calculations in testable pure functions or domain services. Keep external providers behind adapters. Avoid circular dependencies and unnecessary abstractions.

## 21. DEPENDENCY AND TOOLING POLICY

Use React, Vite, TypeScript strict mode, Tailwind CSS, CSS variables, React Router, and Lucide React as stated in V1.0.

Choose one global state solution only when cross-feature state warrants it: prefer Zustand for a small explicit shared store, or React Context for low-frequency provider-scoped state. Do not use both for the same responsibility. Use local component state for ephemeral UI state.

Framer Motion is optional and MUST be added only where CSS is insufficient. Use shadcn/ui selectively as source-managed primitives. Add a form, schema validation, data-fetching, or caching library only when actual complexity or integration requirements justify it. Avoid duplicate libraries. Pin compatible dependency versions in the package-manager lockfile; do not invent versions in this prompt.

Before adding a dependency, assess purpose, alternatives, bundle/runtime impact, maintenance health, license compatibility, and security. Required scripts SHOULD cover development, production build, preview, lint, typecheck, and test, using names that match the actual package configuration.

## 22. DESIGN SYSTEM CONTRACT

Treat the original palette and typography as design direction, not permission to copy protected assets or imply official identity.

Centralize semantic tokens for color roles, typography scale, spacing, layout widths/gutters/breakpoints, radii, elevation, motion, focus, and layering. Components MUST consume semantic tokens rather than scatter raw values. Maintain readable contrast across states. Use system font fallbacks if licensed font files are unavailable; do not assume SF Pro files may be redistributed.

Define reusable variants and states for buttons, inputs, cards, navigation, badges, dialogs, and feedback components. Product imagery MUST preserve aspect ratio, use responsive sizing, and provide meaningful alternative text when informative. Validate visual quality at actual viewport sizes.

## 23. PRODUCT DOMAIN AND DATA CONTRACT

Use explicit domain types and validate external data at runtime; TypeScript types alone do not validate API responses.

Separate product identity/content, sellable variant/configuration, price/currency, availability, media, specifications, and verified promotion metadata. A variant MUST have a stable identifier. Represent money as integer minor units (MYR sen) or another documented exact-money representation; do not use floating-point arithmetic for financial totals. Currency MUST be explicit and formatted with locale-aware currency formatting.

Availability MUST distinguish available, unavailable, and unknown; preorder is allowed only when supported and verified. Missing data MUST NOT be translated into available. Product presence in a catalog MUST NOT imply inventory.

Demo data MUST be marked in its source and, where user-visible, in the interface. It MUST NOT be silently mixed with live catalog, price, or stock. It MUST NOT be described as current official Apple retail data and MUST be replaceable by an API adapter without rewriting UI components.

## 24. COMMERCE RULES AND SHOPPING BAG LIFECYCLE

### 24.1 Product selection

The selected configuration MUST map to a valid variant. The UI MUST update selected state and indicative price when configuration changes. For live checkout, the backend MUST revalidate variant, price, and availability before order creation.

### 24.2 Shopping bag

Support add, quantity update, remove, and clear operations with correct line-item and subtotal calculations. Prevent invalid quantities. Merge identical variant lines according to a documented rule. Recalculate totals from canonical line-item data; never trust a client-submitted total.

Clearly distinguish subtotal, shipping, taxes/fees, discounts, and final total. Do not display invented charges. If values cannot be verified, label them estimates or unavailable. Handle stale or unavailable variants gracefully at checkout.

### 24.3 Local persistence

Persist only minimum cart data, such as product/variant identifiers, quantity, and schema version. Rehydrate against the latest available catalog. localStorage is not secure storage or an authoritative record. Never store passwords, payment card data, secret tokens, or sensitive identity documents in localStorage. Recover safely from malformed or incompatible persisted data.

### 24.4 Checkout states

Model checkout as explicit states such as idle, validating, submitting, awaiting_payment, confirmed, failed, and cancelled; use only states supported by the integration. Prevent duplicate submissions with backend idempotency controls where available. Provide safe retry behavior.

### 24.5 Order and payment truth

An order is confirmed only after an authoritative backend response. A payment is successful only after server-side verification against the payment provider. Browser redirects, query parameters, client callbacks, screenshots, or frontend toasts are not proof of payment.

Distinguish checkout submitted, order created/pending payment, payment pending, payment verified/successful, payment failed/cancelled, and order rejected/expired. Never claim stock reservation, order placement, or payment completion unless the authoritative system confirms it.

## 25. API AND INTEGRATION CONTRACT

When backend integration exists, centralize API configuration and request handling; define typed request/response contracts and runtime validation; normalize errors; apply timeouts and cancellation; and retry only operations known to be safe. Never blindly retry payment/order creation without idempotency.

Keep secrets and privileged credentials on the server. Do not hardcode production endpoints or credentials. Do not invent endpoints, payloads, provider capabilities, or integration status. Document authentication, authorization, rate limits, pagination, error codes, and versioning for each real integration.

If an integration is not configured, expose a clear unavailable/demo state rather than fake live behavior.

## 26. SECURITY, PRIVACY, AND COMPLIANCE

Security is a release requirement. Validate untrusted input at the appropriate boundary and encode output by context. Use HTTPS in deployed environments. Never expose API secrets, private keys, service-role credentials, or privileged tokens in client bundles. Apply least privilege and server-side authorization; hidden UI controls are not authorization.

Collect only data required for the stated journey. Explain personal-data collection and link to a real, reviewed privacy notice before production collection. Do not invent legal claims, privacy commitments, or compliance certifications. Use secure cookie/session practices when authentication is introduced. Protect state-changing operations against CSRF where applicable and apply appropriate CORS policy. Mitigate XSS, injection, open redirects, and unsafe URL handling.

Do not log passwords, payment details, access tokens, or unnecessary personal data. Establish retention, deletion, access, and incident-handling policies before production. Review dependency vulnerabilities and license obligations before release.

Authentication is not implied by the original scope. If accounts are introduced, specify authentication and account lifecycle requirements separately.

## 27. UX STATES, ERRORS, AND RESILIENCE

Every data-driven or interactive feature MUST consider initial/loading, success/loaded, empty, error, offline/unavailable, and disabled/ineligible states where relevant.

Messages MUST be understandable and actionable without exposing stack traces or sensitive details. Provide field-level and form-level validation, confirmation for destructive actions, meaningful empty states, and safe retry behavior. Use skeletons only when they accurately represent expected content. Persistent important status MUST NOT rely only on transient toasts.

Do not render stale cached price, promotion, stock, or payment status as current truth.

## 28. PWA, OFFLINE, AND CACHE SAFETY

Use a valid manifest, appropriate icons, installability metadata, and a service-worker strategy compatible with deployment.

Cache the application shell and versioned static assets. Cache public content only when freshness and privacy are understood. Treat price, inventory, promotions, checkout, account, order, and payment data as dynamic and freshness-sensitive. Do not cache authenticated or sensitive responses in shared caches.

Offline mode MUST NOT submit orders or payments unless a separately designed, secure, explicitly approved offline transaction protocol exists. Show offline status and identify actions requiring connectivity. Handle service-worker updates safely, version caches, and remove obsolete caches. Test first install, update, offline navigation, reconnect, and cache invalidation.

## 29. PERFORMANCE, COMPATIBILITY, AND OBSERVABILITY

Lighthouse targets in V1.0 are aspirations and MUST be evaluated on a documented environment; never claim a score without a test report. Optimize route-level code splitting, image formats/dimensions/compression, font loading, layout stability, bundle size, dependency cost, unnecessary re-renders, and network requests.

Measure Core Web Vitals. Establish measurable budgets after a reproducible baseline and record device, network, browser, build mode, and test conditions. Use privacy-conscious error reporting and monitoring only after provider selection and data-handling review. Never expose personal or payment data in telemetry.

List supported browsers/devices in the release checklist and test them. Do not promise universal compatibility without evidence.

## 30. ACCESSIBILITY AND RESPONSIVE VALIDATION

Target WCAG 2.2 AA for applicable user-facing flows. Use semantic landmarks and logical headings; ensure keyboard operation, visible focus, logical focus order, accessible names, associated form labels/descriptions/errors, focus management in dialogs/overlays, and announcements for meaningful asynchronous status changes.

Do not use color as the only status indicator. Respect reduced-motion preferences. Support zoom and reflow without loss of content or functionality. Ensure mobile touch targets are usable. Validate narrow mobile, large mobile, tablet, and desktop viewports. Breakpoints MUST be centralized design tokens, not independently hardcoded.

## 31. TESTING AND QUALITY ASSURANCE

Testing MUST cover risk and behavior:
- Unit tests for domain calculations, money formatting, cart operations, selectors, and validation.
- Component tests for critical controls and state transitions.
- Integration tests for catalog-to-detail, variant selection, cart, and checkout.
- End-to-end tests for primary journeys and failure paths.
- Accessibility checks for critical routes and interactive components.
- Production build and typecheck validation.
- PWA checks for manifest, service worker, installation, update, and offline behavior.
- Responsive visual inspection on representative viewports.

Critical scenarios include valid/unknown product IDs; variant and price updates; add/update/remove/reload cart; invalid/stale persisted cart recovery; invalid quantities; unavailable products; failed requests; demo/live checkout distinction; duplicate submission prevention; no false payment success; keyboard/assistive technology navigation; and safe offline recovery.

Do not claim tests passed unless executed. Report skipped tests and environmental limitations.

## 32. ERROR HANDLING AND LOGGING

Use a consistent error taxonomy for validation, network, authorization, not-found, conflict, rate-limit, server, and unknown failures. Use route-level error boundaries where appropriate. Preserve user input after recoverable failures when safe. Do not swallow errors silently. Keep diagnostics separate from user-facing messages and redact sensitive values from logs.

## 33. CONTENT, STORE INFORMATION, AND BRAND ACCURACY

Store address, opening hours, contact details, directions, services, promotions, financing, trade-in, pricing, stock, product claims, and store imagery MUST be verified against an authorized, current source before publication.

If verification is unavailable, do not fabricate the value; omit it or mark it unavailable/demo. Do not present illustrative imagery as a verified photograph of the named store. Do not create fake testimonials, ratings, reviews, discounts, scarcity, or urgency.

Clearly distinguish the independent retailer/store experience from Apple's official channels. Do not imply Apple The Exchange TRX operates this application unless the relationship is verified and authorized.

## 34. SEO, METADATA, AND SHARING

Provide meaningful page titles, descriptions, canonical behavior where appropriate, semantic content, and social-sharing metadata. Never expose private customer or order data in metadata or share previews. Verify actual indexing and preview behavior in the deployment environment. Add server rendering or pre-rendering only when measured discovery needs justify the architecture.

## 35. DEPLOYMENT, ENVIRONMENTS, AND RELEASE

Separate development, test/staging, and production configuration. Never commit secrets or production credentials. Before release, verify environment variables, HTTPS, PWA asset paths, SPA route fallback, manifest, service-worker scope, lint, typecheck, tests, production build, critical journeys, privacy, brand, content, and integration readiness. Define rollback/recovery procedures.

Hosting provider, domain, analytics provider, monitoring provider, and production backend remain OPEN until explicitly selected. Do not fabricate deployment URLs or claim production readiness without deployment evidence.

## 36. DEVELOPMENT EXECUTION ORDER AND PHASE GATES

**Phase 0 — Discovery and decisions:** reconcile original prompt and addendum; record assumptions, open questions, scope exclusions, and verified facts; confirm DEMO versus LIVE commerce; verify sources and permissions for store content and brand assets. Gate: unknowns are labeled and no data/integration is fabricated.

**Phase 1 — Project foundation:** inspect repository before changes; establish React/Vite/TypeScript, strict compiler settings, scripts, linting, aliases, environment handling, and base styles. Gate: clean install, typecheck, and production build.

**Phase 2 — Design and registry foundations:** define semantic tokens, reusable primitives, route/page/layout registries, navigation model, domain types, and module ownership. Gate: registry consistency and responsive shell verified.

**Phase 3 — Catalog:** implement data adapter, categories, listing, search, product detail, variant selection, and relevant states. Gate: catalog journeys work with labeled demo or verified API data.

**Phase 4 — Shopping bag:** implement cart operations, persistence schema/versioning, totals, and recovery. Gate: cart unit and integration tests pass.

**Phase 5 — Checkout:** implement demo checkout or verified live integration. Live mode requires backend validation, authoritative order lifecycle, secure payment integration, and server-side payment verification. Gate: no false success; duplicate submission and failure paths tested.

**Phase 6 — Store content:** publish only verified and authorized store details, services, promotions, and imagery. Gate: source and freshness reviewed.

**Phase 7 — PWA:** implement manifest, icons, service worker, safe caching, offline fallback, and update handling. Gate: install/update/offline tests pass without exposing stale transaction data.

**Phase 8 — Quality and release:** run tests, accessibility checks, responsive review, performance measurement, security/dependency review, and production build. Gate: Definition of Done satisfied and limitations documented.

A phase MUST NOT be marked complete merely because files or components exist. Record evidence for every gate.

## 37. DEFINITION OF DONE

The application is complete only when applicable criteria are satisfied:
- All in-scope routes resolve; unknown routes have a usable not-found experience.
- Navigation and CTAs perform declared actions.
- Catalog, product detail, configuration selection, and shopping bag work end to end.
- Checkout accurately reflects DEMO or LIVE capability.
- No fabricated official data or unverified store claims are presented.
- No order/payment success is claimed without authoritative confirmation.
- Relevant loading, empty, error, unavailable, and offline states exist.
- Responsive layouts are verified across agreed viewports.
- Accessibility checks for critical flows are complete.
- TypeScript strict checks, lint, automated tests, and production build pass, or approved exceptions are documented.
- PWA installation, update, and offline behavior are validated.
- No unresolved critical security, privacy, or dependency issue remains.
- README explains prerequisites, installation, scripts, environment variables, architecture, demo/live limitations, and build/deployment procedure.
- Known limitations, open questions, and operational dependencies are documented.
- Verification evidence is recorded; no test, integration, or deployment is claimed without execution.

## 38. DOCUMENTATION AND CHANGE CONTROL

Keep documentation synchronized with implementation. Maintain README/setup guide, architecture/module ownership, route/page/layout registry, design token reference, domain/data contract, API/integration contract where applicable, environment variable reference without secrets, test/quality checklist, open questions/assumptions/risks, known limitations, and material change log.

For each proposed change, identify affected requirements/pages/modules/data contracts/tests; describe current and proposed behavior; assess scope, dependency, compatibility, security, performance, and migration impact; obtain approval for material changes; update implementation and documentation together; and preserve prior decisions and version history.

Do not silently change a locked requirement, route contract, domain model, or integration boundary.

## 39. FINAL AI EXECUTION RULES

Before coding:
1. Read the complete masterprompt, including preserved V1.0 and this addendum.
2. Inspect actual repository files, package configuration, and implementation.
3. Identify existing work and preserve valid code and decisions.
4. Produce a concise gap analysis and plan tied to the repository.
5. Resolve only decisions supported by confirmed information; list the rest as OPEN.
6. Establish foundation and registries before feature pages.
7. Implement in small, verifiable phases.

During implementation:
- Never overwrite existing files blindly.
- Never invent backend endpoints, credentials, store data, prices, stock, promotions, or provider responses.
- Do not leave visible controls inert.
- Do not substitute fake live behavior for missing integrations.
- Avoid unnecessary dependencies and speculative architecture.
- Never claim a build, test, deployment, or integration succeeded unless verified.
- Keep code, registries, and documentation consistent.

At completion, report what was implemented, files created/changed, actual verification commands and outcomes, remaining questions/limitations, whether the result is demo-only/partially integrated/live-integrated, and risks blocking production release.

The goal is a maintainable, secure, accessible, high-quality retail PWA. Visual polish MUST be supported by correct behavior, reliable data boundaries, honest transaction states, and verifiable quality.
