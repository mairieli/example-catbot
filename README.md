# CatBot example
This is an example created for the HICoDE course. 

If you would like to run the chatbot, please follow the steps below. It is recommended to use GitHub codespaces.

### Steps

1. **Create a Codespace:**
   - Click on the green "Code" button on this page, then scroll down to "Codespaces".
   - Click on "Create codespace on main".

2. **Set Up Environment:**
   - In the codespace, open the `.env` file from this repo and add your license key to that file.
     ```
     RASA_LICENSE='your_rasa_license_key_here'
     ```
   - Set this environment variables by running 
     ```
     source .env
     ```
   - Activate your python environment by running
     ```
     source .venv/bin/activate
     ```

4. **Train the Model:**
   - In the terminal, run:
     ```
     rasa train
     ```

5. **Talk to your Bot:**
   - In the terminal, run
     ```
     rasa inspect
     ```
     GitHub will show a notification, click on the green button to view the inspector where you can chat with your assistant.

