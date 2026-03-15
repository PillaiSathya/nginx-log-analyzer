# Nginx Log Analyzer (Shell Script)

A simple command-line tool that analyzes Nginx access logs using Bash and common Linux utilities.

This project was built as part of my DevOps practice to strengthen Linux log analysis and shell scripting skills.

## Features

- Top 5 IP addresses with most requests
- Top 5 most requested paths
- Top 5 response status codes
- Top 5 user agents

## Technologies Used

- Bash
- awk
- sort
- uniq
- head

## Project Structure

nginx-log-analyzer
│
├── access.log
├── log_analyzer.sh
└── README.md

## Usage

Make the script executable:

chmod +x log_analyzer.sh

Run the script:

./log_analyzer.sh access.log

## Example Output

Top 5 IP addresses with most requests:
216.46.173.126 - 2350 requests
180.179.174.219 - 1720 requests

Top 5 most requested paths:
/downloads/product_1 - 30285 requests

![Example Output](docs/example_output.png)

## Learning Outcomes

Through this project I practiced:

- Parsing logs using awk
- Data aggregation using sort and uniq
- Command-line automation using Bash
- Understanding web server log formats

This project helped me better understand how DevOps engineers troubleshoot production systems using log analysis.

## Project Reference

This project is based on the DevOps roadmap project:

https://roadmap.sh/projects/nginx-log-analyser