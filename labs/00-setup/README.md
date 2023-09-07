# Setup for the labs

Here's a detailed walkthrough of what you need to get started with the labs.

## Prerequisites

- Complete the SAP Experience Garage mission (link in the event you've registered for).
- Create a Github Codespace on this repository.


## Environment Configuration
We need to update a configuration file in this repo so that the labs are able to make use of your Azure OpenAI service. In the root of this repository, you will see a file named `env.example`. Make a copy of this file in the same location (the root of the repository) and rename the file to `.env` (don't forget the period at the beginning of the filename!)

---

**A prepared file will be provided to you during the session by the instructors.** You need to copy+paste the contents to the new .env file you have created.



---

With all of the above updates to the `.env` file made, make sure you save the file and then you are ready to start the labs.

**NOTE**: The `.gitignore` file in this repo is configured to ignore the `.env` file, so the secrets such as the API key will not be uploaded to a public repo.

___

## Next Section

📣 [Prompts](../01-prompts/README.md)