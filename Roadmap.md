Day 0 --> 23/02/2024

- Day 0 and  Day 1 
User Data Upload:
    - Enable users to upload documents of various formats (PDF, PPT, Word, etc.) to a designated Google Drive folder.
        -Step 1 
            - Creating Google cloud Project
            - Enable Google Drive API 
            - Creating Service Account Credential 
            - Adding New Keys 
            - Download Project_name_key.json
        - Step 2 
            - Creating System to upload Data files on spesific Google Drive 

    - Support for multiple file formats allows for a broad range of document types to be indexed and searched.

- Day 2 and Day 3
    - Development of a Query Interface
    - Automate the process of transferring uploaded documents from Google Drive to a server environment where they can be processed and indexed.
    - Use Llama Index to create a searchable database of the uploaded documents, incorporating detailed metadata for each file, such as titles, paragraph numbers, page numbers, etc.
- Day 4
Development of a Query Interface
    - Develop a Streamlit application or a similar frontend-based system that interfaces with the indexed data.
    - Allow users to perform searches with the indexed data, returning relevant document snippets along with comprehensive metadata

#### Challenge 
1. How to prevent reload of already loaded documents 
2. How to Automarte on the event on data upload or data create on Google Drive 


#### Query 1 
- Should I Use a Single Google Drive (my drive) as sorage system for all users or Each user can use there own Google Drive and share link to my System 

- ### Solution Architecture 
1. 1 person | 1 Index | 1 Folder 
2. 1 person | Multiple Index | Multiple Folder With Selection 
3. Multiple person | 1 Index | 1 Folder 
4. Multiple person | Multiple Index | Multiple Folder With Selection 