# Studio Log Topics

🏷 The topics used by [Studio Log][1].

## Usage

```js
const topics = require('@studio/log-topics');

console.log(topics.broadcase); // Prints 📣
```

## Install

```bash
❯ npm i @studio/log-topics
```

## Topics

Instead of log levels, [Studio Log][1] uses a set of topics to categorize,
format and filter logs. Unlike log levels, topics are not ordered by severity.

These topics are available:

- ✅ = `ok`
- ⚠️ = `warn`
- 🐛 = `issue`
- 🚨 = `error`
- 🙈 = `ignore`
- 🔺 = `input`
- 🔻 = `output`
- 📤 = `send`
- 📥 = `receive`
- 📡 = `fetch`
- 🏁 = `finish`
- 🚀 = `launch`
- ⛔️ = `terminate`
- ✨ = `spawn`
- 📣 = `broadcast`
- 💾 = `disk`
- ⏱  = `timing`
- 💰 = `money`
- 🔢 = `numbers`
- 👻 = `wtf`

## Related modules

- 👻 [Studio Log][1] logs ndjson to an output stream
- 🎩 [Studio Log Format][2] pretty print Studio Log nsjson
- 🌈 [Studio Emojilog][3] is a CLI to pretty print the Studio Log ndjson with emoji
- 📦 [Studio Changes][4] is used to create the changelog for this module.

## License

MIT

<div align="center">Made with ❤️ on 🌍</div>

[1]: https://github.com/javascript-studio/studio-log
[2]: https://github.com/javascript-studio/studio-log-format
[3]: https://github.com/javascript-studio/studio-emojilog
[4]: https://github.com/javascript-studio/studio-changes
