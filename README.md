# API-testing-Podio
This repository serves as an addition to the organization's project originally hosted privately in [Azure DevOps](https://azure.microsoft.com/en-us/products/devops) . Here, you will find comprehensive information and resources that provide valuable context for the project.
## About
The API-testing.podio project was developed as part of the QA Automation Bootcamp. It focuses on performing comprehensive testing related to  [Podio](https://podio.com), an online team collaboration and project management platform offering both UI and API functionalities.  
To ensure efficient and agile testing practices, we adopted the Behavior-Driven Development (BDD) methodology. By following this approach, we aim to enhance collaboration among team members and promote a shared understanding of project requirements and testing scenarios.  
To automate and streamline the testing process, we utilized Azure DevOps pipelines. These pipelines enable us to automatically run the tests and generate detailed reports. By leveraging the power of automation, we strive to increase testing efficiency and maintain the quality of the Podio platform.  
Through the API-testing.podio project, our goal is to provide thorough and reliable testing coverage, ensuring the stability and usability of Podio for its users.

### Scope
At the core of Podio lies its principal feature known as "Apps." These Apps serve as form builders, allowing users to create structured data entry points tailored to their specific needs. Within each App, users can create instances called "Items" that represent individual entries or records.
![image](https://github.com/kevingaray/API-testing-Podio/assets/48739137/8dfdbff9-d814-4dad-8acc-43513c0a8e27)

### Technologies
The project incorporates various technologies to support its development and testing processes. The following technologies are utilized:
| Technology            | Tool                                   |
|-----------------------|----------------------------------------|
| Language              | python 3.11                            |
| Test framework        | Pytest-bdd                             |
| Test style            | Cucumber-gerking                       |
| Api interactions      | Postman  / Insomnia                    |

### Conventions
- GIT: The project adopts the trunk-based strategy for version control, which encourages frequent integration of code changes into the main branch, promoting collaboration and minimizing conflicts.
- Python: When naming classes, PascalCase is used, which means that each word in the class name is capitalized. For methods and docstrings, snake_case is employed, where words are separated by underscores.
- Test Tags: Descriptive names are used for test tags, providing clarity and ease of identification. Snake_case is employed for tag titles, where words are separated by underscores.
- Feature Files: Snake_case is used for naming feature files, ensuring consistency and clarity. The file names are descriptive, providing a clear understanding of the contained features.

## Test Examples
![image](https://github.com/kevingaray/API-testing-Podio/assets/48739137/2f88eae2-6e0e-4a46-9580-b1cabee750ea)
![image](https://github.com/kevingaray/API-testing-Podio/assets/48739137/0ddca327-934f-4416-8a31-d3670ab384ad)

## Reported Bugs
01. Delete Action isn't available via API 
![image](https://github.com/kevingaray/API-testing-Podio/assets/48739137/b82e450a-4ee3-4185-9f49-7abf6070a255)
02. Update comment has not response body 
![image](https://github.com/kevingaray/API-testing-Podio/assets/48739137/11b2ca9d-942c-4724-9bb4-ae3410f63795)
03. Update Item has not show completed body 
![image](https://github.com/kevingaray/API-testing-Podio/assets/48739137/b1f67002-c1b6-4f60-b56a-1fcd1c2ebc17)

## Azure Dev Ops
Board
![00 azure devops](https://github.com/kevingaray/API-testing-Podio/assets/48739137/f6e4592a-e4e4-43c5-9c1d-0ffb471cf2c2)
Repo
![01 azure repo](https://github.com/kevingaray/API-testing-Podio/assets/48739137/803db31d-9d76-4829-8c94-14aafa05517c)
Pipelines
![02 pipelines](https://github.com/kevingaray/API-testing-Podio/assets/48739137/c720deba-82f8-4a8e-add9-0f55b6c48558)
Cucumber Reports
![03 cucumber reports](https://github.com/kevingaray/API-testing-Podio/assets/48739137/dba46895-453c-4497-8c2f-2d38add45ed1)

## Podio documentation
Visit [Podio developers](https://developers.podio.com/doc)
