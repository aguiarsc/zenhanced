<div align="center">

# 「 ✨ Zenhanced ✨ 」

<img src="https://github.com/user-attachments/assets/e4a95783-e2df-4e0e-8562-77a37609a1c0" width="800">

**A minimalist Zen Browser theme with CLI aesthetics for the ultimate Zen browsing experience**

</div>

---

## ⚡️ Overview

`Zenhanced` transforms your Zen Browser browser into a sleek, distraction-free environment with CLI-inspired aesthetics. Built atop Zen Browser's minimal interface, it adds:

- 🖥️ **Beautiful CLI-style borders** with floating monospace labels 
- 🌓 **Clean, dark aesthetic** with subtle transparency effects
- 🔄 **Smooth transitions & animations** throughout every UI element
- 🧩 **Consistent design language** with 3px border radius everywhere
- 🔍 **Enhanced URL bar** with elegant floating search panel
- 📑 **Refined tab styling** with customized pinned tab appearance

The result is a browsing experience that combines the minimalism of Zen Browser with the aesthetic appeal of terminal interfaces.


## 🛠️ Installation

```bash
# 1. First, enable custom CSS in Zen Browser
about:config → toolkit.legacyUserProfileCustomizations.stylesheets → true

# 2. Locate your profile folder
about:support → Profile Directory → Open Directory

# 3. Create chrome folder if needed
mkdir -p chrome

# 4. Copy theme files
cp userChrome.css userContent.css /path/to/chrome/

# 5. Restart Zen Browser
```

## ✨ Customization

Every aspect of Zenhanced is designed to be easily customizable:

- **Color Scheme** - Modify CSS variables in the theme files
- **Animations** - Adjust transition timings or disable effects
- **Spacing** - Fine-tune margins and padding throughout the UI
- **Borders** - Change border widths, colors, and radius values

The CSS files include extensive comments explaining each component, making customization accessible even to CSS beginners.

```css
:root {
  /* CLI-style interface colors */
  --cli-border-color: rgba(160, 160, 160, 0.55);       /* Adjust to taste */
  --cli-border-hover-color: rgba(220, 220, 220, 0.75); /* Hover state */
  --cli-corner-radius: 3px;                           /* Consistent radius */
  
  /* Many more customization options available */
}
```

## 🔧 Recommended Settings

For the optimal Zenhanced experience:

- 🎨 **Use Dark Theme** - The theme is designed for dark mode
- 📏 **Default Layout** - Do NOT enable compact mode
- ⌨️ **Custom Keybinds** - Set up keyboard navigation for a mouseless experience

## 👥 Contribute

Contributions are welcome and appreciated! Feel free to:

- **Report Issues** - Help identify styling bugs or misalignments
- **Suggest Features** - Have ideas to make Zenhanced even better?
- **Submit PRs** - Code contributions are always welcome

## 🙏 Credits & Inspiration

<div align="center">

Built upon the foundations of [**Zenplified**](https://github.com/sejjy/zenplified) by **sejjy**
&
[**TextFox**](https://github.com/adriankarlen/textfox) by **adriankarlen**

*Massive thanks for the inspiration!*

</div>
