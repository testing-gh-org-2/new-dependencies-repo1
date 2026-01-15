# E2E Stage AZ - New Test Data

This project contains test data for dependency and vulnerability scanning.

## Project Structure

- `package.json` - Node.js dependencies for testing
- `vulnerabilities.json` - CVE vulnerability data for testing
- `index.js` - Sample Express application

## Dependencies

The project includes various npm packages with known vulnerabilities for testing purposes:

| Package | Version | Purpose |
|---------|---------|---------|
| axios | 0.21.1 | HTTP client |
| lodash | 4.17.20 | Utility library |
| express | 4.17.1 | Web framework |
| mongoose | 5.11.15 | MongoDB ODM |
| jsonwebtoken | 8.5.1 | JWT authentication |
| moment | 2.29.1 | Date manipulation |
| And more... | | |

## Vulnerabilities

The `vulnerabilities.json` file contains 15 CVE entries for testing, including:

- CVE-2021-3749 (axios)
- CVE-2021-23337 (lodash)
- CVE-2022-24999 (express)
- CVE-2022-2564 (mongoose)
- CVE-2022-23529 (jsonwebtoken)
- And more...

## Usage

```bash
# Install dependencies
npm install

# Run the application
npm start
```

## Note

This project is for testing purposes only. The vulnerable versions are intentionally included for security scanning tests.
