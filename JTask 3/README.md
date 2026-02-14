# SQL Injection on DVWA (Low Security)

## Objective
Demonstrate SQL Injection vulnerability using DVWA.

## Tools Used
- DVWA
- XAMPP
- Browser

## Steps
1. Installed DVWA on local server.
2. Set security level to Low.
3. Injected payload: 1' OR '1'='1
4. Successfully retrieved all user records.

## Vulnerability Explanation
The application does not sanitize user input.
It directly inserts input into SQL query.
This allows attackers to manipulate database queries.

## Prevention
- Use Prepared Statements
- Input Validation
- Parameterized Queries
- Web Application Firewall
