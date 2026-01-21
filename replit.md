# AI Chroney - AI Chatbot Widget Platform

## Overview

AI Chroney is a minimal, professional chatbot widget platform designed for businesses, offering an embeddable AI chat widget for sales, support, and lead generation. The platform features a clean, conversion-focused landing page with pricing tiers and simple implementation, built as a full-stack web application with a strong emphasis on minimalism and whitespace-heavy design. Its core purpose is to provide AI chatbot widgets for various sectors like e-commerce, SaaS, service firms, and internal teams, enabling product recommendations, FAQ answering, and conversational lead capture.

## User Preferences

Preferred communication style: Simple, everyday language.
Design preference: Modern, minimalistic, and classy with lots of white space and compact spacing.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript.
- **Routing**: Wouter for lightweight client-side routing.
- **UI Components**: Radix UI primitives integrated with shadcn/ui.
- **Styling**: Tailwind CSS with CSS variables for responsive design and theming.
- **State Management**: TanStack Query for server state management.
- **Build Tool**: Vite for fast development and optimized builds.

### Backend Architecture
- **Runtime**: Node.js with Express.js.
- **Language**: TypeScript.
- **API Design**: RESTful API structure under `/api` prefix.
- **Development Server**: Custom Vite integration for HMR.
- **Static Serving**: Express serves the React application in production.

### Data Storage Solutions
- **Storage**: In-memory storage only.
- **Contact Forms**: Submissions stored in memory during runtime.

### Authentication and Authorization
- **Admin Access**: Bearer token authentication for admin endpoints.
- **Security**: Rate limiting for contact form submissions.

### Key Features Architecture
- **AI Integration**: AI assistant positioned as a core product differentiator with a dedicated showcase section.
- **Widget Playground**: Client-side interactive customization page for the chat widget.
- **Landing Page**: Marketing-focused homepage with feature showcases, pricing, and FAQs.
- **Modular Components**: Reusable UI components for various sections.
- **SEO Optimization**: Structured data and meta tags for search engine visibility.
- **Performance**: Optimized builds with code splitting and lazy loading.
- **Design System**: Deep blue primary color with red-purple gradient accents, maintaining a professional aesthetic.

### Design Patterns
- **Monorepo Structure**: Shared types and utilities.
- **Component-Based Architecture**: Modular React components.
- **Type Safety**: End-to-end TypeScript.
- **Mobile-First Design**: Responsive design patterns across all breakpoints.

## External Dependencies

- **UI Library**: Radix UI.
- **Styling**: Tailwind CSS.
- **Query Management**: TanStack Query.
- **Form Handling**: React Hook Form with Zod validation.
- **Icons**: Lucide React.
- **Date Handling**: date-fns.
- **Email**: Nodemailer (for contact form notifications in development).