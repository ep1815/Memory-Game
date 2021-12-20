## The challenge

Your challenge is to build out this Memory game and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout for the game depending on their device's screen size
- See hover states for all interactive elements on the page
- Play the Memory game either solo or multiplayer (up to 4 players)
- Set the theme to use numbers or icons within the tiles
- (optional) Choose to play on either a 6x6 or 4x4 grid

### Expected behaviour

- You can choose to make the default screen either the Start Game screen or the solo player 4x4 grid. Note that we're using the solo player 4x4 grid for the design screenshot, so if you choose the Start Game screen, it won't match up in the design comparison slider. This isn't a big deal, but is something worth considering.
- In a solo game, track the time elapsed since first clicking on a tile and the total number of moves made. A move counts as two tiles being selected as a potential match. Once all pairs have been found, stop the timer and show the end of game modal with the stats.
- In a multiplayer game, track the total number of pairs each player has found. If a player finds a pair, increment their score by one. The current turn switches to the next player after the current player has made a move to find a potential match.
- Clicking "Restart" will restart the game with the current settings
- Clicking "New Game" will go to the Start Game screen where the player can choose their settings
- The icons in the design are from [Font Awesome](https://fontawesome.com/). Please choose whatever icons you prefer. You could even use a different icon library, if you like.

## Where to find everything

- There is minimal styling for this project.

## Building your project

Feel free to use any workflow that you feel comfortable with. Below is a suggested process, but do not feel like you need to follow these steps:

1. Create project repository with github
2. Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes to create reusable styles.
3. Before adding any styles, structure your content with JSX/react components. Writing your JSX first can help focus your attention on creating well-structured content.
4. Write out the base styles for your project, including general content styles, such as `font-family` and `font-size`.
5. Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.

## Deploying your project

As mentioned above, there are many ways to host your project for free. Our recommend hosts are:

- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
