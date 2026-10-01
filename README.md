# RESTful API Security Assessment 

A practical API security testing project focused on assessing RESTful APIs 
against common authentication, authorization, business-logic and API
security risks.
 
## Objective.       
 
The objective is to demonstrate a structured methodology for identifying,
validating and documenting security weaknesses in REST APIs.

## Testing Methodology

The assessment process included:

1. API endpoint discovery
2. Request and response analysis
3. Authentication testing
4. Authorization testing
5. Parameter manipulation
6. Object-level authorization testing
7. Business-logic testing
8. Rate-limit testing
9. Vulnerability validation
10. Risk assessment
11. Remediation recommendations
12. Retesting

## Tools

- Burp Suite Professional
- OWASP ZAP
- Postman
- Kali Linux

## Security Testing Areas

Testing focused on areas including:

- Authentication
- Authorization
- BOLA / IDOR
- Mass Assignment
- Rate Limiting
- Input Validation
- Session and Token Handling
- JWT-related security
- Excessive Data Exposure
- Business Logic
- HTTP Methods
- API Error Handling

## Key Vulnerability Categories

### BOLA / IDOR

Testing whether an authenticated user can access objects belonging to
another user by modifying object identifiers or request parameters.

### Mass Assignment

Testing whether unexpected parameters can be submitted to API endpoints
and modify properties that should not be controlled by the client.

### Rate-Limit Bypass

Testing whether sensitive API functionality can be abused by sending
requests beyond the expected request threshold.

## Validation Process

Potential vulnerabilities were manually validated before being included
in assessment documentation.

Each finding included:

- Description
- Affected endpoint
- Request/response evidence
- Proof of Concept
- Impact
- Severity
- Remediation
- Retesting recommendation

## Remediation

Recommendations focus on:

- Server-side authorization
- Object-level access controls
- Allow-list based parameter handling
- Rate limiting
- Secure authentication
- Input validation
- Proper error handling
- Security logging and monitoring

## Ethical Testing Notice

All examples in this repository are sanitized and intended for authorized
security testing and educational purposes only.

Do not test APIs without explicit authorization.

No real credentials, customer data or private API information is included.
 
