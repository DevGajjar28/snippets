# TSCircuit Snippets

[Docs](https://docs.tscircuit.com) &middot; [Website](https://tscircuit.com) &middot; [Twitter](https://x.com/tscircuit) &middot; [discord](https://tscircuit.com/community/join-redirect) &middot; [Quickstart](https://docs.tscircuit.com/quickstart) &middot; [Online Playground](https://tscircuit.com/playground)

TSCircuit Snippets is a web application for creating, sharing, and managing circuit designs using TypeScript and React. It provides an intuitive interface for designing circuit boards, packages, footprints, and 3D models.

## Features

- Create and edit circuit designs using TypeScript and React
- Real-time preview of PCB layouts and 3D models
- Share and collaborate on circuit designs
- AI-assisted circuit design and error correction
- Import and export designs in various formats

## Getting Started

### Prerequisites

- [Bun](https://bun.sh/) (latest version)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/tscircuit/snippets.git
cd snippets
```

2. Install dependencies:

```bash
bun install
```

### Running the Development Server

To start the development server:

```bash
bun run dev
```

This command will build the fake API and start the Vite development server. Open [http://localhost:5173](http://localhost:5173) in your browser to view the application.

### Building for Production

To build the project for production:

```bash
bun run build
```

This will create a production-ready build in the `dist` directory.

## Project Structure

- `src/`: Contains the main React application code
- `fake-snippets-api/`: Contains the mock API for development
- `public/`: Static assets
- `components/`: Reusable React components
- `hooks/`: Custom React hooks
- `pages/`: Main page components
- `lib/`: Utility functions and helpers

## Contributing

We welcome contributions to TSCircuit Snippets! Please read our [Contributing Guide](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by [val.town](https://val.town), [codesandbox.io](https://codesandbox.io/), and [v0.dev](https://v0.dev)
- Built with [React](https://reactjs.org/), [Vite](https://vitejs.dev/), and [Tailwind CSS](https://tailwindcss.com/)

For more information, visit [tscircuit.com](https://tscircuit.com).
