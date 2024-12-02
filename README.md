# Repository Search and Analysis Tool

This repository provides tools for interacting with the GitHub API to search for repositories. Designed to meet client-specific needs, it supports both REST and GraphQL-based queries for efficient and flexible data retrieval.

---

## Features

- **Search Repositories**: Retrieve repositories based on various filters such as language, stars, and creation date.
- **Commits**: Analyze commit histories and extract metadata.
- **Contents**: Access file contents and manage repository files.

---

## Client Requirements

The application is designed to fulfill the following client-specific requirements:

1. **Oldest Python Repository**:
   - Retrieve the oldest publicly available repository written in Python using the basic REST API search.
   - Allow flexibility in excluding inactive or unpopular repositories when needed.

2. **Most Popular Python Repository**:
   - Identify the most popular Python repository based on the number of stars using GraphQL.
   - Include sorting and filtering capabilities to refine search results.

3. **REST API Support**:
   - Provide a straightforward way to search repositories using the `/search/repositories` endpoint.
   - Include support for query parameters like `language`, `sort`, and `order`.

4. **GraphQL API Support**:
   - Leverage GraphQL to perform advanced searches and retrieve detailed metadata about repositories.
   - Provide example queries and variables to ensure ease of use.

5. **Latest Commits**:
   - Retrieve the latest commits from a repository, along with the content of the last commit.

6. **Documentation**:
   - Provide clear examples of both REST and GraphQL queries in the documentation.
   - Include instructions for integrating with Postman or other API testing tools.

---

This ensures that the application not only meets the immediate client requirements but also supports extensibility for future use cases.
