IPMA Weather API Testing with Postman

This project demonstrates API testing using the IPMA Weather API.

The goal is to validate that the API endpoints respond correctly, return valid data, and meet expected performance requirements.

API tested:
https://api.ipma.pt/

---

Tools and Technologies:

- Postman
- JavaScript
- API Testing
- JSON Validation

---

API Endpoints Tested:

- Weather Forecast
- Districts and Islands
- Precipitation Classes
- Sea Locations
- Weather Type Classes
- Wind Speed Classes

---

Validations Implemented:

- Status code validation
- Response time validation
- JSON response validation
- Response body validation
- Content-Type header validation

---

Example Test:

Javascript:

pm.test("Status code should be 200", function () {
    pm.response.to.have.status(200);
});