# AI Image Generator

A modern web application that generates images using OpenAI's NEBIUS API model. Built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🎨 Generate high-quality images using NEBIUS
- 🚀 Built with Next.js 13 and TypeScript
- 💅 Modern UI with Tailwind CSS and shadcn/ui
- 🔥 Real-time image generation
- ⚡ Fast and responsive design
- 🛡️ Error handling and loading states
- 📱 Mobile-friendly interface

## Prerequisites

Before you begin, ensure you have:

- Node.js 16.8 or later
- An NEBIUS API key ([Get one here](https://studio.nebius.com/settings/api-keys))

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd ai-image-generator
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenAI API key:
```env
NEBIUS_API_KEY=your-api-key-here
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. Enter a descriptive prompt in the input field
2. Click the "Generate" button
3. Wait for the AI to generate your image
4. The generated image will appear below the input field

## Tech Stack

- [Next.js](https://nextjs.org/) - React framework
- [TypeScript](https://www.typescriptlang.org/) - Type safety
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [shadcn/ui](https://ui.shadcn.com/) - UI components
- [NEBIUS API](https://studio.nebius.com/) - Image generation
- [Lucide React](https://lucide.dev/) - Icons

## Project Structure

```
├── app/
│   ├── api/
│   │   └── generate/
│   │       └── route.ts    # OpenAI API endpoint
│   ├── page.tsx           # Main application page
│   └── layout.tsx         # Root layout
├── components/
│   └── ui/               # UI components
├── public/              # Static assets
└── styles/             # Global styles
```

## Environment Variables

| Variable | Description |
|----------|-------------|
| `NEBIUS_API_KEY` | Your nebius API key |

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
