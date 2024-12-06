I want to create a modern, responsive personal website using the following technology stack:

# Website Development Project Specification

## 0. Brand Identity

- Company Name: TRUE SPOKE
- Tagline: Aligning your spokes to the AI revolution
- Brand Voice: Technical/Analytical with elements of Approachable/Educational

  Primary Characteristics:

  - Data-driven expertise
  - Clear communication
  - Problem-solving focus

  Tone Guidelines:

  - Confident but not arrogant
  - Technical but accessible
  - Practical and solution-oriented

  Key Messaging Themes:

  - Evidence-based insights
  - Real-world applications
  - Continuous innovation

## 1. Visual Identity

### Color Palette

```
Primary Colors:
- Primary: 023047
- Secondary: 219ebc
- Accent: ffb703

Supporting Colors:
- Background Light: fb8500
- Background Dark: 8ecae6
- Text Primary: 22333b
- Text Secondary: ffb703
```

### Logo Assets

```
Logo Variations:
- Full Logo Light: public/images/logo/truespoke_logo_light.png
- Full Logo Dark: public/images/logo/truespoke_logo_dark.png
- Icon Only Light: public/images/logo/truespoke_logo_light_only.png
- Icon Only Dark: public/images/logo/truespoke_logo_dark_only.png

Sizes:
- Large: 240px width
- Medium: 160px width
- Small: 80px width
- Favicon: 32x32px, 16x16px

File Formats:
- SVG (preferred for web)
- PNG (with transparency)
- ICO (favicon)
```

## 2. Core Technologies:

- React with TypeScript
- Vite as the build tool
- Tailwind CSS for styling
- React Router for navigation
- Google Analytics 4 for tracking

## 3. Required Features:

- Responsive navigation with mobile menu
- Hero section for personal introduction
- About/Bio section
- Projects/Portfolio section
- Contact section
- Footer with social links
- Page analytics tracking
- SEO optimization
- Custom favicon

## 4. Specific Components Needed:

- Navigation bar with:
  - Logo/Name
  - Mobile-responsive menu
  - Links to different sections
- Layout component for consistent page structure
- Hero section with:
  - Personal introduction
  - Call-to-action button
- Project cards for showcasing work
- Contact form or contact information
- Footer with social media links

## 5. File Structure:

```
src/
├── components/
│   ├── Navigation.tsx
│   ├── Footer.tsx
│   └── Layout.tsx
├── pages/
│   ├── HomePage.tsx
│   ├── ProjectsPage.tsx
│   └── ContactPage.tsx
├── utils/
│   └── analytics.ts
├── App.tsx
├── index.css
└── main.tsx
```

## 6. Required Dependencies:

```json
{
  "dependencies": {
    "react": "^18.2.0",
    "react-router-dom": "^6.0.0",
    "react-ga4": "^2.1.0",
    "lucide-react": "^0.263.1"
  },
  "devDependencies": {
    "typescript": "^5.0.0",
    "tailwindcss": "^3.0.0",
    "postcss": "^8.0.0",
    "autoprefixer": "^10.0.0",
    "@types/react": "^18.0.0",
    "@vitejs/plugin-react": "^4.0.0"
  }
}
```

## 7. Configuration Files Needed:

- tailwind.config.js
- tsconfig.json
- vite.config.ts
- postcss.config.js
- index.html with proper meta tags and title

## 8. Design Considerations:

- Clean, modern aesthetic
- Mobile-first approach
- Consistent color scheme
- Proper spacing and typography
- Smooth animations/transitions
- Accessible design elements

## 9. Analytics Setup:

- Google Analytics 4 initialization
- Page view tracking
- Event tracking for:
  - Project views
  - Contact attempts
  - Download resume (if applicable)
  - Social link clicks

## 10. Additional Features:

- Dark/light mode toggle
- Loading states
- Error boundaries
- Image optimization
- Form validation
- Smooth scrolling
- Meta tags for social sharing

Please help me set up this project with a focus on maintainability, performance, and modern best practices. Include instructions for initializing the project, installing dependencies, and configuring all necessary tools.
