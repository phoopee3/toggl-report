# toggl-report
A small script to get toggl data by day based on a date range

**You will need a workspace id and an api token**

### Workspace ID

To get your wordkspace id, open toggl and click on `reports` in the left menu

The url will be something like `toggle.com/app/reports/summary/123456789/period/thisWeek`

The `123456789` is your workspace id

Change the line of code in `index.html` where it reads `var workspace_id = 0;` to your workspace id

### API Token

To get your API token, click on your name in the lower left corner of Toggl and click on `Profile Settings`

Scroll down to the bottom and there should be a field for API token

Change the line of code in `index.html` where it reads `var token = 'YOUR-API-TOKEN...';`

Make sure to leave the `:api_token` in the string
