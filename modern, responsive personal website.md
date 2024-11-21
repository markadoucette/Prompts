I want to create a modern, responsive personal website using the following technology stack:

1. Core Technologies:
- React with TypeScript
- Vite as the build tool
- Tailwind CSS for styling
- React Router for navigation
- Google Analytics 4 for tracking

2. Required Features:
- Responsive navigation with mobile menu
- Hero section for personal introduction
- About/Bio section
- Projects/Portfolio section
- Contact section
- Footer with social links
- Page analytics tracking
- SEO optimization
- Custom favicon

3. Specific Components Needed:
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

4. File Structure:
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

5. Required Dependencies:
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

6. Configuration Files Needed:
- tailwind.config.js
- tsconfig.json
- vite.config.ts
- postcss.config.js
- index.html with proper meta tags and title

7. Design Considerations:
- Clean, modern aesthetic
- Mobile-first approach
- Consistent color scheme
- Proper spacing and typography
- Smooth animations/transitions
- Accessible design elements

8. Analytics Setup:
- Google Analytics 4 initialization
- Page view tracking
- Event tracking for:
  - Project views
  - Contact attempts
  - Download resume (if applicable)
  - Social link clicks

9. Additional Features:
- Dark/light mode toggle
- Loading states
- Error boundaries
- Image optimization
- Form validation
- Smooth scrolling
- Meta tags for social sharing

Please help me set up this project with a focus on maintainability, performance, and modern best practices. Include instructions for initializing the project, installing dependencies, and configuring all necessary tools.
