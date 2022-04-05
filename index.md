<p align="center">
      <img src="https://cdn.discordapp.com/attachments/943708746813702154/950993331612168192/KairosBot-Banner.png">
</p>

## ❓How the bot works

If you have set your timezone and enabled automatic timestring detection and translation, the bot will automatically reply to any message that it detects a timestring in with the timestamp. It can also recognise and translate multiple timestrings in a single message. Here are examples of timestrings:

```
12:00
9:34 pm
07:34AM tmr
2:47 8 days ago
09:51pm 7 days later
11:58 ytd
```

Heres an example use case:\
![](https://cdn.discordapp.com/attachments/686061884843360256/952161746506895370/KairosBot-Demo.png)

## 📝Commands

```
key: [] is required and () is optional
```

### /settimezone [timezone]

Configures your timezone

### /gettimezone (@user)

Gets the timezone of a given user (defaults to yourself)

### /gettimezonetime [timezone]

Gets the local time of a given timezone

### /getusertime [@user]

Gets the local time of a given user

### /timestamp (hour) (min) (am_pm) (date) (month) (year) (date_format) (timezone) (include_raw)

Creates a timestamp according to the data you provide

### /enable

Enables automatic timestring detection and translation

### /disable

Disables automatic timestring detection and translation

### /help

Sends you some help

### /timestrings

shows you examples of timestrings

### /ping

Replies with "Pong" and the latency
