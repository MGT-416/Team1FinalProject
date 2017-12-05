# Team1FinalProject

For this project, we want to analyze football transfers. The data to build our network will be web scraped from `transfermarkt.com`, a football-specialized website. This website records all transfers between clubs all around the world, from major leagues to less-popular ones. The data do not concern only the first-level leagues, but also second and inferior divisions.

For each transfer, the website stores a lot of infomation, from the player name to the selling club director. Only a subset of those records are of interest for our project:

- Player attributes:
    - **Player Name**: Name of the player
    - **Player Link**: Transfetrmarkt.com url for the player's profile
    - **Player position**: Position of the player
    - **Age**: Age of the player at the time of the transfer


- Tranfer money:
    - **Fee**: Monetary value, if any, of the transfer
    - **Market value**: Theoritical value of the player, computed by Transfermarkt.com

- Clubs
    - **From club**: Club/Team that the player leaves
    - **To club**: Club/Team that the player joins.
    - **From manager**: Manager of the club that the player leaves.
    - **To manager**: Manager of the club that the player joins.
    - **From manager link**: Transfetrmarkt.com url for the manager of the club that the player leaves.
    - **To manager link**: Transfetrmarkt.com url for the manager of the club that the player joins.
    
    
- Competitions
    - **From competition**: Competition/League where the `from club` participate
    - **To competition**: Competition/League where the `to club`  participate
    
    
We want to analyze: **[TODO]**