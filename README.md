# Election DApp - Decentralized Application for Election Management

## Team Members

**Ajaykumar Burigari** - 809320385 - Burigari@csu.fullerton.edu

**Harshini Madhurai** - 832473029 - harshinimadhurai@csu.fullerton.edu

**Bhargava Sriram Medharametla** - 816283923 - mbahrgavasriram@csu.fullerton.edu

**Jayanth Vallabi** - 884435876 - jayanthvallabi@csu.fullerton.edu

## Project Overview

The Election DApp is a decentralized application built on the Ethereum blockchain with a React JS client-side interface. It is designed to facilitate secure, transparent, and decentralized election processes. The application is ideal for election officials and voters, ensuring a seamless and trustworthy voting experience.

## Features

**For Election Officials**

	•	Voter Verification: Verify eligible voters.
	•	Candidate Management: Add the list of candidates standing for election.
	•	Voting Phase Control: Start or end the voting period.
	•	Result Management: View and display election results.

**For Voters**

	•	Registration: Register for participation in the election.
	•	Candidate List: View the list of candidates.
	•	Voting: Cast a vote securely.

## Technologies Used

	•	Smart Contracts: Developed using Solidity.
	•	Blockchain Platform: Deployed on the Ethereum blockchain using Truffle.
	•	Development Tools:
	•	Ganache: For local blockchain testing.
	•	Metamask: As a browser extension for wallet and Ethereum interaction.
	•	Frontend: Built using React JS.
	•	Web3 JS: For blockchain interaction on the client side.

## Commands Used in the Project

# Install Truffle globally
npm i truffle -g

# Navigate to the client directory and install dependencies
cd ./client
npm i

# Return to the root directory, compile and deploy contracts
cd ..
truffle compile
truffle migrate

# Start the React client application
cd ./client
npm run start

**Applications Needed**

	1.	Ganache: For local Ethereum blockchain testing.
	2.	Metamask: Browser extension for Ethereum wallet management.

**How It Works**

	1.	Election Officials:
	•	Verify voters and manage candidates.
	•	Start and stop the voting phase as needed.
	•	View results after the election concludes.
	2.	Voters:
	•	Register with their credentials.
	•	Review the candidate list.
	•	Cast their vote securely during the voting phase.

## Setup Guide

	1.	Install Ganache and set up a local Ethereum blockchain.
	2.	Add the Metamask extension to your browser and configure it to connect to the local blockchain.
	3.	Clone the project repository and navigate to the root directory.
	4.	Use the provided commands to install dependencies, compile smart contracts, deploy them, and run the client application.

This DApp ensures transparency and trust by leveraging blockchain technology, making it a robust solution for modern election systems.



## GitHub Link to the DApp: https://github.com/ajay094-dev/Election-DApp---Decentralized-Application-for-Election-Management.git