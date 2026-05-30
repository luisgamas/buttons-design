# Payment & Sponsorship Buttons for Markdown

A curated collection of ready-to-use buttons for **Buy Me a Coffee**, **PayPal**, and **GitHub Sponsors** — perfect for README files, documentation, landing pages, or any Markdown content.

All assets are free, public, and served directly via GitHub's raw CDN.

---

## Available Buttons

Each service provides two visual variants:

| Variant | Description |
|---|---|
| **Standard** | Outlined icon — clean and minimal |
| **Fill** | Solid icon — bolder and more prominent |

| Service | Directory | Standard | Fill |
|---|---|---|---|
| ☕ Buy Me a Coffee | `buy_me_a_coffe/` | `buy_me_a_coffe.svg` | `buy_me_a_coffe_fill.svg` |
| 💰 PayPal | `paypal/` | `paypal.svg` | `paypal_fill.svg` |
| ❤️ GitHub Sponsor | `github_sponsor/` | `github_sponsor.svg` | `github_sponsor_fill.svg` |

> **Note:** Old button designs have been moved to `buy_me_a_coffe_old/` and `paypal_old/` and are no longer recommended for use.

---

## Usage

### Markdown syntax

```markdown
[![Button label](IMAGE_URL)](LINK_URL)
```

### HTML syntax (custom size)

```html
<a href="LINK_URL">
  <img src="IMAGE_URL" width="220" alt="Button label" />
</a>
```

---

## Examples

### ☕ Buy Me a Coffee

| Style | Preview |
|---|---|
| Standard | [![Buy me a Coffee](https://raw.githubusercontent.com/luisgamas/buttons-design/main/buy_me_a_coffe/buy_me_a_coffe.png)](https://www.buymeacoffee.com/luisgamas) |
| Fill | [![Buy me a Coffee](https://raw.githubusercontent.com/luisgamas/buttons-design/main/buy_me_a_coffe/buy_me_a_coffe_fill.png)](https://www.buymeacoffee.com/luisgamas) |

```markdown
[![Buy me a Coffee](https://raw.githubusercontent.com/luisgamas/buttons-design/main/buy_me_a_coffe/buy_me_a_coffe.png)](https://www.buymeacoffee.com/luisgamas)
```

```markdown
[![Buy me a Coffee](https://raw.githubusercontent.com/luisgamas/buttons-design/main/buy_me_a_coffe/buy_me_a_coffe_fill.png)](https://www.buymeacoffee.com/luisgamas)
```

### 💰 PayPal

| Style | Preview |
|---|---|
| Standard | [![Donate with PayPal](https://raw.githubusercontent.com/luisgamas/buttons-design/main/paypal/paypal.png)](https://www.paypal.com/donate/?hosted_button_id=NYCR5M6QHZ7JC) |
| Fill | [![Donate with PayPal](https://raw.githubusercontent.com/luisgamas/buttons-design/main/paypal/paypal_fill.png)](https://www.paypal.com/donate/?hosted_button_id=NYCR5M6QHZ7JC) |

```markdown
[![Donate with PayPal](https://raw.githubusercontent.com/luisgamas/buttons-design/main/paypal/paypal.png)](https://www.paypal.com/donate/?hosted_button_id=NYCR5M6QHZ7JC)
```

```markdown
[![Donate with PayPal](https://raw.githubusercontent.com/luisgamas/buttons-design/main/paypal/paypal_fill.png)](https://www.paypal.com/donate/?hosted_button_id=NYCR5M6QHZ7JC)
```

### ❤️ GitHub Sponsor

| Style | Preview |
|---|---|
| Standard | [![Sponsor me on GitHub](https://raw.githubusercontent.com/luisgamas/buttons-design/main/github_sponsor/github_sponsor.png)](https://github.com/sponsors/luisgamas) |
| Fill | [![Sponsor me on GitHub](https://raw.githubusercontent.com/luisgamas/buttons-design/main/github_sponsor/github_sponsor_fill.png)](https://github.com/sponsors/luisgamas) |

```markdown
[![Sponsor me on GitHub](https://raw.githubusercontent.com/luisgamas/buttons-design/main/github_sponsor/github_sponsor.png)](https://github.com/sponsors/luisgamas)
```

```markdown
[![Sponsor me on GitHub](https://raw.githubusercontent.com/luisgamas/buttons-design/main/github_sponsor/github_sponsor_fill.png)](https://github.com/sponsors/luisgamas)
```

---

## Custom sizing (HTML)

When you need a specific button size, use the HTML `<img>` tag with a `width` attribute:

```html
<a href="https://www.buymeacoffee.com/luisgamas">
  <img src="https://raw.githubusercontent.com/luisgamas/buttons-design/main/buy_me_a_coffe/buy_me_a_coffe.png" width="200" alt="Buy me a Coffee" />
</a>
```

```html
<a href="https://www.paypal.com/donate/?hosted_button_id=NYCR5M6QHZ7JC">
  <img src="https://raw.githubusercontent.com/luisgamas/buttons-design/main/paypal/paypal.png" width="200" alt="Donate with PayPal" />
</a>
```

```html
<a href="https://github.com/sponsors/luisgamas">
  <img src="https://raw.githubusercontent.com/luisgamas/buttons-design/main/github_sponsor/github_sponsor.png" width="200" alt="Sponsor me on GitHub" />
</a>
```

---

## File format & compatibility

All buttons are provided in **SVG** (scalable, crisp at any size) and **PNG** (fallback for environments that do not render SVGs). We recommend using the PNG versions in Markdown for maximum compatibility across platforms (GitHub, GitLab, npm, etc.).

---

## License

This project is open and free to use. Feel free to include these buttons in your own projects without attribution.
