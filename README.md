# Book Listing App README

## Overview
This repository contains the source code for a book listing app built using the Lightning Web Components (LWC) framework on the Salesforce platform. The app utilizes the Fetch API to retrieve book data from the Google Books API.

## Features
- Display a list of books retrieved from the Google Books API.
- View detailed information about each book, including title, author, and description.
- Search for books by title, author, or keyword.

## Prerequisites
Before running the app locally or deploying it to a Salesforce environment, ensure you have the following:
- Salesforce Developer Edition account or access to a Salesforce environment.
- Node.js and npm installed on your local machine.
- Salesforce CLI installed and configured.

## Setup Instructions
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install project dependencies.
4. Deploy the app to your Salesforce environment using Salesforce CLI:
   ```bash
   sfdx force:source:deploy -p force-app
   ```
5. Once deployed, open your Salesforce org.
6. Navigate to the app builder and add the 'BookListingApp' component to a Lightning page.
7. Save and activate the Lightning page.
8. Access the Lightning page in your Salesforce org to view the book listing app.

## Usage
- Upon accessing the app, you will see a list of books retrieved from the Google Books API.
- Use the search bar to search for specific books by title, author, or keyword.
- Click on a book to view detailed information.

## Development
To contribute to the development of this app, follow these steps:
1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them to your branch.
4. Push your changes to your fork.
5. Submit a pull request to the main repository's `master` branch for review.

## Resources
- [Salesforce Developer Documentation](https://developer.salesforce.com/docs/)
- [Lightning Web Components Documentation](https://developer.salesforce.com/docs/component-library/documentation/en/lwc)
- [Google Books API Documentation](https://developers.google.com/books/docs/overview)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
