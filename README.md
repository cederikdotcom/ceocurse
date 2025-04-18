# CEO Curse (CuRSe)

A comprehensive toolkit for executives to Cut expenses, Raise capital, and Sell something profitably.

## Overview

CEO Curse provides executives with practical tools to manage their company's financial health effectively. The name CuRSe stands for the three essential financial management tools every CEO needs:

- **C**ut expenses
- **R**aise capital
- **S**ell something profitably

## Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm (v8 or later)
- MongoDB (v5 or later)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/ceo-curse.git
   cd ceo-curse
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Set up environment variables
   ```bash
   cp .env.example .env
   # Edit .env with your specific configuration
   ```

4. Start the development server
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
ceo-curse/
├── docs/               # Documentation
├── public/             # Static assets
├── src/                # Source code
│   ├── components/     # React components
│   ├── pages/          # Page definitions
│   ├── services/       # Business logic
│   ├── models/         # Data models
│   └── utils/          # Utility functions
├── tests/              # Test suite
└── .github/            # GitHub workflows
```

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm start` - Start the production server
- `npm test` - Run tests
- `npm run lint` - Run linter

## Deployment

The application is configured for deployment on Vercel or Netlify. Follow these steps:

1. Connect your GitHub repository to your preferred platform
2. Configure the environment variables
3. Deploy

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Link: [https://github.com/yourusername/ceo-curse](https://github.com/yourusername/ceo-curse)
