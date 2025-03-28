Step-by-step Process Followed:
1. Installed Node.js and npm from https://nodejs.org
2. Created a new folder for the project: sit737-2025-prac4c
3. Initialized the project using npm init -y
4. Installed required libraries using:
npm install express winston
5. Created index.js file to write the microservice code
6. Implemented 4 basic API endpoints using Express:
/add?num1=&num2=
/subtract?num1=&num2=
/multiply?num1=&num2=
/divide?num1=&num2=
7. Implemented 3 advanced endpoints:
/power?base=&exponent=
/sqrt?num=
/modulo?num1=&num2=
8. Used isNaN() and other checks to handle invalid inputs and division by zero
9. Added meaningful HTTP 400 error messages for invalid requests
10. Created a /logs folder to store logs
11. Set up Winston logger to log:
Operation details (info logs)
Errors (in error.log)
12. Logged each API request with details like operation and operands
13. Ran the application using node index.js
14. Tested all endpoints using browser and Postman
15. Verified log files: logs/combined.log and logs/error.log
16. Wrote a short error handling report (error_handling_report.md) explaining Circuit Breaker, Retry, and Fallback
17. Created README.md and added all documentation
18. Initialized Git, committed the code, and pushed to GitHub repo:
https://github.com/Nishitha0304/sit737-2025-prac4c
19. Submitted the GitHub link through OnTrack
