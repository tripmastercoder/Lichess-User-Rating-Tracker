# Lichess-User-Rating-Tracker
Python/SQL programme for generating and viewing statistics on a Lichess user's rating history.

The scraping_lichess file contains functions to access the Lichess API and return information on either the current top ten rated players for each game type or for the current ratings and rating history for specific users.

The search_user_ratings file contains code which allows a user to choose whether to search for top ten rated players or for a specific user's rating information, adds the nformation to a database and uses sqlite3 to query the created tables and filter the search results by either date or rating.
