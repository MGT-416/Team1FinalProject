# Team1FinalProject

For this project, we want to analyze football transfers. The data to build our network is web scraped from [`transfermarkt.com`](https://www.transfermarkt.com/), a football-specialized website. This website records all transfers between clubs all around the world, from major leagues to less-popular ones. The data does not concern only the first-level leagues, but also second and inferior divisions. Due to the great granularity of the data stored in this website, our analysis will only take into account all transfers from the 1st January 2015 to the 31 December 2016.

Our network is composed of football clubs. Each node represents a club who participate in at least one transfer between the two years of interest. A transfer between two clubs is encapsulated as an edge.

A first step in this project will be to analyze the differences between the major three types of transfers: Free transfers, loans, and monetary transfers. Each type of transfers has its own specificities, regarding the type of clubs or the characteristics of players. In a second phase, we will look more deeply in the monetary transfers network and the way money flows in this market.

The question we want to answer with this data is: Does the monetary transfers have the same characteristics as the loans on the free transfers? What is the kind of clubs participating in these type of transfers? What are the differences between clubs doing a lot of monetary transfers and the clubs doing loans? What are the interactions between clubs of the same country? Of the same league division? We will also look at the players and try to create a player's profile for each type of transfers. We will also look exclusively at the monetary transfers and try to understand how the money flows between clubs, which are the key clubs in this network, which clubs have the more effect on the amount of money involving transfers?

To answer these questions, we will mainly rely on centralities measures, like the degree centrality or the PageRank centrality. Diffusion models will also be a key part of our analysis of monetary transfers.


## Project Structure

**Report**
- "0. Project Report.ipynb"


**Data scraping and network creation**
- "1. Build Data.ipynb"
- "2. Managers history.ipynb"


**Analysis**
- "3. Transfers vs Loan vs Free.ipynb"
   
   - _Centralities study (section 5.1)_
   
- "4. Agents to agents.ipynb"
    
   - _Creating the networks for agents and small analysis_
   
- "5. Age analysis and Pagerank influence analysis.ipynb"

   - _Age distribution, age groups and Pagerank influence analysis_
   
- "6. Money infection analysis.ipynb"

   - _Study of money flows in the graph_
   
   
   
   
## Contributors
This project was done in the **MGT-416 Networks Analytics** at EPFL, fall 2017.
- **Dupont Hugo**
- **Kokhov Artem**
- **Rodrigues Danny**
