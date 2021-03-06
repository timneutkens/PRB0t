# 🤖 PRB0t
The Pull Request Bot for Anonymous contributions on GitHub!

---

[BETA] Url: `POST`:`https://xrbhog4g8g.execute-api.eu-west-2.amazonaws.com/prod/prb0t`

Request Sample:
```json
{
  "user": "<github-user>",
  "repo": "<github-repo>",
  "desc": "<commit-description>",
  "files": [
  	{"path": "<file-path>", "content": "<file-content>"}
  ]
}
```

## What can you do with it?

- If you have a static website hosted in github... you could add a button **Edit this page**.
- You can contribute anonymously to the *Internet 🕸*
- You can upload files...
- You can use your github for storage...
- ... etc... ecc..

## Try it!
```
curl -X POST \
  https://xrbhog4g8g.execute-api.eu-west-2.amazonaws.com/prod/prb0t \
  -H 'cache-control: no-cache' \
  -H 'content-type: application/json' \
  -d '{
  "user": "PRB0t",
  "repo": "PRB0t",
  "desc": "🤖",
  "files": [
  	{"path": "README.md", "content": "Failure is when you stop trying to do something."}
  ]
}'
```

## Contribute
[We're looking for Team members](https://github.com/PRB0t/PRB0t/issues/5) to form a little community around this little tool which we believe has a lot of potentialities ✨
