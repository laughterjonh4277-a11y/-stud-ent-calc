# StudentCalc

**Calculate Smarter. Plan Better.**

A mobile-friendly academic calculator starter built with React and Vite.

## Included
- GPA calculator using course credit units and grade points
- CGPA calculator using previous CGPA/units plus current semester courses
- Target CGPA estimator
- Responsive navigation and student-focused landing page
- No login or database required for the calculators to work

## Run locally
Install Node.js, then run:

```bash
npm install
npm run dev
```

## Build for deployment
```bash
npm run build
```

## Deploy to Vercel
Import this repository into Vercel. Vercel should detect Vite automatically. Build command: `npm run build`; output directory: `dist`.

## Important
The default grade scale is a configurable 5-point scale: A=5, B=4, C=3, D=2, E=1, F=0. Institutions may use different grading rules, so students should confirm their university's grading policy. Supabase authentication, persistent profiles, and the secure admin dashboard are not connected in this starter version.
