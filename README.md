# JavaFX API Integration Project

## Overview

This project is a Java 17 application developed using JavaFX 17. The application aims to demonstrate the integration of multiple external RESTful JSON APIs, allowing users to seamlessly access and combine data from different services without needing to interact with them individually.

## Objectives

The primary goals of this project include:

- Integrating at least two RESTful JSON APIs from the [public-apis list](https://github.com/public-apis-dev/public-apis).
- Combining responses from different APIs to enhance user experience and provide meaningful data.
- Utilizing user input to dynamically adjust API requests.
- Ensuring that the application adheres to safety, security, and non-discrimination policies.

## Features

- **User-Friendly Interface:** Built with JavaFX, providing an intuitive interface for users to input data and view results.
- **API Integration:** Combines data from two or more APIs to present comprehensive information.
- **Dynamic Requests:** User input is utilized to modify the API requests, creating a personalized experience.
- **Rate Limiting Management:** Includes mechanisms to manage and display API rate limits to avoid exceeding allowed requests.

## Requirements

- Java 17
- JavaFX 17
- External libraries: [Gson](https://github.com/google/gson) for JSON parsing.

## APIs Used

### 1. [API Name 1](API_1_URL)

- **Description:** Briefly describe the purpose of the first API.
- **Key Features:**
  - Supports dynamic URIs.
  - Returns JSON-formatted responses.
  - No OAuth authentication required (API key may be needed).

### 2. [API Name 2](API_2_URL)

- **Description:** Briefly describe the purpose of the second API.
- **Key Features:**
  - Supports dynamic URIs.
  - Returns JSON-formatted responses.
  - No OAuth authentication required (API key may be needed).

## Implementation Details

### How It Works

1. **User Input:** The application collects user input to initiate API requests.
2. **API Request Handling:**
   - The first API is queried based on user input.
   - The response from the first API is processed and used to make a subsequent request to the second API.
3. **Data Combination:** The results from both APIs are combined and displayed to the user in a cohesive manner.

### Rate Limiting

The application implements measures to handle rate limits imposed by the APIs. Users are informed when the application is intentionally waiting to comply with these limits.
