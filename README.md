# Integrity Systems Company - Common Animal Schema
Welcome to the GitHub repository for the common animal schema. 

This repository respresents livestock information using **JSON Schema** and **OpenAPI specification**. It brings together individual animal schemas from the [ICAR Animal Data Exchange Working Group](https://github.com/adewg/ICAR) and [DataLinker.org](https://datalinker.org). We intend that this repository will be used to identify entities and attributes that are needed to support Australian livestock farming, which will then be submitted back to ICAR and DataLinker for inclusion in global specifications.

## Contributing to this repository
You are welcome to contribute to this repository, and we encourage you to join our collaboration. Contributing to this project works like contributing to an open source project:
- Your contributions become part of the project; you can't enforce your own copyright over them.
- Please don't submit contributions that would breach confidentiality, non-disclosure, or controlled intellectual property rights.

## Using the Wiki
We will use the [Wiki](https://github.com/integritysystemscompany/animal_schema/wiki) to:
- Document the data dictionary for events and animal information.
- Record brief minutes from our meetings.
- Provide advice for using the common animal schema.

## Providing feedback and asking questions
The [Issues](https://github.com/integritysystemscompany/animal_schema/issues) section of this repository is the best place to ask questions and provide feedback. We prefer this approach to using email communication because then all collaborators can participate and learn from the discussion.
- Do search to see if anyone else has logged the same issue before adding yours.
- Do participate by commenting on issues logged by others.
- If you have several disparate items of feedback, please create separate issues to allow the discussion to progress for each area.
We will close issues once they have been resolved.

## In the Code section
You'll find the source code for JSON schemas and OpenAPI specifications in this folder. If you're unsure how things fit together, please see the Wiki. Both JSON Schema and OpenAPI files end in .json, so it can be hard to tell them apart at first glance. We will put -openapi in the file name of OpenAPI files to make it a little easier.
- You'll find the JSON Schema documentation at [json-schema.org](https://json-schema.org/). 
- Many people use the [Swagger UI](https://swagger.io/tools/swagger-ui/) to edit OpenAPI documents.
We will implement the Spectral JSON/OpenAPI validation tool as a GitHub Action. When you check in your code, Spectral will attempt to validate it. You'll find any errors or warnings in the GitHub [Actions](https://github.com/integritysystemscompany/animal_schema/actions) section. Please try to resolve all errors and warnings. Ask for help if you need it.

If you plan on editing or contributing to the code, we recommend that you fork the repository, check the Spectral validation results in your own fork, and ensure this is clean before submitting a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) to the master. We will review and merge pull requests.
