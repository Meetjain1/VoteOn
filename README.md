# VoteOn (The Perfect Decentralized Election System on Ethereum)

#### VoteOn offers a secure and transparent solution for modern elections. By harnessing the power of Ethereum's blockchain, this system creates tamper-proof voting records, allowing users to cast votes remotely while ensuring anonymity and preventing fraud. This innovative project represents a step forward in trustworthy, decentralized voting, making it ideal for secure and fair electoral processes.

## Features
- Implements JWT for secure voter authentication and authorization.
- Utilizes Ethereum blockchain for tamper-proof and transparent voting records.
- Removes the need for intermediaries, ensuring a trustless voting process.
- Admin panel to manage candidates, set voting dates, and monitor results.
- Intuitive UI for voters to cast votes and view candidate information.
- Role-based access control for admin and voters.
- Secure login system with password and voter ID.
- Voting period management (start and end dates defined by admin).
- Real-time vote counting and candidate information display.
- Prevention of double voting using blockchain and backend checks.
- Cross-origin resource sharing (CORS) enabled for secure API access.
- Environment-based configuration for sensitive data (API keys, DB credentials).
- Responsive and modern UI for both admin and voters.
- Integration with MetaMask for blockchain interactions.
- Error handling and user feedback for all major actions.

## Tech Stack

**Frontend:**
- HTML5, CSS3 (custom styles for login, admin, and voting pages)
- JavaScript (ES6+)
- jQuery (for DOM manipulation and AJAX)
- Responsive design for desktop and mobile

**Backend:**
- Node.js (Express.js server for serving frontend and handling authentication)
- Python (FastAPI for database API and authentication)
- JWT (jsonwebtoken library for secure token-based authentication)
- dotenv (for environment variable management)

**Blockchain:**
- Ethereum (smart contracts for voting logic)
- Solidity (Voting smart contract)
- Truffle (for contract deployment and testing)
- Web3.js (for blockchain interaction in frontend)
- MetaMask (user wallet and blockchain gateway)

**Database:**
- MySQL (voter and admin data storage, vote tracking)
- mysql-connector-python (Python MySQL integration)

**Authentication & Security:**
- JWT (JSON Web Tokens for secure, stateless authentication)
- Role-based access (admin vs. voter)
- Secure password and voter ID management
- CORS middleware for API security
- Environment variables for sensitive data

**Other Tools:**
- npm (Node.js package management)
- dotenv (environment variable management)
- Git & GitHub (version control)

## Requirements
- Node.js
- Metamask
- Python 
- FastAPI
- MySQL Database (port – 3306)

## Screenshots

![Login Page](https://github.com/user-attachments/assets/307c784c-ec14-4a3c-91c8-b5a55ec612b7)

![Admin Page](https://github.com/user-attachments/assets/6c7285ee-159a-4dc3-86b1-074b86b0404f)

![Voter Page](https://github.com/user-attachments/assets/dea75510-bf6d-4d4d-899c-66b316e96216)