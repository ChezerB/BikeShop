1. Code & Development

  Code is implemented following project requirements, clean, modular, and well-structured.
  
  Follows best practices for Next.js, React, and Tailwind CSS.
  
  No unused imports, commented-out code, or unnecessary console logs.
  
  Code passes linting and formatting checks.
  
  Sensitive data (e.g., API keys, Stripe keys, MongoDB URI) is secured using environment variables.

2. Functionality

  All acceptance criteria for the user story are met.
  
  Feature works as intended across supported devices and browsers.
  
  No blocking bugs or broken functionality.
  
  API endpoints are implemented, tested, and returning correct responses.

3. UI/UX

  Styled consistently using Tailwind CSS and follows the agreed design system.
  
  Responsive and mobile-friendly across devices (desktop, tablet, mobile).
  
  Accessibility is considered (basic ARIA roles, alt text for images, color contrast).

4. Data & Integration

  Product catalog, accessories, and services are properly retrieved from MongoDB.
  
  Stripe payment flow is tested in test mode and works end-to-end.
  
  Cloudinary integration correctly stores and serves images.
  
  Bookings (maintenance, test rides) are stored and retrievable from the database.

5. Testing & Quality

  Unit tests exist for core logic (where applicable).
  
  API endpoints are tested with sample requests/responses.
  
  Critical user flows (browse catalog, add to cart, checkout, booking) are tested manually.
  
  No critical or high-severity defects remain open.

6. Deployment

  Feature is deployed successfully on Vercel without errors.
  
  Environment variables are correctly set in Vercel.
  
  Changes are merged into the main branch without conflicts.

7. Documentation

  Code is commented where necessary for clarity.
  
  README or project docs updated if new setup steps, environment variables, or dependencies are introduced.
  
  API routes and important workflows documented.

8. Approval

  Code reviewed and approved by both teammates.
  
  Stakeholder/Product Owner accepts the feature as meeting requirements.
