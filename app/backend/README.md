# Backend Application

This directory contains the backend application for the Azure Search OpenAI Demo project.

## Prerequisites

- Node.js (version 14.x or higher)
- npm (version 6.x or higher)
- Azure account

## Installation

1. Clone the repository:
  ```sh
  git clone https://github.com/yourusername/azure-search-openai-demo.git
  ```
2. Navigate to the backend directory:
  ```sh
  cd azure-search-openai-demo/app/backend
  ```
3. Install the dependencies:
  ```sh
  npm install
  ```

## Configuration

1. Create a `.env` file in the `app/backend` directory and add the following environment variables:
  ```env
  AZURE_SEARCH_API_KEY=your_azure_search_api_key
  AZURE_SEARCH_ENDPOINT=your_azure_search_endpoint
  OPENAI_API_KEY=your_openai_api_key
  ```

## Running the Application

To start the backend server, run:
```sh
npm start
```

The server will start on `http://localhost:3000`.

## API Endpoints

- `GET /search`: Perform a search query using Azure Search.
- `POST /generate`: Generate text using OpenAI API.

## License

This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for details.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING](../CONTRIBUTING.md) guidelines before submitting a pull request.

## Contact

For any questions or issues, please open an issue on the [GitHub repository](https://github.com/yourusername/azure-search-openai-demo).
