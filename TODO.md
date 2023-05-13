# Task List for Proof of Concept

1. Create Data Adapters
   - [ ] Implement BigQuery adapter
   - [ ] Implement Postgres adapter
   - [ ] Implement MySQL adapter

2. Enhance Adapters with Metadata Retrieval
   - [ ] Add functionality to fetch schema information from the adapters
   - [ ] Retrieve table descriptions from the adapters
   - [ ] Include creation and last modified timestamps for tables
   - [ ] Retrieve table NULL and distinct value information

3. Standardize Metadata Format
   - [ ] Implement a standard data format and convention for the fetched metadata
   - [ ] Convert the metadata from each adapter to the standard format

4. Incorporate OpenAI GPT-4 API
   - [ ] Integrate the OpenAI GPT-4 API into the project
   - [ ] Prepare an engineered prompt for the AI to understand the task

5. Feed Metadata Information to AI
   - [ ] Pass the standardized metadata to the AI model as input
   - [ ] Utilize the metadata to enhance the AI's understanding and responses

6. Accept User Input for Query
   - [ ] Develop a user interface to gather input data from the user
   - [ ] Collect user-provided information to enhance AI query generation

7. Extract SQL from AI Response
   - [ ] Implement functionality to extract the generated SQL from the AI's response

8. Perform Query Validations
   - [ ] Develop validation logic to ensure the generated SQL meets certain criteria
   - [ ] Perform syntax checks and other relevant validations on the generated query

9. Execute Query in Adapters
   - [ ] Run the generated SQL query in the appropriate adapter (BigQuery, Postgres, MySQL)
   - [ ] Retrieve the query results from the adapter

10. Make Results Visualization Friendly
    - [ ] Format and structure the query results for better visualization
    - [ ] Consider appropriate visualization tools or libraries for displaying the results

11. Display Query Results
    - [ ] Present the query results to the user in a user-friendly manner
    - [ ] Provide options for exporting or saving the results if needed


