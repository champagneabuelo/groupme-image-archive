# Groupme Image Archive

## Groupme URL to paginate through messages
https://api.groupme.com/v3/groups/[group_id]/messages?&limit=100&before_id=[message_id]
- pulling the last message ID of the request will paginate to the next page of messages
- the final request will return a 304 code

## Information needed to run script
- Groupme Developer Token
- Register project with Dropbox


## Useful Links/Docs
Groupme API Docs:
- https://dev.groupme.com/docs/v3

Dropbox Go SDK Docs:
- https://godoc.org/github.com/dropbox/dropbox-sdk-go-unofficial/dropbox/files#Client

Dropbox HTTP API:
- https://www.dropbox.com/developers/documentation/http/documentation#files-upload

Dropbox CLI, written in Go:
- https://github.com/dropbox/dbxcli
