# AI Service — Red Team Exercise Manager

## Features
- Generate cybersecurity incident reports
- AI-powered (Groq API)
- Input validation and error handling
- Security tested (ZAP)

## Endpoint

POST /report

## Example Request

curl -X POST http://127.0.0.1:5000/report \
-H "Content-Type: application/json" \
-d '{"text": "phishing attack"}'

## Example Response

Returns structured cybersecurity report with:
- Title
- Summary
- Risk level
- Impact
- Recommendations

## Tech Stack
- Python (Flask)
- Groq API (LLM)
- Pytest (testing)
- OWASP ZAP (security)

## Status
Project completed and validated