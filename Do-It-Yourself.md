### For Open Source Project
- As of now, you can create an issue requesting the API documentation with the repository link.
- We will create the document, verify it, and send you the link.

We will soon launch a version for anyone to create documentation of open source projects and help the community

### For Private Repositories
This CLI is still a work in progress, so you might get issues. Please report them to us and we will fix them on priority

1. **Install the Required Library**
    - Begin by installing the **`knowl_apidocs`** library. Open your command line interface and execute the following command:

```
pip install knowl_apidocs
```

2. **Clone the Repository (If Necessary)**
    - If you haven't already, clone the repository to your local machine. This step is essential to ensure you have the latest version of the repository for generating documentation.
    
    ```
    git clone <repository_url>
    ```
    
3. **Setting Up Environment Variables (Optional)**
    - For **`KNOWL_API_KEY`**, Sign up or log in to app.knowl.ai and Generate the key
    - For the **`OPENAI_API_KEY`**, [visit your OpenAI account](https://platform.openai.com/api-keys) dashboard to retrieve it.
    - In your repository's root directory, create a file named **`.knowlenv`** and add the following lines to your **`.knowlenv`** file, replacing the placeholders with your actual keys.

```
KNOWL_API_KEY=your_knowl_api_key
# Note: Without KNOWL_API_KEY, you will not receive a link to the API Docs and only openAPI.yaml will be saved in your repository.
OPENAI_API_KEY=your_openai_api_key
# Note: Use your own OpenAI key if preferred.
```
4. **Execute the Documentation Command**:
    - In the CLI, navigate to your repository's directory and run:
    
    ```
    knowl_apidocs <path_to_your_repository>
    # This generates an OpenAPI.yaml in your repository's folder.
    # If KNOWL_API_KEY is set in the .knowlenv file, log in to https://www.app.knowl.io to access the complete API documentation.
    ```
    
5. **Completion of Documentation Generation**
    - The generation of your API documentation may take a few minutes.
    - You will receive an email notification once your API documentation is successfully generated.



