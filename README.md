
# Sports Betting Analytics Platform

A modern, AI-powered sports betting analytics platform built with React, Node.js, and TypeScript. This platform provides real-time sports data analysis, AI-driven predictions, and comprehensive betting tools.

## Features

### Dashboard
- Real-time market index tracking across multiple sports leagues
- Live betting odds and line movements
- Dynamic sports data visualization
- Quick pick game recommendations
- Upcoming events calendar

### AI Analysis Tools
- Genius Analysis: AI-powered betting insights
- Self-Learning Model: Adaptive prediction system
- Edge Finder: Identifies value betting opportunities
- Pattern Recognition: Historical trend analysis

### Bankroll Management
- Bankroll tracking and visualization
- Risk management tools
- Performance analytics
- Bet sizing recommendations

### Additional Features
- Crypto wallet integration
- Live sports podcast player
- Customizable dashboard widgets
- Historical betting performance tracking

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

## Usage Examples

### 1. Analyzing a Bet

```typescript
// Using the GeniusAnalysis component
<GeniusAnalysisCard 
  event="NFL: Chiefs vs Raiders"
  betType="spread"
  odds={-110}
/>
```

### 2. Quick Pick Game

```typescript
// Get AI-generated pick
const quickPick = await generateQuickPick({
  sport: "NFL",
  betType: "moneyline",
  amount: 100
});
```

### 3. Bankroll Management

```typescript
// Track bet performance
const performance = await trackBetPerformance({
  betAmount: 100,
  odds: -110,
  result: "win",
  sport: "NBA"
});
```

## API Integration

The platform integrates with multiple sports data providers:

- API-Sports for live odds and fixtures
- Custom AI models for predictions
- Crypto payment gateways
- Historical performance databases

## Customization

The dashboard is fully customizable through the settings panel:

1. Click the "Customize" button in the top right
2. Drag and drop widgets to rearrange
3. Toggle features on/off
4. Save your layout

## AI Models

The platform uses several AI models:

- Edge Detection Model
- Pattern Recognition
- Risk Assessment
- Value Betting Analysis

## Real-time Features

- Live odds updates
- Market movement tracking
- Instant bet analysis
- Performance metrics

## Contributing

This project is open to contributions. Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## Security

- All sensitive data is encrypted
- API keys are stored securely
- User data is protected
- Regular security audits

## Support

For support or feature requests, please open an issue in the repository.
