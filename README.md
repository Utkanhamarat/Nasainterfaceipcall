-NASA NEO API Test Automation Project-

Description: I developed a test automation project that queries and verifies celestial bodies near Earth between certain dates using NASA's Near Earth Object API. Environments were created within the scope of the project, test scenarios including GET requests, verification tests and error management processes were written. Technical Details: HTTP response code verification with 
pm.test("Valid code is 200", function () { pm.response.to.have.status(200); });
commands Automatically running tests at certain intervals using Collection Runner and Monitor Runner and analyzing the results API test automation, using Postman environment, working with JSON data, collection and monitor settings, analyzing test results. Technologies: Postman, REST API, JSON.
