# MFL Lineup Validator

## Overview
The MFL Lineup Validator is a tool designed to assist users in validating their lineups for the MFL (My Fantasy League) platform. This README provides comprehensive setup and usage instructions for the validator.

## Features
- Validate player selections against league rules.
- Check for roster limits and position requirements.
- Generate detailed reports for lineup issues.

## Setup Instructions

### Prerequisites
- Make sure you have [Node.js](https://nodejs.org/) installed.
- Ensure you have access to the MFL API.

### Installation Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/kartsetupelite/mfl-lineup-validator.git
   cd mfl-lineup-validator
   ```
2. **Install Dependencies**
   ```bash
   npm install
   ```
3. **Configure API Access**
   - Create a `.env` file in the root of the project and add your MFL API credentials:
   ```env
   MFL_API_KEY=your_api_key
   MFL_LEAGUE_ID=your_league_id
   ```

## Usage Instructions

### Running the Validator
To run the validator, use the following command:
```bash
npm start
```

### Validating a Lineup
- Follow the on-screen prompts to input your lineup.
- The validator will check your selections and report any discrepancies.

### Generating Reports
- To generate a detailed report of your lineup, run:
```bash
npm run report
```

## Contributing
If you'd like to contribute to the project, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For further questions or support, please contact the project maintainer via GitHub.