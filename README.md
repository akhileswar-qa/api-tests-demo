# api-tests-demo
# API Automation Tests - Postman Framework

# Pre-Requisites
- Node.js (https://nodejs.org/en/download/prebuilt-installer)
- Npm
- Newman (https://learning.postman.com/docs/collections/using-newman-cli/installing-running-newman/)
- Postman (https://www.postman.com/downloads/)
- HTML extra reporter (https://www.npmjs.com/package/newman-reporter-htmlextra)


# Commands/Options to to run colletction 
- Navigate to postman-api-tests folder 
- Run tests through command prompt including HTML reports generation 
```newman run reqres-in/reqres-api-validations.postman_collection.json -e reqres-in/test.postman_environment.json -r htmlextra --reporter-htmlextra-export reqres-in/report.html```

