# Manage student repositories
* Set assignment deadlines
* Change access permissions (read/write) for students to their repositories
* Update files in student repositories with files from a template repository
* Remove files from student repositories
* Add/remove student repositories workflows
* Trigger student repositories workflows

# How to trigger workflows
1. On GitHub, navigate to the main page of the repository.
2. Under your repository name, click Actions.
3. In the left sidebar, click the workflow you want to run.
4. Above the list of workflow runs, select Run workflow.
5. Select the branch where the workflow will run and type the input parameters used by the workflow. Click Run workflow.

# Secrets
* CLASSROOM_TOOLS: https://github.com/ClassroomSuite/ClassroomTools
* REPO_PAT: A personal access token with repo permissions
* REPO_WORKFLOW_PAT: A personal access token with repo and workflow permissions
