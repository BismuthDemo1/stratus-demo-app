Stratus is a site for processing and viewing meteorological predictions.

It was originally created by Nick Gregory that we now use to show Bismuth's capabilities as it's a medium complexity app
spanning a data processing queue, backend API, and frontend.

We've created a handful of issues in Jira representing real features and bugs.
Feel free to modify the issues, adding details on what you'd like to see Bismuth do.

To assign Bismuth to an issue, click Apps->Bismuth on the Jira ticket, select the repository, then click Assign.
Bismuth will pick up the issue, show you its progress in the ticket and, after a few minutes, open a completed PR.
You can also view everything Bismuth is doing by going to https://app.bismuth.cloud.

To see the changes Bismuth has made, you can run Stratus locally:

1. Clone the repo and checkout the PR's branch
1. Run `./dev.sh`
1. Run `./dev-data.sh` to load some initial data into the system. This will take a few minutes.

The frontend will then be available at http://localhost:3000
