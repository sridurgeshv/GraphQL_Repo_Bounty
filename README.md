<!DOCTYPE html>
<html lang="en">

<body>
  <h1>GraphQL With Etherscan APIs Bounty</h1>

  <h2>Overview of Bounty</h2>
  <p>This project builds upon the GraphQL with REST API module, leveraging the knowledge to encapsulate multiple REST API endpoints into a unified GraphQL API for streamlined and efficient querying.</p>

  <p>For this bounty, the task involves working with Etherscan APIs to consolidate various Etherscan API endpoints into a singular GraphQL API. The specified Etherscan APIs include:</p>
  <ul>
    <li><a href="https://docs.etherscan.io/api-endpoints/accounts#get-ether-balance-for-a-single-address">Get Ether Balance for a Single Address</a></li>
    <li><a href="https://docs.etherscan.io/api-endpoints/stats-1#get-total-supply-of-ether">Get Total Supply of Ether</a></li>
  </ul>

  <h2>Getting Started</h2>
  <ol>
    <li><p>Sign up for a new <a href="https://etherscan.io/login">Etherscan account</a> if you haven't already, to acquire your unique API key.</p></li>
    <li><p>Clone this Git repository to your local machine.</p></li>
    <li><p>Create a new .env file within the cloned repository and define a ETHERSCAN_API variable to store your Etherscan API key.</p></li>
    <li><p>Execute the <code>npm install</code> command in your terminal to install the necessary dependencies.</p></li>
    <li><p>Implement code changes within <code>schema.graphql</code> and <code>ethDatasource.js</code> to align with the specified task.</p></li>
    <li><p>Run the <code>node index.js</code> command in your terminal to initialize the GraphQL server and perform your desired queries.</p></li>
  </ol>
</body>

</html>
