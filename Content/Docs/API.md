# GitHub API Methods Overview

This document provides a brief overview of commonly used GitHub API methods for interacting with repositories, commits, and other data.

---

## API Methods

### 1. **Search Repositories**
   - **Method**: `GET /search/repositories`
   - **Purpose**: Search for repositories based on query parameters like language, stars, and more.
   - **Example**: `GET https://api.github.com/search/repositories?q=language:python+stars:>100`
   - **Docs**: [Search Repositories](https://docs.github.com/en/rest/search#search-repositories)

### 2. **Get Commits**
   - **Method**: `GET /repos/{owner}/{repo}/commits`
   - **Purpose**: Retrieve the list of commits for a specific repository.
   - **Example**: `GET https://api.github.com/repos/octocat/Hello-World/commits`
   - **Docs**: [List Commits](https://docs.github.com/en/rest/commits#list-commits)

### 3. **Get Commit Details**
   - **Method**: `GET /repos/{owner}/{repo}/commits/{sha}`
   - **Purpose**: Retrieve detailed information about a specific commit, including files changed.
   - **Example**: `GET https://api.github.com/repos/octocat/Hello-World/commits/{sha}`
   - **Docs**: [Get Commit](https://docs.github.com/en/rest/commits#get-a-commit)

### 4. **Check Rate Limit**
   - **Method**: `GET /rate_limit`
   - **Purpose**: Check the current rate limit status of your API requests.
   - **Example**: `GET https://api.github.com/rate_limit`
   - **Docs**: [Rate Limit](https://docs.github.com/en/rest/rate-limit)

---

## GitHub API Documentation
For more details on all available API methods, visit the official [GitHub API Documentation](https://docs.github.com/en/rest).
