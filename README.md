# PDF to CSV Conversion

This process uses OpenAI's GPT-4o-mini model which takes an incoming PDF and converts the important data into multiple dictionaries. These dictionaries will then be assigned to a DataFrame, which will be joined with an existing CSV file.

## Instructions
1. **Create CSV File**
   - Create a CSV file which can be used as database.
2. **Add CSV File Location and API Key**
   - Manually specify the location of your CSV file within the Notebook.
   - Add your OpenAI API key to authenticate the requests.
