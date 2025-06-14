<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# MAP_BE

<em>Transforming News into Location-Driven Insights Instantly</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/leegitae00/Map_BE?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/leegitae00/Map_BE?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/leegitae00/Map_BE?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Flask-000000.svg?style=flat&logo=Flask&logoColor=white" alt="Flask">
<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/OpenAI-412991.svg?style=flat&logo=OpenAI&logoColor=white" alt="OpenAI">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)
- [Roadmap](#roadmap)

---

## Overview

Map_BE is a versatile developer tool that integrates AI and mapping APIs to enrich regional news articles with precise geolocation data and transit information. Built on Flask, it offers a streamlined API for fetching, enhancing, and utilizing location-aware news insights within your applications.

**Why Map_BE?**

This project simplifies the process of geolocating news content and providing route planning features. The core functionalities include:

- 🗺️ **Location Extraction:** Uses OpenAI to automatically identify and extract location data from news articles.
- 🚦 **Map Integration:** Leverages Kakao Maps to retrieve accurate geographic coordinates for locations.
- 📰 **News Enrichment:** Enhances news articles with geolocation data for more relevant content delivery.
- 🚉 **Route Planning:** Supports transit directions, enabling seamless navigation within your app.
- ⚙️ **API-Driven Architecture:** Built with Flask, ensuring easy integration and extensibility for your projects.

---

## Features

|      | Component       | Details                                                                                     |
| :--- | :-------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**  | <ul><li>RESTful API built with Flask</li><li>Separation of concerns between routes and services</li><li>Environment-based configuration management</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Consistent code style following PEP 8</li><li>Modular structure with dedicated directories for routes, services, and utils</li><li>Use of environment variables for sensitive info</li></ul> |
| 📄 | **Documentation** | <ul><li>Basic README with setup instructions</li><li>API endpoints documented via docstrings</li><li>Minimal external docs; potential for Swagger/OpenAPI integration</li></ul> |
| 🔌 | **Integrations**  | <ul><li>OpenAI API for AI functionalities</li><li>Requests library for HTTP calls</li><li>Flask-CORS for cross-origin support</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Separate modules for API routes, services, and environment config</li><li>Reusable utility functions</li></ul> |
| 🧪 | **Testing**       | <ul><li>Limited testing; potential for unit tests using pytest</li><li>Test coverage not explicitly shown in codebase</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Basic Flask server; no explicit performance optimizations</li><li>Potential bottlenecks in external API calls</li></ul> |
| 🛡️ | **Security**      | <ul><li>Uses environment variables for sensitive data</li><li>Basic CORS setup; no advanced security measures observed</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Managed via `requirements.txt`</li><li>Key dependencies include `flask`, `requests`, `python-dotenv`, `openai`, `flask-cors`</li></ul> |

---

## Project Structure

```sh
└── Map_BE/
    ├── app_new.py
    └── requirements.txt
```

---

### Project Index

<details open>
	<summary><b><code>MAP_BE/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/leegitae00/Map_BE/blob/master/app_new.py'>app_new.py</a></b></td>
					<td style='padding: 8px;'>- Provides a Flask-based API to fetch and enhance regional news articles with geolocation data, leveraging OpenAI for location extraction and Kakao Maps for coordinate retrieval<br>- Facilitates news search and route planning functionalities, integrating multiple APIs to deliver location-aware news insights and transit directions within the broader application architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/leegitae00/Map_BE/blob/master/requirements.txt'>requirements.txt</a></b></td>
					<td style='padding: 8px;'>- Defines the external dependencies necessary for the web application, ensuring proper setup of core frameworks like Flask and supporting libraries such as requests and openai<br>- Facilitates seamless integration of web server functionalities, API interactions, and environment configurations, thereby supporting the overall architecture of a RESTful service that handles client requests and communicates with AI models.</td>
				</tr>
			</table>
		</blockquote>
	</details>
</details>

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** Python
- **Package Manager:** Pip

### Installation

Build Map_BE from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/leegitae00/Map_BE
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Map_BE
    ```

3. **Install the dependencies:**

**Using [pip](https://pypi.org/project/pip/):**

```sh
❯ pip install -r requirements.txt
```

### Usage

Run the project with:

**Using [pip](https://pypi.org/project/pip/):**

```sh
python {entrypoint}
```

### Testing

Map_be uses the {__test_framework__} test framework. Run the test suite with:

**Using [pip](https://pypi.org/project/pip/):**

```sh
pytest
```

---

## Roadmap

- [X] **`Task 1`**: <strike>Implement feature one.</strike>
- [ ] **`Task 2`**: Implement feature two.
- [ ] **`Task 3`**: Implement feature three.

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
