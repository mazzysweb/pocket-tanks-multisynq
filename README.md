# pocket-tanks-multisynq
Trying to build the classic Pocket Tanks Game for fun using the Multisynq
```markdown
# Pocket Tanks with Multisynq

A simple two-player artillery game built with Multisynq for real-time synchronization.

## Prerequisites
- A Multisynq API key (sign up at https://multisynq.io to get one).
- A GitHub account.

## Setup
1. **Get a Multisynq API Key**:
   - Sign up at https://multisynq.io.
   - Copy your API key.
   - Open `game.js` and replace `YOUR_API_KEY` with your actual API key.

2. **Deploy to GitHub**:
   - Create a new repository on GitHub (e.g., `pocket-tanks-multisynq`).
   - Unzip this folder (`pocket-tanks-multisynq`).
   - Push the contents to your GitHub repository:
     - Initialize a Git repository: `git init`
     - Add files: `git add .`
     - Commit: `git commit -m "Initial commit"`
     - Link to remote: `git remote add origin <your-repo-url>`
     - Push: `git push -u origin main`
   - Enable GitHub Pages:
     - Go to your repository on GitHub.
     - Navigate to **Settings > Pages**.
     - Set the source to the `main` branch and `/ (root)` folder.
     - Save. GitHub will provide a URL (e.g., `https://yourusername.github.io/pocket-tanks-multisynq`).

3. **Play the Game**:
   - Open the GitHub Pages URL in two different browsers or devices.
   - Each player joins the game, and the first player to join starts as Player 1.
   - Adjust angle (0-90 degrees) and power (10-100), then click "Fire" to shoot.
   - Take turns firing until one player's health reaches 0.

## Notes
- Ensure both players are connected to the internet.
- The game uses Multisynq for real-time synchronization, so no server setup is needed.
- If you encounter issues, check the Multisynq documentation at https://multisynq.io/docs.

## Credits
Built with Multisynq and inspired by Pocket Tanks by BlitWise Productions.
```
