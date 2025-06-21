# How to include emojis in your emails

If you try to use regular emojis (like 🎉 or 💸) in your Gmail Blaster emails, you’ll notice they don’t work. The tool can’t send messages that contain raw emojis — the email will simply fail to send.

#### The Fix

Instead of pasting emojis directly, you need to convert them into **HTML decimal codes**. That way, the emojis will show up properly in your emails _and_ the message will send without errors.

#### Example

❌ This won’t work:

```
Subject: 🎉 Special Deal!
```

✅ This will work:

```
Subject: &#127881; Special Deal!
```

#### Use the Emoji Converter

To make this easier, I’ve made a free tool that converts emojis into the correct format. Just paste the emoji and copy the result:

{% embed url="https://pythonandvba.com/go/gmail-blaster-emoji-converter" %}
