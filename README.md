# Zed Editor Configuration ⚙️

This repository houses my personal configuration for the [Zed editor](https://zed.dev/), a lightning-fast, collaborative code editor. It's designed for optimal productivity and a visually pleasing coding experience.

## ✨ Features

- **Vim Mode Enabled**: Enjoy the power and efficiency of Vim keybindings.
- **Custom Fonts**:
    - **UI**: `CaskaydiaCove Nerd Font Propo` at size `15` for a clean and readable interface.
    - **Buffer**: `CaskaydiaCove Nerd Font Mono` at size `13` for a distraction-free coding experience.
    - **Terminal**: `CaskaydiaCove Nerd Font Mono` at size `12` for consistent look and feel.
- **Theme**:
    - **System Aware**: The theme adapts to your system's light/dark mode settings.
    - **Light Mode**: Catppuccin Frappé for a bright and inviting look.
    - **Dark Mode**: Catppuccin Mocha for a rich and comfortable coding environment.
- **AI Assistant**:
    - **Google Gemini**: Powered by the lightning-fast `gemini-2.0-flash-exp` model for your coding needs.
    - **Experimental Models**: Includes support for Google's `learnlm-1.5-pro-experimental` model as well.
- **Privacy-Focused**: Telemetry and diagnostic data collection are explicitly disabled.
- **Optimal UI Settings**: Carefully chosen font sizes to improve visual clarity.
- **Auto-Installed Extensions**: Includes automatic installation of several popular extensions:
  - `catppuccin` (for theme support)
  - `csv` (for CSV file editing)
  - `docker-compose` (for Docker Compose files)
  - `dockerfile` (for Dockerfile editing)
  - `git-firefly` (for enhanced Git integration)
  - `html` (for HTML file editing)
  - `lua` (for Lua language support)
  - `nix` (for Nix language support)
  - `ruff` (for Python code linting with Ruff)
  - `toml` (for TOML file editing)

## 🚀 Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yousiki/zed-config ~/.config/zed
   ```

   **Note:** If you have already customized your Zed settings, ensure you back them up first!

2. **Replace Existing Settings:** Copy the content of `zed/settings.json` from this repository and overwrite your existing `~/.config/zed/settings.json` file.

3. **Launch Zed:** Open or restart Zed editor. It will load the new configuration.

4. **Font Requirement:** Make sure you have `CaskaydiaCove Nerd Font Propo` and `CaskaydiaCove Nerd Font Mono` installed on your system. You can find these fonts at:
   - [Nerd Fonts](https://www.nerdfonts.com/)

## 📝 Customization

Feel free to modify `zed/settings.json` to match your preferences. This is a starting point and is meant to be further customized by you.

## 💡 Considerations

- **Font Installation:** Ensure that the required fonts are installed and properly recognized by your system. You might need to adjust your system's font configuration or clear font caches after installing them.
- **System Theme**: Your system theme dictates light/dark mode selection, so make sure that is set as you wish.
- **API Keys**: Some features such as AI assistants may require API keys. If this is required, you will have to set it up following the [Zed documentation](https://zed.dev/docs). This repo does not manage those, only the settings that are stored on your local machine.

## Contributing

If you'd like to improve this configuration or have suggestions, feel free to open an issue or submit a pull request!

## License

This project is licensed under the [MIT License](LICENSE).
