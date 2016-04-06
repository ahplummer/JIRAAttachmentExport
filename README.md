## JIRAAttachmentExport
###Description
Use this utility to export all attachments for a set of issues for given JQL format.
###Usage
```$python.exe JIRAAttachmentExport.py -baseurl=https://<you>.atlassian.net -jql="project=TEST and resolution = Unresolved" -throttleissues=3```

* -baseurl (required): a valid base URL that the API calls will be appended to.
* -jql (required): any valid JIRA JQL
* -throttleissues (optional): number of issues to grab per HTTP request
