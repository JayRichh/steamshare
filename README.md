# SteamShare

Steam screenshot management and editing platform built with Next.js 14. Created using [next-temploot](https://github.com/JayRichh/next-temploot).

## Core Features

- **Steam Integration** - Seamless login, screenshot sync, and friend activity
- **Screenshot Gallery** - Browse and manage your Steam screenshots
- **Canvas Editor** - Professional editing tools powered by Fabric.js
- **Friend System** - View and interact with Steam friends' content

## Project Structure

```
src/
├── app/              # Next.js app router
│   ├── dashboard/    # Screenshot management
│   ├── editor/      # Canvas editor
│   ├── steam/       # Steam integration
│   └── api/         # API endpoints
├── components/       # React components
├── context/         # React context
├── hooks/           # Custom hooks
├── tools/           # Canvas tools
│   ├── drawing/     # Drawing tools
│   └── filters/     # Image filters
└── types/           # TypeScript types
```

## Tech Stack

- **Framework** - Next.js 14, React 18
- **Canvas** - Fabric.js 6.5
- **Styling** - Tailwind CSS, Framer Motion
- **Forms** - React Hook Form, Zod
- **UI** - Lucide Icons, CVA
- **Dev Tools** - TypeScript, ESLint, Prettier

## Development

```bash
npm install
npm run dev
```

Requires `STEAM_API_KEY` in `.env.local`

## License

MIT
