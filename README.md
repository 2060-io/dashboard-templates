# Dashboard Templates

This is an open-source project that manages various templates for deploying services on Kubernetes related to the 2060 project ([2060.io](https://2060.io/)). The goal is to facilitate rapid deployment when generating custom chatbots.

## Considerations

- If you wish to contribute to the templates, create a pull request. After undergoing validation for consistency with the template version, it will be added to the repository.
  
- It's important to note that the template file for Fastbots includes a 'config.yml' file. This file contains the generic deployment used by the project. Since this project aims to create custom chatbots, this file can be highly parameterized according to your needs. If you require a personalized chatbot, feel free to fork this repository and customize the file. Additionally, note that the 'schema.yml' file in this project contains the validation schema applied to 'config.yml'. It ensures necessary tests are conducted to validate its consistency.

