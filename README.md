# UNO Card Game

A beautiful, interactive implementation of the classic UNO card game built with HTML, CSS, and JavaScript. Play against three computer opponents in this modern web-based version of UNO!

![UNO Game Screenshot](screenshot.png)

## Features

- Complete UNO gameplay implementation
- Play against 3 computer opponents
- Beautiful, realistic card designs
- Full deck of 108 cards
- Special card actions (Draw Two, Reverse, Skip, Wild, Wild Draw Four)
- Card animations and effects
- Configurable sound effects and animation speeds
- Responsive design for different screen sizes
- Classic UNO rules enforcement

## How to Play

1. Open `uno-card-game.html` in a modern web browser
2. You start with 7 cards, and so do your computer opponents
3. Match cards by color or number/symbol
4. Use special cards strategically:
   - Draw Two (+2): Next player draws 2 cards and misses their turn
   - Reverse (↔): Changes direction of play
   - Skip (⊘): Next player misses their turn
   - Wild (W): Choose any color
   - Wild Draw Four (+4): Choose any color and next player draws 4 cards
5. Click the "UNO!" button when you have one card left
6. First player to get rid of all their cards wins!

## Game Controls

- Click on a card to play it
- Click the draw pile to draw a card
- Click the "UNO!" button when you have one card left
- Use the Rules button to view complete game rules
- Use the Options button to customize game settings

## Game Options

- Sound effects toggle
- Animation speed control
- Card stacking rules (+2 on +2, +4 on +4)
- Force play of drawn matching card

## Technical Details

### Requirements
- Modern web browser with JavaScript enabled
- No additional dependencies or installation required

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge

### File Structure
```
.
├── README.md
└── uno-card-game.html
```

## Development

The game is built using:
- HTML5 for structure
- CSS3 for styling and animations
- Vanilla JavaScript for game logic
- CSS Grid and Flexbox for responsive layout

### Key Components

- `Card` class: Handles card creation and display
- `UnoGame` class: Manages game state and logic
- CSS custom properties for easy theme customization
- Event-driven architecture for game actions

## Future Enhancements

- Multiplayer support
- Save game state
- Additional game modes
- Custom card themes
- Mobile touch optimization
- Sound effects and background music
- Player statistics and achievements

## Credits

Created as a web-based implementation of the classic UNO card game. UNO is a registered trademark of Mattel.

## Contributing

Feel free to fork this project and submit pull requests for any improvements! 

## License

This project is created for educational purposes. The UNO game concept and trademark belong to Mattel.

## Author

Developed by Jeremy Martinez-Quinones.