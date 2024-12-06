# Chess.com Wrapped

A web application that generates a personalized, Spotify Wrapped-style visualization of your Chess.com annual performance statistics.

## Features

- 🎯 Dynamic username-based data fetching
- 📊 Comprehensive statistics visualization
- 🎨 Beautiful, responsive design with chess-themed elements
- 📱 Mobile-friendly interface
- 📸 Shareable summary card generation
- 📋 One-click copy to clipboard functionality
- 🔄 Real-time data processing
- ⚡ Client-side only (no server required)

## Statistics Tracked

- Overall game performance (wins, losses, draws)
- Best winning streaks
- Favorite time controls
- Most played openings
- Rating progression
- Game accuracy statistics
- Time-of-day playing patterns
- Day-of-week activity
- Best wins and memorable games
- Fastest victories
- Longest games

## Technologies Used

- HTML5
- Vanilla JavaScript
- Tailwind CSS
- html2canvas (for summary card generation)
- Chess.com Public API

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chess-wrapped.git
   ```

2. Open `index.html` in your web browser
   - No build tools or server setup required
   - Works directly from the file system

## Usage

1. Enter your Chess.com username
2. Click "Generate Wrapped"
3. View your personalized chess statistics
4. Share your summary card:
   - Click "Copy to Clipboard" to save the image
   - Share on social media

## API Integration

Uses the Chess.com Public API endpoints:
- `/pub/player/{username}/stats`
- `/pub/player/{username}/games/archives`

## Browser Compatibility

Tested and working on:
- Chrome
- Firefox
- Safari
- Edge

## Known Limitations

- Limited to games played in the current year
- Depends on Chess.com API availability
- Requires an active internet connection
- Some statistics may be unavailable for users with private games

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by Spotify Wrapped
- Thanks to Chess.com for providing the public API
- Built with ❤️ for the chess community

## Future Improvements

- Historical year comparison
- More detailed opening analysis
- Advanced statistical insights
- Performance optimization
- Offline support
- Additional sharing options
