You can submit a new workflow, or an update to an existing one, in three different ways:

- Creating an issue on GitHub
- Use the **Submit to Workflow Directory** workflow
- Submitting a pull request

If your workflow makes use of an API, make sure that you use Import Questions and remove your API keys before submitting. It should not violate an API developer's terms of service as it would result in consequences for the user of the workflow.

## Creating an issue on Github

The easiest way to submit a workflow is to create a new issue on GitHub. A GitHub account is required. Follow the issue template and provide:

- Workflow name
- A description
- Link to the workflow at **workflow.is**

## Use the Submit to Workflow Directory workflow

You can use [this workflow](workflows/Submit%20to%20Workflow%20Directory/Submit%20to%20Workflow%20Directory.wflow) to create a submission request automatically. Copy the link for the workflow you want to submit and then run this workflow to create the required GitHub issue for you.

## Submitting a pull request

If you're familiar with Git, you can create a pull request containing the workflow you wish to add. When creating a pull request, make sure that the following steps are taken:

- Create a new directory for your workflow
- The **.wflow** workflow file is placed in this directory
- A README.md is created and added to this directory

### Format for README

The README for a workflow uses the following structure:

    # Workflow Title
    
    Submitted by: [@your_github](link_to_github_profile)
   
    Description of the workflow

To export a workflow, open the Share Sheet and select **Share as File**. When editing the README, make sure to place your workflow in alphabetical order and include a short description. 

## Updating a workflow

If you're submitting an update to an existing workflow:

    - Overwrite the existing **.wflow** file
    - Update the README.md (if required)
