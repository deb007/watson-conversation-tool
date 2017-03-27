# Watson Conversation Tool
The Watson Conversation Tool (wctool) is a Python-based command line tool to manage workspaces of the [IBM Watson Conversation](https://www.ibm.com/watson/developercloud/doc/conversation/index.html) service in IBM Bluemix.

# Overview
To use the tool, copy `config.json.sample` to `config.json` and insert your service credentials.

Some commands and parameters:
```
-l                             : List the workspaces
-g -id workspaceID -full       : Get details for a specific workspace
-g -id workspaceID -o outfile  : Save workspace to a file
```

# License
See [LICENSE](LICENSE) for license information.

# Contribute / Contact Information
If you have found errors or some instructions are not working anymore, then please open an GitHub issue or, better, create a pull request with your desired changes.

You can find more tutorials and sample code at:
https://ibm-bluemix.github.io/
