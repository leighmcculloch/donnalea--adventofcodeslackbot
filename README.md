# AdventOfCodeSlackbot
Slackbot/Keybasebot to notify when someone on the leaderboard has achieved a new star

# About
This project was built with Swift Package Manager with Swift 4 and generally followed this tutorial: 
<https://www.swiftbysundell.com/posts/building-a-command-line-tool-using-the-swift-package-manager>

# Environment Variables

A webhook URL must be set with one of these two environment variables:
`WEBHOOK`: Webhook URL for posting to Slack/Keybase.
`WEBHOOK_TYPE`: Which service will be receiving the webhook, should be `slack` or `keybase`. If unset, defaults to `slack`.
`ADVENT_COOKIE`: Advent-of-Code web cookie for authentication.
`ADVENT_JSON`: JSON URL for retrieving the leaderboard to monitor.

# Generating Xcode Project
`swift package generate-xcodeproj`




