# Software-Engineer-ntern-Zeotap
“Enhancing CDAP Wrangler with byte size &amp; time parsers + ClickHouse ingestion tool”

Software Engineer Intern - Assessment Repository
Overview
This repository contains the code and solutions for the Software Engineer Intern assessment tasks provided. It includes two assessments:

1st Assessment – Wrangler Byte Size and Time Duration Parsers.

2nd Assessment – Bidirectional ClickHouse & Flat File Data Ingestion Tool.

Each assessment has its respective tasks, requirements, and implementation details.



Assessment 1 - Wrangler Byte Size and Time Duration Parsers

Assessment 2 - Bidirectional ClickHouse & Flat File Data Ingestion Tool

Testing

Installation
Follow these steps to get the project running on your local machine.

1. Clone the Repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
2. Install Dependencies
If you're working with the Wrangler Parser in Java, use Maven:


mvn clean install
For the Bidirectional ClickHouse & Flat File Data Ingestion Tool, install any necessary Python, Golang, or Java dependencies as specified in the relevant part of the repository.

3. Run the Application
Follow the instructions provided in the respective assessment folders. Each assessment may require different runtime environments or execution instructions.

Usage
1. Assessment 1 - Wrangler Byte Size and Time Duration Parsers
Objective: Enhance the Wrangler application by adding parsers for byte size and time duration.

Tasks:

Modify ANTLR Lexer and Parser to support new byte size and time duration formats.

Implement classes for ByteSize and TimeDuration to handle parsing and conversions.

Add new token types and update the RecipeVisitor to handle them.

Implement and test the aggregate-stats directive to calculate total data transfer size and response time.

To run this part of the project, follow the instructions provided in the wrangler folder.

2. Assessment 2 - Bidirectional ClickHouse & Flat File Data Ingestion Tool
Objective: Build a web application to transfer data between ClickHouse and flat files.

Tasks:

Create a frontend UI to allow users to select data sources (ClickHouse or Flat File).

Implement backend logic for bidirectional data flow:

ClickHouse to Flat File: Export selected columns from ClickHouse to a file.

Flat File to ClickHouse: Import selected columns into ClickHouse.

Include JWT authentication for secure ClickHouse connection.

Display progress and result (success/failure) of the data ingestion process.

To run this part of the project, follow the instructions in the clickhouse_ingestion folder. Make sure to have ClickHouse set up and running locally or via Docker.

Testing
Unit tests for both assessments are available in the respective test folders (wrangler-api for Wrangler Parser, and clickhouse-ingestion for the Ingestion Tool).

To run tests for Assessment 1:
mvn test
For Assessment 2, ensure you have the necessary environment and dependencies set up for testing (e.g., ClickHouse, database connections).

Contributions
If you'd like to contribute to this repository, feel free to open a pull request. Please make sure to follow the instructions for submitting pull requests.


