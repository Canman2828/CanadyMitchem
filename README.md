# ⌨️ Readme Typing SVG

**Dynamically generated SVG that simulates typing and deleting text**.  This project lets you embed an animated typing effect into GitHub READMEs or any web page to draw attention to key information.  It is inspired by [Sunny Patel’s profile README](https://github.com/sunnypatell#hey-there-im-sunny-patel-), which uses an animated headline to greet visitors.

## About the project

Readme‑Typing‑SVG is an open‑source service written in PHP that generates SVG images on the fly.  When embedded in a README or website, the SVG looks like text being typed and erased letter by letter.  You can choose your own lines of text, specify the height and width of the image, pick a font and colours, and control looping or pausing behavior.  The goal of the project is to help developers showcase their profiles or projects in a fun and animated way without writing complex code.

- **Self‑hostable** – The PHP code can be deployed on your own server or as a Heroku application, giving you full control over uptime and customization【582474615130771†L396-L403】.
- **Easy to integrate** – Embed the generated SVG in any README or HTML page with a single markdown snippet【582474615130771†L305-L314】.
- **Customizable** – Adjust parameters such as text lines, size, font, colours, alignment, duration and repetition【582474615130771†L364-L391】.
- **MIT licensed** – Free to use and modify for personal or commercial purposes【582474615130771†L449-L466】.

## 🚀 Quick start

1. Copy the markdown below into your GitHub README:

   ```md
   [![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Hello,+world!;Welcome+to+my+repo)](https://git.io/typing-svg)
   ```

2. Replace the `lines` parameter with your own phrases separated by semicolons.  Use `+` or `%20` for spaces【582474615130771†L305-L314】.
3. Adjust the `width` parameter if your longest line is cut off.  Increase the `height` or `size` parameters for bigger text【582474615130771†L369-L384】.
4. Commit and push your README—GitHub will display the animated typing effect automatically.

> 💡 **Tip:** You can experiment with different lines, fonts and colours at the **demo site**: [readme‑typing‑svg.demolab.com/demo/](https://readme-typing-svg.demolab.com/demo/)【582474615130771†L317-L322】.

## ⚙️ Parameters & customization

The service accepts query parameters so you can fine‑tune the look and behavior of the typing animation.  Here are some of the most useful options【582474615130771†L364-L391】:

| Parameter | Description | Example |
|-----------|-------------|---------|
| `lines`   | Text to display.  Separate multiple lines with a semicolon (`;`) and replace spaces with `+` or `%20` | `First+line;Second+line` |
| `height`  | Height of the SVG in pixels (default **50**) | `80` |
| `width`   | Width of the SVG in pixels (default **400**) | `500` |
| `size`    | Font size in pixels (default **20**) | `30` |
| `font`    | Any font from Google Fonts (default **monospace**) | `Fira+Code` |
| `color`   | Text colour in hex without `#` (default **36BCF7**) | `F724A9` |
| `background` | Background colour in hex without `#` (default transparent) | `000000` |
| `center` | `true` to centre text or `false` for left alignment (default **false**) | `true` |
| `vCenter` | `true` to vertically centre text; `false` aligns text above centre (default) | `true` |
| `multiline` | `true` to wrap lines or `false` to retype on one line (default **false**) | `true` |
| `duration` | Time to print a single line in milliseconds (default **5000**) | `3000` |
| `pause` | Pause between lines in milliseconds (default **0**) | `1000` |
| `repeat` | `true` to loop from the first line after the last (default **true**) | `false` |
| `separator` | Custom separator used between lines (default `;`) | `//` |
| `letterSpacing` | CSS [letter‑spacing](https://developer.mozilla.org/docs/Web/CSS/letter-spacing) value (default **normal**) | `2px` |

For the full list of parameters and examples, see the [Options](#parameters--customization) section of the original project README【582474615130771†L364-L393】.

## 🤚 Demo & examples

### Live demo
Use the live preview site to build and preview your typing SVG before adding it to your README:

- 🌐 **Demo Site:** [https://readme-typing-svg.demolab.com/demo/](https://readme-typing-svg.demolab.com/demo/)【582474615130771†L317-L322】

### Profiles using this project
Want inspiration?  Here are a few GitHub profiles that embed Readme‑Typing‑SVG:

- [Jonah Lawrence](https://github.com/DenverCoder1) – creator of this project【582474615130771†L325-L333】
- [Waren Gonzaga](https://github.com/wearenotreal) – uses a colourful typing intro【582474615130771†L325-L333】
- [Aditya Raute](https://github.com/adiXcodr) – integrates multiple lines for a longer message【582474615130771†L325-L333】

Feel free to open a pull request on this repository’s README to add your own profile to the list【582474615130771†L325-L333】.

## 🌧 Deploying it yourself

Although the public demo service is available, you can host your own instance for better uptime and full control【582474615130771†L396-L403】.  Deployment options include:

1. **PHP server:**  Copy the PHP files to any server with PHP installed.
2. **Heroku:**  Use the provided “Deploy to Heroku” button and follow the on‑screen instructions【582474615130771†L406-L417】.

After deployment, use your server’s URL instead of `readme-typing-svg.demolab.com` in the markdown snippet.

## 🤝 Contributing & support

Contributions are welcome!  Whether you fix a bug, add a feature, or improve the documentation, please open an issue or submit a pull request【582474615130771†L419-L428】.  Before submitting a PR, test your changes locally and ensure they follow the project’s guidelines.

If you like this project, please ⭐ star the repository and share it with others【582474615130771†L430-L433】.  You can also support the maintainer via [GitHub Sponsors](https://github.com/sponsors/) or [Ko‑fi](https://ko-fi.com/)【582474615130771†L430-L437】.

## 📜 License

This project is released under the **MIT License**【582474615130771†L449-L466】, so you can use it freely in personal and commercial projects.  See the [LICENSE](LICENSE) file for full license text.

---

Made with ❤️ using PHP and inspired by the engaging style of Sunny Patel’s profile README.  Bring your README to life with animated typing!
