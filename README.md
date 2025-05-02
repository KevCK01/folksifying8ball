# Folksifying 8 Ball Web Application

A folksy, interactive 8 Ball web application that provides random answers by combining phrases from three different categories.

## Current Features

- Clean, modern interface with background image
- Text input field for questions
- Two interaction methods:
  - "Shake It!" button for random answers
  - "Ask It" button for question-based answers
- Enter key support for submitting questions
- Animated response display with shake effect
- Responsive design that works on all devices
- Three-column phrase combination system:
  - Column 1: Subject phrases (100 phrases)
  - Column 2: Action phrases (100 phrases)
  - Column 3: Outcome phrases (47 phrases)

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- No external dependencies required
- Served using Python's built-in HTTP server
- Background image support (8ballbackground.png)
- Dynamic phrase combination system

## How to Run

1. Ensure all files are in the same directory:
   - index.html
   - 8ballbackground.png
   - README.md

2. Start the server:
   ```bash
   python3 -m http.server 8080
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8080
   ```

## Current State (Checkpoint)

- Basic functionality complete
- UI/UX implemented
- Background image integration
- Dual-button system (Shake It/Ask It)
- Enter key support
- Responsive design
- Animation effects
- Three-column phrase system implemented
- Random phrase combination logic
- Proper phrase formatting and spacing

## Next Steps

Potential future improvements:
- Add more outcome phrases to match the 100 count of other columns
- Implement sound effects
- Add question history
- Save favorite responses
- Add dark/light theme toggle
- Add phrase category indicators
- Implement phrase filtering options 