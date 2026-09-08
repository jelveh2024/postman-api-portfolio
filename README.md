# postman-api-portfolio
This repository contains API testing examples using Postman.

## Included
- CRUD API tests
- Environment configurations
- Automated assertions

## Tools Used
- Postman
- Newman

## How to Run
1. Import collection
2. Import environment
3. Run using Postman's collection run feature or via the following steps
4. Install Newman: sudo npm install -g newman
5. Install newman-reporter-html: sudo npm install newman-reporter-html
6. On command line: npx newman run postman_collection.json -e postman_environment.json --reporters cli,html --reporter-html-export report.html
