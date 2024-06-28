# AI for Developer Productivity: Technical Writer Agent

## Overview
In this project, we developed a **Technical Writer Agent** to enhance developer productivity. The core functionality of our agent leverages Retrieval-Augmented Generation (RAG) to dynamically update and refine technical documentation. This innovative approach not only streamlines the documentation process but also ensures that it remains accurate, up-to-date, and contextually relevant.

## Now It's Your Turn!
Embrace your creativity and personalize this project to craft a solution that uniquely addresses the challenges and inefficiencies you face in your own environment. After seeing what our Technical Writer Agent can do, it’s time for you to take the reins. Use the foundation we’ve built and apply it to a challenge you face in your own professional or personal environment. Here’s how you can get started:

### Minimum Requirements
1. **RAG Integration:** Successfully integrate Retrieval-Augmented Generation (RAG) to enable your agent to access and utilize external information when generating responses.
2. **Vector Database Implementation:** Create and implement a vector data store capable of embedding and retrieving documents, ensuring that the system can access necessary information efficiently.

### Stretch Goals
1. **Enhanced UI/UX:** Develop a more advanced and user-friendly interface that includes features such as real-time suggestions, auto-completion of content, and a more interactive documentation process.
2. **Automated Content Updates:** Implement a feature where the agent periodically checks and updates existing documentation based on new information or changes in the relevant field, ensuring that all documentation remains current without manual intervention.
3. **Integration with Existing Tools:** Develop integrations for the agent with commonly used development tools and platforms (e.g., Confluence, Jira, Notion) to streamline workflows and increase accessibility.
4. **Add The Features You Want**: Let your creativity shine by adding a unique feature that significantly simplifies or enhances your daily routines. Innovate with functionalities that solve problems and improve efficiency or satisfaction in meaningful ways.

## Privacy and Submission Guidelines
- **Submission Requirements:** Please submit a link to your public repo with your implementation or a loom video showcasing your work on the [BloomTech AI Platform](app.bloomtech.com). 
- **Sensitive Information:** If your implementation involves sensitive information, you are not required to submit a public repository. Instead, a detailed review of your project through a Loom video is acceptable, where you can demonstrate the functionality and discuss the technologies used without exposing confidential data.

---

## README Update
### Changes
File: .github/workflows/update_readme.yaml
Diff:
@@ -19,7 +19,7 @@ jobs:
       - name: Setup Python
         uses: actions/setup-python@v3
         with:
-          python-version: '3.12'
+          python-version: '3.12.3'
 
       # Install Python dependencies
       - name: Install Dependencies
@@ -44,7 +44,7 @@ jobs:
         env:
           GITHUB_TOKEN: ${{ secrets.MY_GITHUB_TOKEN }}
           OPENAI_API_KEY: ${{ secrets.OPENAI_API_KEY }}
-          REPO_NAME: ${{ github.repository }}
+          REPO_PATH: ${{ github.repository }}
           PR_NUMBER: ${{ env.pull_request_number }}
 
       # Additional step to enable debugging, helps in troubleshooting

### Commit Messages
- Update python issue
- Update repo name