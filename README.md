# NLW Agents - Frontend

This is the frontend application for **NLW Agents**, built with React 19 and modern development tools. Provides a complete Q&A platform with AI-powered answers, audio recording capabilities, and room management.

> 📖 **See the [main project](https://github.com/LucasLobell/agentsAskAi) for complete project overview and setup instructions.**

## 🚀 Tech Stack

- **React 19**: UI library for building interactive interfaces
- **Vite**: Fast build tool and development server
- **TypeScript**: Type safety for JavaScript
- **React Router DOM**: Client-side routing
- **@tanstack/react-query**: Data fetching and caching
- **React Hook Form**: Form management with validation
- **Zod**: Schema validation
- **Tailwind CSS**: Utility-first CSS framework with custom design system
- **Radix UI**: Accessible UI primitives
- **shadcn/ui**: Component library with New York style
- **Class Variance Authority (CVA)**: Variant management for class names
- **clsx** and **tailwind-merge**: Utility for conditional class names
- **Lucide React**: Icon library
- **dayjs**: Date formatting and manipulation
- **Biome**: Code formatting and linting

## ⚙️ Quick Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```

3. **Build for production:**
   ```bash
   npm run build
   ```

4. **Preview production build:**
   ```bash
   npm run preview
   ```

## 📁 Key Files

- `src/main.tsx` - React entry point with StrictMode
- `src/app.tsx` - Main app component with routing and React Query setup
- `src/pages/create-room.tsx` - Home page with room creation and listing
- `src/pages/room.tsx` - Room interface with Q&A functionality
- `src/pages/record-room-audio.tsx` - Audio recording interface
- `src/components/question-form.tsx` - Question input form with validation
- `src/components/question-list.tsx` - List of questions and AI answers
- `src/components/question-item.tsx` - Individual Q&A display component
- `src/components/create-room-form.tsx` - Room creation form
- `src/components/room-list.tsx` - List of available rooms
- `src/http/` - API hooks for data fetching and mutations
- `src/lib/utils.ts` - Utility functions for class name merging
- `src/index.css` - Tailwind CSS with custom design system variables

## 🗂️ Project Structure

- **Component-based**: UI split into reusable components
- **Pages**: Route-based page components in `src/pages`
- **HTTP Hooks**: Custom hooks for API interactions in `src/http`
- **Utilities**: Shared helpers in `src/lib`
- **Routing**: Managed with React Router
- **State/Data**: Server state handled by React Query
- **Forms**: Managed with React Hook Form and Zod validation
- **Styling**: Tailwind CSS with shadcn/ui design system

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## 🔧 Development

- **Vite**: Configured in `vite.config.ts` with React and Tailwind plugins
- **TypeScript**: Configuration in `tsconfig.json` and `tsconfig.app.json`
- **Path Aliases**: `@` aliased to `src/` for cleaner imports
- **Code Quality**: Biome configured for linting and formatting
- **API Integration**: Connects to backend at `http://localhost:3333`
- **Design System**: shadcn/ui with New York style and custom CSS variables
- **Form Validation**: React Hook Form with Zod schemas

## 📚 Dependencies

- **React**: `react`, `react-dom`, `react-router-dom`
- **Data Fetching**: `@tanstack/react-query`
- **Forms**: `react-hook-form`, `@hookform/resolvers`, `zod`
- **Styling**: `tailwindcss`, `@radix-ui/react-slot`, `tw-animate-css`
- **Utilities**: `class-variance-authority`, `clsx`, `lucide-react`, `tailwind-merge`, `dayjs`
- **Build Tools**: `vite`, `typescript`, `@biomejs/biome`