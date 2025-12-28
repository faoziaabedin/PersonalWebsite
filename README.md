# Faozia Abedin — Portfolio

Bold, monochrome personal portfolio built with React and Tailwind CSS.

## Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm start
```

The site runs at `http://localhost:3000`.

## Build for Production

```bash
npm run build
```

Output goes to `/build` directory.

## Stack

- React 18
- Tailwind CSS
- Lucide React icons
- Oswald + Barlow + JetBrains Mono fonts

## Structure

```
src/
  App.js        # Single-file portfolio component
  index.js      # React entry point
  index.css     # Tailwind + custom styles
```

## Customization

All content data lives at the top of `App.js`:

- `SOCIAL_LINKS` — Contact info and social URLs
- `PROJECTS` — Featured work with tech stacks
- `EXPERIENCE` — Work history timeline
- `TECH_STACK` — Skills/technologies
- `AWARDS` — Recognition highlights

## Adding a Project

```javascript
{
  name: 'ProjectName',
  description: 'One-line description max.',
  tech: ['React', 'Node.js', 'PostgreSQL'],
  github: 'https://github.com/faoziaabedin/project',
  highlight: '1000+ users'
}
```

## Design System

- **Colors**: Black (#000), White (#FFF), Grays only
- **Display Font**: Oswald (headers)
- **Body Font**: Barlow (text)
- **Mono Font**: JetBrains Mono (code/details)
- **Spacing**: py-24 for sections, gap-12 for grids

## Deploy

Works with Vercel, Netlify, or any static host:

```bash
# Vercel
npx vercel

# Netlify
npx netlify deploy --prod --dir=build
```

---

Built with intention. No decoration for decoration's sake.

