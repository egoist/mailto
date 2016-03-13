# mailto

Public mail sending service, feel free to use it in personal service.

## How

POST `https://mailto.leanapp.cn/api/send`

Params:

|Name|Description|
|---|---|
|name|sender's name|
|email|the sender's email|
|sendTo|send to the email|
|subject|email subject|
|text|email content|

All params are required.

**Success**

```json
{
    "message": "Thanks! I will reply soon!"
}
```

**Failed**

```json
{
    "error": "Error message"
}
```

Example: https://egoistian.com/contact.html

## License

MIT &copy; [EGOIST](https://github.com/egoist)
