# OpenAI Web Search RAG LLM API with BUN.js

## Overview
This project provides an API that leverages OpenAI's GPT-3.5 to rephrase search queries, performs data scraping with Cheerio, and gathers data through web search with Brave Search. The data is then processed for similarity search and generating responses based on the content.

## Features
- Query rephrasing using OpenAI GPT-3.5
- Data scraping using Cheerio
- Web search using Brave Search
- Text processing and vectorization for similarity search
- Built with Bun.js for the backend server

## Quick Start
1. **Get API Keys**:
    - OpenAI: [Get API Key Here](https://platform.openai.com/account/api-keys)
    - Brave Search: [Get API Key Here](https://brave.com/search/api/)
2. **Environment Variables**: Create a `.env` file with the following content:
    ```env
    OPENAI_API_KEY="KEYGOESHERE"
    BRAVE_SEARCH_API_KEY="KEYGOESHERE"
    ```
3. **Install Dependencies**: Run `bun install langchain openai cheerio` to install the required packages.
4. **Run Server**: Execute `node index.js` to start the server on port 3005.

## API Usage
Send a POST request to `http://localhost:3005` with a JSON payload containing search parameters.

## Author
DevelopersDigest
- [Website](https://www.developersdigest.tech/)
- [Patreon](https://www.patreon.com/DevelopersDigest/)
- [YouTube](https://www.youtube.com/@DevelopersDigest)
- [Twitter](https://twitter.com/dev__digest)
