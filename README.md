# GraphQL With Etherscan APIs 

## Overview 
This project builds upon the GraphQL with REST API module, leveraging the knowledge to encapsulate multiple REST API endpoints into a unified GraphQL API for streamlined and efficient querying.

For this bounty, the task involves working with Etherscan APIs to consolidate various Etherscan API endpoints into a singular GraphQL API. The specified Etherscan APIs include:

- [Get Ether Balance for a Single Address](https://docs.etherscan.io/api-endpoints/accounts#get-ether-balance-for-a-single-address)
- [Get Total Supply of Ether](https://docs.etherscan.io/api-endpoints/stats-1#get-total-supply-of-ether) 

## Getting Started
1. Sign up for a new [Etherscan account](https://etherscan.io/login) if you haven't already, to acquire your unique API key.
2. Clone this Git repository to your local machine.
3. Create a new .env file within the cloned repository and define a ETHERSCAN_API variable to store your Etherscan API key.
4. Execute the $npm install command in your terminal to install the necessary dependencies.
5. Implement code changes within schema.graphql and ethDatasource.js to align with the specified task.
6. Run the $node index.js command in your terminal to initialize the GraphQL server and perform your desired queries.



