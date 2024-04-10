#### ⚡️ Requirements

1. [Node.js](https://nodejs.org) installed on your computer (18)
2. A good code editor, preferably [VSCode](https://code.visualstudio.com)
3. A free OpenAI account, with API credits and API key at [Platform.OpenAI.com](https://platform.openai.com/signup)

#### 📚 Tools Used

- [Next 14 with App Router](https://nextjs.org) - create pages
- [OpenAI API](https://replicate.com) - access the model
- [TLDraw Editor](https://www.npmjs.com/package/@tldraw/tldraw) - draw the UI
- [TailwindCSS](https://tailwindcss.com) - style library
- [React Hot Toast](https://react-hot-toast.com)
- [Lucide Icons](https://lucide.dev)

#### 🧠 Learn More

- [Nextjs Route Handler](https://nextjs.org/docs/app/building-your-application/routing/route-handlers)
- [OpenAI API Node Client](https://www.npmjs.com/package/openai)

#### 🧠 Installation

- Download the repo
- Install dependencies
- `npm run dev` to open the drawing program

#### 🧠 Usage

- use drawing tools to create UI elements or page
- Click the "Generate" button to send the prompt to OpenAi
- If the query is successful, the Preview Modal should open showing an image of the generated UI with a tab to view the code (HTML).

**Note**: multiple submissions of the same or slightly tweaked drawing can return different results. Apparently there are many assistants, and the prompt does allow some creative license. Feel free to tweak the prompt to your needs.

Inspired by: https://github.com/SawyerHood/draw-a-ui
