# VoteOn (The Perfect Decentralized Election System on Ethereum)

#### VoteOn offers a secure and transparent solution for modern elections. By harnessing the power of Ethereum's blockchain, this system creates tamper-proof voting records, allowing users to cast votes remotely while ensuring anonymity and preventing fraud. This innovative project represents a step forward in trustworthy, decentralized voting, making it ideal for secure and fair electoral processes.

## Features
- **Secure Authentication & Authorization**: Implements JSON Web Tokens (JWT) for robust and secure voter authentication and role-based authorization (Admin/Voter), ensuring that only verified users can access specific functionalities.
- **Blockchain-Powered Transparency**: Leverages the Ethereum blockchain to create immutable and transparent voting records. Every vote is a transaction that can be audited, yet voter anonymity is maintained.
- **Decentralized & Trustless**: Eliminates the need for central intermediaries, fostering a trustless voting environment where the integrity of the election process is guaranteed by the decentralized nature of the blockchain.
- **Comprehensive Admin Dashboard**: Provides administrators with a powerful interface to:
    - Manage election candidates (add, remove, update).
    - Configure voting periods (start and end dates/times).
    - Monitor election results in real-time.
    - View detailed analytics and visualizations of voting data.
    - Oversee voter registration and verification processes.
- **User-Friendly Voter Interface**: Offers an intuitive and accessible UI for voters to:
    - Easily cast their votes for preferred candidates.
    - Receive real-time confirmation of their vote being successfully recorded on the blockchain.
    - Access detailed information about each candidate.
    - Verify their vote on the blockchain.
- **Double-Voting Prevention**: Smart contract logic and backend checks are implemented to prevent any attempts at double-voting, ensuring each voter can only cast one vote per election.
- **Enhanced System Security**: Incorporates measures such as encrypted data transmission, secure smart contract development practices, and protection against common web vulnerabilities.

## Technology Stack

### Frontend
*   **Core JavaScript**: Utilizes vanilla JavaScript for core DApp logic and interactivity.
*   **Web3 Integration**: Web3.js for communication with the Ethereum blockchain (interacting with Metamask and smart contracts).
*   **Styling**: CSS3 for custom styling.
*   **Build Tools**: Browserify for bundling JavaScript modules.
*   **Wallet Connection**: MetaMask for user authentication and transaction signing.

### Backend
*   **Server-Side Logic**: Node.js for the main application server.
*   **API Framework (Database Interaction)**: FastAPI (Python) for creating a robust API to interact with the MySQL database.
*   **Authentication**: JWT (JSON Web Tokens) handled by the backend services.
*   **Database**: MySQL for storing user data, roles, and other non-blockchain critical information.

### Blockchain
*   **Network**: Ethereum (utilizing a local development network like Ganache during development).
*   **Smart Contracts**: Solidity for writing the election and voting logic.
*   **Development Framework**: Truffle Suite for compiling, deploying, and testing smart contracts.
*   **Local Blockchain**: Ganache for local development and testing of blockchain interactions.

### Development & Operational Tools
*   **Version Control**: Git & GitHub.
*   **Package Management**: npm (for Node.js), pip (for Python).

## Screenshots

![Login Page](https://github.com/user-attachments/assets/307c784c-ec14-4a3c-91c8-b5a55ec612b7)

![Admin Page](https://github.com/user-attachments/assets/6c7285ee-159a-4dc3-86b1-074b86b0404f)

![Voter Page](https://github.com/user-attachments/assets/dea75510-bf6d-4d4d-899c-66b316e96216)

## Code Structure

    ├── blockchain-voting-dapp            # Root directory of the project.
        ├── build                         # Directory containing compiled contract artifacts.
        |   └── contracts                 
        |       ├── Migrations.json       
        |       └── Voting.json           
        ├── contracts                     # Directory containing smart contract source code.
        |   ├── 2_deploy_contracts.js     
        |   ├── Migrations.sol            
        |   └── Voting.sol                
        ├── Database_API                  # API code for database communication.
        |   └── main.py                   
        ├── migrations                    # Ethereum contract deployment scripts.
        |   └── 1_initial_migration.js    
        ├── node_modules                  # Node.js modules and dependencies.
        ├── public                        # Public assets like favicon.
        |   └── favicon.ico               
        ├── src                           
        |   ├── assets                    # Project images.
        |   |   └── eth5.jpg              
        |   ├── css                       # CSS stylesheets.
        |   |   ├── admin.css             
        |   |   ├── index.css             
        |   |   └── login.css             
        |   ├── dist                      # Compiled JavaScript bundles.
        |   |   ├── app.bundle.js         
        |   |   └── login.bundle.js       
        |   ├── html                      # HTML templates.
        |   |   ├── admin.html            
        |   |   ├── index.html            
        |   |   └── login.html            
        |   └── js                        # JavaScript logic files.
        |       ├── app.js                
        |       └── login.js              
        ├── index.js                      # Main entry point for Node.js application.
        ├── package.json                  # Node.js package configuration.
        ├── package-lock.json             # Lockfile for package dependencies.
        ├── README.md                     # Project documentation.
        └── truffle-config.js                    # Truffle configuration file.
