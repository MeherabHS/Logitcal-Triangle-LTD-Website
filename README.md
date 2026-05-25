# Logical Triangle Frontend

A modern, high-performance frontend application built with Next.js and React, featuring TypeScript for type-safe development and Tailwind CSS for responsive design.

## Overview

Logical Triangle Frontend is a professional-grade web application that demonstrates best practices in modern web development. The project combines server-side rendering capabilities with a robust component architecture to deliver an optimal user experience.

## Technology Stack

- **Framework:** Next.js 16.2.6
- **UI Library:** React 19.2.4
- **Language:** TypeScript 5
- **Styling:** Tailwind CSS 4.3.0
- **Icons:** Lucide React 1.16.0
- **Validation:** Zod 4.1.5
- **Email Service:** Nodemailer 6.10.1
- **Linting:** ESLint 9

## Code Composition

- TypeScript: 95.7%
- CSS: 3.2%
- Other: 1.1%

## System Requirements

- Node.js >= 18.17.0
- npm >= 9.0.0
- npm@10.2.4 (recommended)

## Getting Started

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/Meherab-32816/ltc.git
cd ltc
npm install
```

### Development

Run the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:3000`

### Production Build

Build and start the production server:

```bash
npm run build
npm start
```

For custom port configuration:

```bash
PORT=8000 npm run start:prod
```

## Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Create optimized production build
- `npm start` - Run production server on port 3000
- `npm run start:prod` - Run production server with configurable port
- `npm run lint` - Run ESLint to check code quality
- `npm run lint:fix` - Automatically fix linting issues
- `npm run type-check` - Perform TypeScript type checking
- `npm run clean` - Remove build artifacts and cache
- `npm run analyze` - Analyze bundle size
- `npm run export` - Build static export

## Project Features

- Server-side rendering with Next.js
- Full TypeScript support for enhanced type safety
- Tailwind CSS for utility-first styling
- ESLint configuration for code quality
- Email functionality with Nodemailer
- Schema validation using Zod
- Icon library with Lucide React
- Production-ready configuration

## Development Best Practices

- Type-safe development with TypeScript
- Consistent code formatting and linting
- Environmental configuration for different deployment stages
- Optimized bundle analysis tools
- Modular component architecture

## Environment Configuration

The application supports different deployment modes:

- **Development:** `npm run dev`
- **Production:** `NODE_ENV=production npm run start:prod`

## File Structure

```
ltc/
├── package.json
├── tsconfig.json
├── eslint.config.js
├── tailwind.config.ts
├── postcss.config.js
└── src/
    └── [Application source files]
```

## Performance Optimization

This project includes built-in optimizations:

- Next.js automatic code splitting
- CSS-in-JS with Tailwind CSS
- Static generation and incremental static regeneration
- Image optimization
- Bundle analysis capabilities

## Contributing

To contribute to this project:

1. Ensure code follows the established TypeScript patterns
2. Run `npm run lint:fix` before committing
3. Execute `npm run type-check` to verify type safety
4. Maintain test coverage and code quality standards

## License

This project is private and maintained by Meherab-32816.

## Support

For issues, questions, or contributions, please open an issue in the repository.

---

**Version:** 1.0.0  
**Repository:** https://github.com/Meherab-32816/ltc
