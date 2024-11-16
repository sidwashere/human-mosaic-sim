# The Human Mosaic - Advanced AI Social Simulation Platform

A sophisticated multi-agent interaction ecosystem that models complex social dynamics through an immersive, real-time web visualization.

## Features

- Real-time agent interaction simulation
- Dynamic conversation generation using OpenAI GPT-3.5
- Complex personality and relationship modeling
- Cyberpunk-inspired visualization
- Modular and extensible architecture

## Tech Stack

- Frontend: React with Vite
- Rendering: HTML5 Canvas
- State Management: React Hooks
- API Integration: OpenAI GPT-3.5-turbo
- Styling: CSS with cyberpunk theme

## Getting Started

1. Clone the repository:
```bash
git clone [repository-url]
cd the-human-mosaic
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Update `VITE_OPENAI_API_KEY` with your OpenAI API key
   - Set `VITE_USE_MOCK_DATA` to `false` if you want to use the real OpenAI API

4. Start the development server:
```bash
npm run dev
```

## Configuration

The simulation can be configured through the following environment variables:

- `VITE_OPENAI_API_KEY`: Your OpenAI API key
- `VITE_USE_MOCK_DATA`: Set to `true` to use mock data instead of real API calls

## Current Features

- Multi-agent simulation with dynamic personalities
- Complex conversation generation
- Real-time visualization
- Relationship modeling
- Topic-based interactions

## Architecture

The application is built with a modular architecture:

- `App.jsx`: Main application component
- `SimulationCanvas`: Handles agent visualization
- `ConversationPanel`: Displays agent conversations
- `InteractionPanel`: Shows agent relationships
- `utils/`: Helper functions and configuration

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License.

---

### Credits

Developed by Sidney Njer
