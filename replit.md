# Portfolio Website

## Overview

A modern, responsive portfolio website for Karthikeya Malladi built using React with TypeScript, featuring a Netflix-inspired dark theme design. The application showcases personal information, skills, projects, certifications, and education details with smooth animations and interactive components.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety
- **Build Tool**: Vite for fast development and optimized builds
- **Styling**: Tailwind CSS with custom Netflix-themed color palette
- **UI Components**: Radix UI primitives with shadcn/ui component library
- **Animations**: Framer Motion for smooth transitions and micro-interactions
- **Routing**: Wouter for client-side routing (lightweight alternative to React Router)
- **State Management**: TanStack Query for server state management

### Backend Architecture
- **Runtime**: Node.js 20 with Express.js framework
- **Language**: TypeScript with ES modules
- **Development**: TSX for TypeScript execution in development
- **Production Build**: ESBuild for backend bundling

### Data Layer
- **ORM**: Drizzle ORM with PostgreSQL support
- **Database**: PostgreSQL 16 (configured but not actively used for current portfolio)
- **Schema**: Defined in shared directory for type consistency
- **Migrations**: Drizzle Kit for schema management

## Key Components

### Frontend Components
- **Portfolio Sections**: Hero, About, Skills, Projects, Certifications, Education, Contact
- **Custom UI Components**: SkillCard, ProjectCard, CertificationCard with animation variants
- **Navigation**: Responsive navbar with smooth scroll functionality
- **Theme**: Netflix-inspired dark theme with red accent colors

### Backend Infrastructure
- **Storage Interface**: Abstracted storage layer with in-memory implementation
- **Route Registration**: Express route handler system
- **Development Server**: Vite dev server integration for HMR
- **Static Serving**: Production static file serving

### Shared Resources
- **Schema Definitions**: User schema with Zod validation
- **Type Safety**: Shared types between frontend and backend
- **Configuration**: Centralized configuration files

## Data Flow

1. **Static Content**: Portfolio data is hardcoded in component files for simplicity
2. **Client-Side Rendering**: React components render portfolio sections
3. **Animation System**: Framer Motion handles scroll-triggered animations
4. **Navigation**: Smooth scrolling between sections using DOM manipulation
5. **Responsive Design**: Tailwind CSS breakpoints ensure mobile compatibility

## External Dependencies

### Frontend Dependencies
- **UI Framework**: React ecosystem with TypeScript
- **Styling**: Tailwind CSS with PostCSS processing
- **Components**: Radix UI primitives and shadcn/ui components
- **Animation**: Framer Motion for declarative animations
- **HTTP Client**: Native fetch API with TanStack Query wrapper
- **Icons**: Lucide React for consistent iconography

### Backend Dependencies
- **Server**: Express.js with TypeScript support
- **Database**: Neon serverless PostgreSQL driver
- **ORM**: Drizzle ORM with schema validation
- **Session Management**: connect-pg-simple for PostgreSQL sessions
- **Development**: TSX for TypeScript execution

### Development Tools
- **Build System**: Vite with React plugin and runtime error overlay
- **Code Quality**: TypeScript strict mode configuration
- **Path Resolution**: Absolute imports with @ and @shared aliases
- **Environment**: Replit-specific plugins for development experience

## Deployment Strategy

### Development Environment
- **Platform**: Replit with Node.js 20 runtime
- **Database**: PostgreSQL 16 module
- **Development Server**: Runs on port 5000 with auto-reload
- **Hot Module Replacement**: Vite HMR for instant updates

### Production Build
- **Frontend**: Vite builds optimized static assets to dist/public
- **Backend**: ESBuild bundles server code to dist/index.js
- **Deployment**: Replit autoscale deployment with build/start scripts
- **Static Assets**: Served from dist/public directory

### Configuration
- **Environment Variables**: DATABASE_URL for PostgreSQL connection
- **Port Configuration**: External port 80 mapped to internal port 5000
- **Module System**: ES modules throughout the application
- **TypeScript**: Strict compilation with incremental builds

## Changelog

- June 22, 2025: Initial setup with Netflix-themed portfolio
- June 22, 2025: Added complete portfolio sections with user's resume information
- June 22, 2025: Implemented user's profile photo in hero section
- June 22, 2025: Removed all blur effects for clean display as requested
- June 22, 2025: Added "Karthikeya" branding to top-left navigation
- June 22, 2025: Prepared for deployment and GitHub upload with documentation

## Recent Changes

✓ Complete Netflix-themed portfolio with all resume information
✓ Clean design without blur effects for optimal readability
✓ Professional photo integration in hero section
✓ "Karthikeya" branding in navigation bar
✓ All portfolio sections: Hero, About, Skills, Projects, Certifications, Education, Contact
✓ Deployment preparation with README.md, LICENSE, and DEPLOYMENT.md
✓ Ready for GitHub upload and live deployment

## User Preferences

Preferred communication style: Simple, everyday language.