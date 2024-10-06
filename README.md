# Material Donor Mutual Assist

## Overview
The Material Donor Mutual Assist project by BWorks is designed to streamline the process of managing donations, providing a transparent view into the journey of each donated item. This initiative allows donors to track their contributions from the moment they are donated to their ultimate use, offering them a detailed view of how their items are making a difference. By keeping donors informed about the status and use of their donations, the project fosters a sense of trust and community, encouraging continued support and involvement. The system simplifies the administrative tasks involved in updating and managing donations, making it easier to attract and retain donors who are motivated by seeing the tangible impact of their contributions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Development Setup

Follow these steps to set up your development environment.

### Prerequisites

- **Node.js**: Ensure that Node.js is installed on your system. If it's not installed, download and install it from [Node.js Official Website](https://nodejs.org/).

### Installation

1. **Clone the Repository**:  
   Clone the repository to your local machine.

    ```bash
    git clone https://github.com/oss-slu/material-donor-mutual-assist.git
    ```

2. **Navigate to the Project Directory**:  
   Move into the project folder.

    ```bash
    cd material-donor-mutual-assist
    ```

3. **Install Dependencies**:  
   Run the following command in your project directory to install required dependencies:

    ```bash
    npm install
    ```

    This command installs all the packages defined in your `package.json` file (both dependencies and devDependencies).

### Frontend Setup

The frontend application is located in the `client-app` folder.  
Follow the instructions provided in the [Frontend Setup Guide](https://github.com/oss-slu/material-donor-mutual-assist/blob/main/client-app/README.md).

### Server Setup

The Node.js server resides in the `server` folder, which communicates with a PostgreSQL database.  
Follow the instructions provided in the [Server Setup Guide](https://github.com/oss-slu/material-donor-mutual-assist/blob/main/server/README.md).

## Code Formatting

We use Prettier to ensure consistent code formatting across the project. Before pushing your code to the remote repository, follow these steps:

1. **Format the Code**:  
   To automatically format your code, run the following command:

    ```bash
    npm run prettier:write
    ```

2. **Check Code Formatting**:  
   After formatting, run this command to ensure everything is properly formatted:

    ```bash
    npm run prettier:check
    ```

   Only push the code to the repository once all formatting issues have been resolved.
