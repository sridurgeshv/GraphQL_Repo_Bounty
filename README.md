<!DOCTYPE html>
<html lang="en">
<body>

<h1>GraphQL With Etherscan APIs Bounty</h1>

<h2>Overview of Bounty</h2>
<p>This project builds upon the GraphQL with REST API module, leveraging the knowledge to encapsulate multiple REST API endpoints into a unified GraphQL API for streamlined and efficient querying.</p>
<p>For this bounty, the task involves working with Etherscan APIs to consolidate various Etherscan API endpoints into a singular GraphQL API. The specified Etherscan APIs include:</p>
<ul>
  <li>Get Ether Balance for a Single Address</li>
  <li>Get Total Supply of Ether</li>
</ul>

<h2>Getting Started</h2>
<ol>
  <li>Sign up for a new <a href="https://etherscan.io/login" target="_blank">Etherscan account</a> if you haven't already, to acquire your unique API key.</li>
  <li>Clone this Git repository to your local machine.</li>
  <li>Create a new .env file within the cloned repository and define a ETHERSCAN_API variable to store your Etherscan API key.</li>
  <li>Execute the <code>$npm install</code> command in your terminal to install the necessary dependencies.</li>
  <li>Implement code changes within <code>schema.graphql</code> and <code>ethDatasource.js</code> to align with the specified task.</li>
  <li>Run the <code>$node index.js</code> command in your terminal to initialize the GraphQL server and perform your desired queries.</li>
</ol>

</body>
</html>
