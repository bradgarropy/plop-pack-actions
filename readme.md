## 💧 plop-pack-actions

<a href="https://npmjs.com/package/@bradgarropy/plop-pack-actions">
    <img alt="npm" src="https://img.shields.io/npm/v/@bradgarropy/plop-pack-actions.svg?style=flat-square">
</a>

<a href="https://npmjs.com/package/@bradgarropy/plop-pack-actions">
    <img alt="npm" src="https://img.shields.io/npm/dt/@bradgarropy/plop-pack-actions?style=flat-square">
</a>

_A collection of [plop][plop] actions to make your life easier._

### 📦 Installation

This package is installable from [npm][npm].

```bash
npm install --save-dev @bradgarropy/plop-pack-actions
```

### 🥑 Usage

Before you can use the `plop-pack`, you have to load it into the `plop` object.

```javascript
plop.load("@bradgarropy/plop-pack-actions")
```

Once loaded, you now have access the following actions.

#### `copy`

Copies a file from a source path to a destination path.

```javascript
{
    type: "copy",
    src: "templates/default.jpg",
    dest: "my-blog-post/images/default.jpg"
}
```

### ❔ Questions

🐛 report bugs by filing [issues][issues]  
📢 provide feedback with [issues][issues] or on [twitter][twitter]  
🙋🏼‍♂️ use my [ama][ama] or [twitter][twitter] to ask any other questions

[plop]: https://plopjs.com
[npm]: https://npmjs.com
[issues]: https://github.com/bradgarropy/plop-pack-actions/issues
[twitter]: https://twitter.com/bradgarropy
[ama]: https://github.com/bradgarropy/ama
