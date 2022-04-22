# Botty Botterson - Discord Bot

# [Discord API Docs](https://discord.com/developers/docs/getting-started#overview)

Useful software:

[Trello Board](https://trello.com/b/hdPVSuGj/discord-bot): Project management board / ticketing system

[Postman](https://app.getpostman.com/join-team?invite_code=21b0edb74f65a5492e06fbda2c62ea46)(Download this): Postman is a tool to simulate HTTP requests.

[ngrok](https://ngrok.com/)(Download this and [add to PATH](https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/)): ngrok is a network tunneling app that allow you to run servers locally and access them from the web (allow discord to ping your local host environment)
```
ngrok http 3000
```

You should see your connection open:

```
Tunnel Status                 online
Version                       2.0/2.0
Web Interface                 http://127.0.0.1:4040
Forwarding                    http://1234-someurl.ngrok.io -> localhost:3000
Forwarding                    https://1234-someurl.ngrok.io -> localhost:3000

Connections                  ttl     opn     rt1     rt5     p50     p90
                             0       0       0.00    0.00    0.00    0.00
```

Copy the forwarding address that starts with `https`, in this case `https://1234-someurl.ngrok.io`, then go to your [app's settings](https://discord.com/developers/applications).
