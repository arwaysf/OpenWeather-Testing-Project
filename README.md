# OpenWeather Testing Project

## Overview  
The **OpenWeather Testing Project** is a comprehensive automation framework designed to ensure the functionality, reliability, and accuracy of OpenWeather's API and UI. By leveraging tools like Selenium IDE and Postman, the project aims to simplify testing workflows and integrate smoothly into CI/CD pipelines.

## Features  
- **API Testing:**  
  Validate and verify API endpoints using Postman, ensuring compliance with functional requirements and response integrity.  

- **UI Testing:**  
  Automate browser interactions using Selenium IDE to check for UI responsiveness, accessibility, and functionality.  

- **JSON Test Cases:**  
  Test scenarios, expected outcomes, and functional requirements are documented in structured JSON files for clarity and reusability.  

- **CI/CD Integration:**  
  Ready for integration with CI/CD pipelines, supporting efficient testing and deployment workflows.  

## Getting Started  

### Prerequisites  
- Install [Selenium IDE](https://www.selenium.dev/selenium-ide/) for UI testing.  
- Install [Postman](https://www.postman.com/) for API testing.  
- Ensure you have access to the OpenWeather API (sign up for a free API key [here](https://openweathermap.org/api)).  

### Installation  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/1med2/OpenWeather-Testing-Project.git  
   cd OpenWeather-Testing-Project  
   ```  
2. Set up the test environment based on the tools you'll be using (e.g., Selenium browser extension or Postman).  

### Running Tests  
- **UI Testing (Selenium):**  
  Import the Selenium project files into the Selenium IDE and execute the defined test suites.  
- **API Testing (Postman):**  
  Load the provided Postman collection and run the test cases.  

### CI/CD Integration  
- Add the Selenium and Postman tests to your CI/CD pipeline using tools like Jenkins, GitHub Actions, or GitLab CI/CD.  

## Project Structure  
- `/ui-tests`: Contains Selenium IDE test scripts.  
- `/api-tests`: Includes Postman collections and test cases.  
- `/docs`: Functional requirements and test scenarios in JSON format.  

## Contributing  
We welcome contributions! Please follow these steps:  
1. Fork the repository.  
2. Create a new branch for your feature or bug fix.  
3. Submit a pull request with a detailed explanation.  

## License  
This project is licensed under the [MIT License](LICENSE).  

## Acknowledgments  
Special thanks to the creators of Selenium and Postman for their powerful tools.  

For further details, check out the repository [here](https://github.com/1med2/OpenWeather-Testing-Project).  
