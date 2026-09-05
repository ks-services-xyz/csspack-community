# KSPack 📦

> A lightweight, modular, utility-first CSS framework built for rapid UI development and maximum flexibility.

KSPack organizes modern CSS utilities, base tokens, layout systems, and component helpers into clean, isolated modules. Use the full bundle or import only the specific utilities your project requires.

> KSPack provides a structured design system foundation built on CSS variables, flexible Grid/Flexbox layouts, responsive spacing, and standard utility classes.

---

## 🚀 Features

* **Modular Architecture:** Clear file structure allows importing only the utility modules you need.
* **Design Tokens First:** Standardized variables for colors, typography, sizing, and spacing in `base_variable.css`.
* **Flexbox & Grid Layouts:** Intuitive helper classes for modern layout patterns.
* **Responsive Utilities:** Utility classes designed for responsive layouts.
* **Zero Dependencies:** Pure, native CSS without preprocessor or compile-step requirements.
* **Utility-First:** Build interfaces quickly using small, reusable CSS utility classes.
* **Minification Ready:** Built-in scripts for generating production-ready build files.
* **Lightweight:** Use only what your project needs.

---

## 📦 Installation

Install KSPack using npm:

```bash
npm install @kraft.stitch/kspack
```

After installation, the compiled CSS files will be available inside the package.

---

## 🎨 Usage

Import the KSPack CSS file into your project:

```css
@import "@kraft.stitch/kspack/css-pack.min.css";
```

Or include the stylesheet directly in your HTML:

```html
<link
  rel="stylesheet"
  href="node_modules/@kraft.stitch/kspack/css-pack.min.css"
/>
```

---

## 🌐 CDN

KSPack can also be used directly from a CDN without installing it through npm.

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@kraft.stitch/kspack/css-pack.min.css"
/>
```

For production applications, you can pin a specific version:

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@kraft.stitch/kspack@1.0.0/css-pack.min.css"
/>
```

---

## 🧩 Utility Modules

KSPack is organized into independent utility modules so you can use the parts you need.

Typical modules include:

* Background utilities
* Color utilities
* Typography utilities
* Spacing utilities
* Display utilities
* Flexbox utilities
* Grid utilities
* Position utilities
* Sizing utilities
* Border utilities
* Border-radius utilities
* Responsive utilities
* Design tokens / CSS variables

Refer to the package source and documentation for the complete list of available utilities.

---

## 🎯 Example

```html
<div class="d-flex justify-center align-center p-4">
  <h1 class="text-primary">Hello KSPack!</h1>
</div>
```

KSPack utilities can be combined to build layouts without writing custom CSS for every component.

---

## 📚 Documentation

For detailed documentation, utility references, examples, and usage guidelines, visit the KSPack community repository:

👉 **[KSPack Documentation](https://github.com/ks-services-xyz/kspack-community)**

---

## 🐛 Issues & Feature Requests

Found a bug, have a feature idea, or want to suggest an improvement?

Please open an issue in the KSPack community repository.

👉 **[Report an Issue or Request a Feature](https://github.com/ks-services-xyz/kspack-community/issues)**

You can use GitHub Issues for:

* 🐛 Bug reports
* 💡 Feature requests
* 🎨 Utility suggestions
* 📚 Documentation improvements
* ⚡ Performance improvements
* 💬 General feedback

---

## 🤝 Contributing

Contributions and suggestions are welcome.

If you would like to contribute to KSPack:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes.
5. Create a pull request.

Please check the community repository for contribution guidelines.

👉 **[Contribute to KSPack](https://github.com/ks-services-xyz/kspack-community)**

---

## 📄 License

KSPack is released under the **MIT License**.

See the [LICENSE](LICENSE) file for the complete license text.

---

## ⭐ Support the Project

If you find KSPack useful, consider giving the project a ⭐ on GitHub.

Your feedback, suggestions, and contributions help improve KSPack.

**Made with ❤️ by @kraft.stitch**
