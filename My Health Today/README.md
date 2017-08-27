# My Health Today

Submitted by: [@jneug](https://twitter.com/jneug)

This workflow will help you quickly enter data into the Health app. There are many apps out there that specialize in a few data types and are great to get specific evaluations of your data, but this workflow is accessible from the Today view.

It can be configured to your needs, to show you only those data types you frequently update and a selection of values to enter with the tab of a button. To do this, the workflow has to be configured with a JSON dictionary of a specific form. If you know how JSON works, then just have a look at the provided example and write your own. If you don know what JSON is, then refer to the [Health Item Generator](/workflows/health-item-generator) workflow, for (nearly) fully automated config generation. 

**Important Note**: To use this workflow you need to give Workflows access to Health App. To do so, create a new workflow and add a “Log Health Sample” action. Select the type you want to use and tab “Grant Access”. Allow read and write access on the popup and tab allow at the top. Do this for every health type you want to access via Workflows.

# Health Item Generator

Submitted by: [@jneug](https://twitter.com/jneug)

Use this workflow to generate items for the My **Health Today** workflow. It can generate skeletons for the configuration dictionary used by the former workflow.