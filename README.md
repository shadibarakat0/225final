This project is a dynamic web application that integrates with the NBA API to display real-time NBA team standings, player rosters, and player statistics. Built using HTML, Bootstrap, and Vanilla JavaScript, the app provides a clean and responsive interface for sports fans to explore NBA data.

Features
NBA Standings: View team rankings by season, along with win/loss records.
Player Rosters: Explore the rosters of NBA teams.
Player Statistics: Dive into detailed statistics for individual players.
Responsive Design: The app works seamlessly across devices using Bootstrap.
Error Handling: Graceful feedback is provided for API errors or missing data.
Pages
Standings Page (index.html):
Displays NBA team standings for a selected season.
Users can filter standings by season.
Players Page (players.html):
Lists the players for a selected team.
Provides a "View Stats" button for more details on each player.
Player Stats Page (stats.html):
Shows aggregated and per-game statistics for a selected player.
API Integration
This project uses the NBA API to fetch data. Below are the endpoints utilized:

Standings Endpoint:
URL: https://api-nba-v1.p.rapidapi.com/standings

Purpose: Fetches team standings for a specified season.
Players Endpoint:
URL: https://api-nba-v1.p.rapidapi.com/players

Purpose: Fetches player rosters for a specific team and season.
Player Stats Endpoint:
URL: https://api-nba-v1.p.rapidapi.com/players/statistics

Purpose: Fetches detailed statistics for a specific player in a given season.
Games Endpoint:
URL: https://api-nba-v1.p.rapidapi.com/games

Purpose: Fetches game data for teams in a given season.
Authentication
The API requires an API key for access. This key is included in the project via the fetch headers:

javascript
Copy code
headers: {
    'x-rapidapi-key': 'YOUR_API_KEY',
    'x-rapidapi-host': 'api-nba-v1.p.rapidapi.com'
}
Technologies Used
HTML: Markup for structuring the web pages.
CSS & Bootstrap: Styling and responsiveness.
Vanilla JavaScript: Logic for API integration and dynamic content rendering.
NBA API: Source of real-time basketball data.
