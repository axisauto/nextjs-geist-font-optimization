# Food Delivery App

A React Native Expo application with web support that showcases a food delivery interface with restaurant listings, menu items, and cart functionality.

## Features

- Restaurant listings with details
- Menu items display
- Shopping cart functionality
- Responsive web design
- Client-side routing with React Router

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Expo CLI

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd food-delivery-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

## Running the App

To run the app in web mode:

```bash
npm run web
# or
yarn web
```

The app will be available at `http://localhost:19006`

## Development

This project uses:
- TypeScript for type safety
- React Router for navigation
- Inline styles for styling
- Expo for cross-platform development

## Project Structure

```
food-delivery-app/
├── src/
│   └── screens/
│       ├── HomeScreen.tsx
│       ├── RestaurantScreen.tsx
│       └── CartScreen.tsx
├── App.tsx
├── webpack.config.js
└── package.json
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
