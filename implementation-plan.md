Modernize Neptune Navigators Website Design
The goal is to transform the current plain website into a modern, polished, and premium digital presence that highlights our 3D reconstruction and AI inspection capabilities.

User Review Required
IMPORTANT

I will be switching the site to a dark-premium theme by default to better showcase the 3D models and videos.
I will use Google Fonts (Inter & Outfit) for a modern typography feel.
I will group the "Technology Demo" and "Interactive 3D Port Model" into a featured Visualizations Spotlight section.
Proposed Changes
Design System (CSS)
[MODIFY] 

style.css
Implement a core color palette: Deep Navy (#0a0f18), Electric Teal (#00f5ff), and Soft Silver (#e2e8f0).
Add glassmorphism utilities (backdrop-filter) for cards and sections.
Update typography to Inter for body and Outfit for headings.
Add smooth transitions and hover states for all interactive elements.
Content & Structure (HTML)
[MODIFY] 

index.html
Hero Section: Redesign with a dynamic gradient and improved tagline positioning.
Visualizations Spotlight: Create a high-impact section for the 3D Port Model and the AI Detection Video. Use a "Digital Twin" vs "Real-time Analysis" comparison layout.
Improved Sections: Refactor "What We Do", "HARRIS System", and "Team" sections into modern card-based layouts.
Animations: Add entrance animations (fade-in/slide-up) for sections as they enter the viewport.
Layout & SEO
[MODIFY] 

default.html
Include Google Fonts link.
Add <meta> tags for better social sharing (Open Graph).
Verification Plan
Automated Tests
No automated testing framework currently exists. I will verify the build using Jekyll's local server if possible, or manual inspection of the generated HTML.
Run bundle exec jekyll build to ensure no syntax errors in the Liquid templates.
Manual Verification
Visual Audit: Open the site in a browser and verify the "Visualisations Spotlight" section is prominent and engaging.
Interactivity Check: Ensure the 3D model rotates smoothly and provides a "premium" feel.
Responsiveness Check: Verify the design adapts correctly to mobile and tablet screen sizes.
Performance Check: Ensure videos and 3D models load without significant lag.