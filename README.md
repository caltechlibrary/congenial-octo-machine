# Post New Repositories to Slack

This GitHub Actions workflow will parse the list of repositories and post any created in the last 25 hours to Slack with a message that includes the command to subscribe. This is an alternative to subscribing the entire organization which may include very noisy repositories. While it requires some manual work when new repositories are created, the notification reduces the chances that any necessary subscriptions will be overlooked.

The workflow requires a repository secret for `SLACK_BOT_TOKEN` and a repository variable for `CHANNEL_ID`.
