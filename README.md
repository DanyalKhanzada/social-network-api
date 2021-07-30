# Social Network API &nbsp;&nbsp;&nbsp;[![MIT](https://img.shields.io/badge/license-MIT-yellow?style=for-the-badge)](https://shields.io/)

## Description

Social Media API using NoSQL. This express.js API forms the backend for a social media website. The API has the following functionalities:
1. Users can be created, edited, and deleted (GET, POST, PUT, DELETE)
2. Users can post 'thoughts' i.ei text between 1 and 280 characters. Thoughts can be created, edited, and deleted. (GET, POST, PUT, DELETE)
3. Users can post 'reactions' to thoughts between 1 and 280 characters. Reactions can be created and deleted. (POST, DELETE)

The database can be tested and updated using a third-party API client such as Insomnia Core. 
![App screenshot](./assets/images/social-network-api-screenshot.png)

# Table of Contents
1. [Requirements](#requirements)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Questions](#questions)
5. [License](#license)

## Requirements
To use this app, you must have the following installed:
- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
- [Insomnia Core](https://insomnia.rest/products/insomnia) or a similar API client.

A basic knowledge of the command line is also required. See [here](https://datacarpentry.org/shell-genomics/02-the-filesystem/index.html) for help navigating directories in the command line.

## Installation

1. To install the app, clone the respository above, or download as a .zip file.

![Image of download button](./assets/images/installation-1.png)

![Download options](./assets/images/installation-2.png)

2. In the command line, navigate to the directory containing the downloaded repsitory.
3. Download the required dependencies by typing the following in the command line: `npm install`

## Usage
To make requests to the database:
1. In the root directory of the app, start the server by entering `npm start` in the command line.
2. Enter the URL `http://localhost:3001/api` in Insomnia Core.
3. In Insomnia Core, you can make GET, POST, PUT, and DELETE requests for users, thoughts, and reactions.
