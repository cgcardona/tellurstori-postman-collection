# TellUrStori POSTMAN Collection

This `README` provides guidance on how to setup and use the TellUrStori POSTMAN collection. The collection includes a set of predefined requests for interacting with the TellUrStori API, allowing you to manage and test functionalities related to users, threads, and AI-generated content such as texts, images, and audios.

## Prerequisites

Before you begin, ensure you have the following installed:
- [Git](https://git-scm.com/downloads)
- [Postman](https://www.postman.com/downloads/)

## Setup

### Cloning the GitHub Repository

To get started, clone the repository that contains the Postman collection:

```bash
git clone https://github.com/cgcardona/tellurstori-postman-collection.git
cd tellurstori-postman-collection
```

### Installing the Postman Collection

1. Open Postman.
2. Click on `Import` in the top left corner.
3. Choose `File` and drag the `TellUrStori.postman_collection.json` file into the target area or use the file selector to navigate and select the JSON file.
4. Click `Import` to add the collection to your Postman workspace.

## Using the POSTMAN Collection

### Sending Requests

- Select a request from the collection on the left sidebar.
- Review the pre-filled request parameters and body.
- Click the `Send` button to execute the request.

### Viewing Responses

- Once a request is sent, the response will be displayed in the lower section of the Postman interface.
- You can review the status code, response time, and the body of the response.

### Sending New Body Data

- To modify the body of a request (for POST or PUT methods):
  - Navigate to the `Body` tab below the request URL.
  - Modify the JSON or form data as required.
  - Send the request to view the new response.

### Update Environment Variables

- To manage environment variables:
  - Go to the `Environment` quick look (eye icon on the top right) and click `Edit`.
  - Add or update the variables such as `base_url` or `port`.
  - Save the changes and ensure the correct environment is selected from the dropdown next to the eye icon.

### Additional Tips

- **Authorization**: If the API requires authentication, set up the authorization methods under the `Authorization` tab.
- **Saving Responses**: You can save responses for future reference by clicking `Save Response`.
- **Documentation**: Utilize Postman’s ability to generate and publish beautiful, machine-readable documentation directly from the collection.

## Conclusion

This README provides a basic guide to importing and using the TellUrStori POSTMAN collection. For more detailed information, refer to Postman's official documentation or the specific documentation for the TellUrStori API.