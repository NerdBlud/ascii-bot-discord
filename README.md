# ASCII Discord Bot 🎨🤖

This is a Discord bot that allows users to convert images into ASCII art and create large ASCII text banners. The bot supports multiple customization options for the ASCII conversion, including character sets, grayscale mode, and inversion of colors.

---

## Commands 📜

### `/ascii` 🖼️
**Description:**  
Upload an image, and the bot will convert it into ASCII art.

**Usage:**
1. Upload an image.
2. The bot will offer options to customize the conversion (character set, grayscale, invert).
3. Once configured, the bot will generate the ASCII art and display it in an embed.

**Example:**

/ascii image=<uploaded_image>


### `/bigtext` 🔠
**Description:**  
Transform text into large ASCII art with special spacing.

**Usage:**
1. Enter your text when prompted.
2. The bot will generate a large ASCII art representation of the text.

**Example:**

/bigtext

The bot will prompt you to enter text, which will then be converted to large ASCII art and displayed in an embed or a `.txt` file if it's too large.

### `/font` 🅰️
**Description:**  
Displays the available font styles for use with ASCII text.

**Usage:**
1. Type `/font` to see the list of available font styles for use in ASCII text generation.

**Example:**

/font

The bot will return a list of font styles like `bold`, `italic`, and `monospace`.

---

## Features ✨

- **Convert images to ASCII art**: Supports different character sets like Standard, Detailed, Block, and Minimal. 🖼️➡️🔲
- **Big Text**: Generate large ASCII art representations of text with customizable fonts. 🔠🎨
- **Font Styles**: Supports multiple fonts like `bold`, `italic`, and `monospace`. 🖋️
- **Grayscale & Inversion**: Customize the output with grayscale and invert options. ⚫⚪
- **File Download**: If the ASCII art is too large for an embed, the bot will offer the ASCII art as a downloadable `.txt` file. 📥

---

## Setup 🔧

1. Clone the repository:

git clone <repository_url>
cd <repository_folder>


2. Install dependencies:

pip install -r requirements.txt


3. Update your bot's token:
In the `main.py` file, replace `YOUR_BOT_TOKEN_HERE` with your bot's token.

4. Run the bot:

python main.py


---

## Dependencies 📦

- **discord.py**: The main library for interacting with Discord's API. 🔌
- **Pillow**: A Python Imaging Library (PIL) fork used to handle images. 🖼️📸
- **pyfiglet**: For generating large ASCII text from input. 📝

---

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. ⚖️