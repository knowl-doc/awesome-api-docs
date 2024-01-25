1. **Install the Required Library**
```
pip install knowl_apidocs
```

2. **Clone the Repository (If Necessary)**

    ```
    git clone <repository_url>
    ```
    
3. **Setting Up Environment Variables (Optional)**
- In the repository's root directory, create a file named `.knowlenv`
- Add the following lines to your `.knowlenv` file
- Sign up to [app.knowl.ai](http://app.knowl.ai/) and generate the key KNOWL_API_KEY.
```
- KNOWL_API_KEY=your_knowl_api_key  # If blank or not found then openapi.yaml is generated but not api docs
```
4. **Execute the Documentation Command**:
- Navigate to your repository's directory and run:    
    ```
    knowl_apidocs <path_to_your_repository>
    ```
- This generates an OpenAPI.yaml in your repository's folder.
- Log in to https://www.app.knowl.io to access the API documentation if KNOWL_API_KEY is added in the .knowlenv file

6. **Completion of Documentation Generation**
    - The generation of your API documentation may take a few minutes.
    - You will receive an email notification once your API documentation is successfully generated.


###### Note: This CLI is still a work in progress, so you might get issues. Please report them to us and we will fix them on priority

