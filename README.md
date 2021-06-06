# Elsa - Global Banhammer

Elsa - Global Banhammer is a telegram bot that allows users to report and ban for the content they post.
This bot is exclusively for users who should be restricted from all telegram channels and should not be used for specific channels.

The bot uses a system of trust in the reporting user, reporting well increases trust (and therefore validation speed). Low confidence causes the bot to ignore reports sent by a user

If you have a problem, please send a new issue at https://github.com/TheWNetwork/ggbanbot-issues/issues

## Roadmap

See the [open issues](https://github.com/TheWNetwork/ggbanbot-issues/issues) for a list of proposed features (and known issues).

## Commands
### User Commands

- /help - Show the commands list you have available on Elsa
- /new|/report - Create a new report. Must be used replying a message
- /view - View latest 10 reports you have sent to Elsa
- /show {report} - View data about a specific report
- /me - Show the data the bot have about the user
- /comment {report} - Add a new comment on an existing report
- /about {id} - View info about a user.
- /stats - View bot statistics

### Moderator Commands

- /viewall|/all - View all open reports
- /accept {report} - Accept a report and send it to admins
- /reject {report} - Reject a report
- /close {report} - Close a report with no action
- /warn | /warning {report} - Close a report with a warning
