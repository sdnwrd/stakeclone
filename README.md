# Stake Casino Replica

A fun replica of the Stake gambling website with fake balance for entertainment purposes.

## Features

- **Games**: Mines, Dragon Tower, Plinko, Dice, Limbo
- **Fake Balance**: Start with $100, persists in localStorage
- **Realistic Odds**: All games use proper probability calculations
- **Responsive Design**: Works on desktop and iPad
- **Game History**: Track your recent bets and results

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Deployment

This project is ready to deploy to Vercel:

1. Install Vercel CLI: `npm install -g vercel`
2. Run: `vercel`
3. Follow the prompts

Or deploy via the Vercel website by uploading the project folder.

## Games

### Mines
- 5x5 grid with adjustable mine count (1-24)
- Find gems to increase multiplier
- Cash out anytime or risk hitting a mine

### Dragon Tower
- Climb 9 floors by choosing safe doors
- 3 difficulty levels (Easy/Medium/Hard)
- Higher floors = higher multipliers

### Plinko
- Drop balls through pegs into multiplier buckets
- Adjustable rows (8/12/16) and risk levels
- Watch the ball bounce to your payout

### Dice
- Roll over or under your prediction
- Adjustable prediction slider
- Real-time multiplier calculation

### Limbo
- Crash-style game with flying multiplier
- Set your target multiplier
- Will it crash before reaching your target?

## Technologies Used

- React 18
- Tailwind CSS
- Local Storage for persistence
- Responsive design

## License

This project is for educational and entertainment purposes only.
