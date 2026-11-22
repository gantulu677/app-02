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
