# ShellConfig.my 

This repository contains configuration for a custom shell environment setup, specifically, `.pk10.zsh` file, which enhances your shell environment by leveraging the [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) framework and [Powerlevel10k](https://github.com/romkatv/powerlevel10k) theme. This custom shell setup provides a more interactive and visually appealing terminal experience.

## Prerequisites

1. [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)
2. [Powerlevel10k](https://github.com/romkatv/powerlevel10k)

## Installation

1. First, make sure you have the required prerequisites installed. If you haven't already installed Oh My Zsh and Powerlevel10k, please follow their respective installation guides linked in the Prerequisites section.

2. Open your `.zshrc` file located in your home directory with your preferred text editor, for example:

   ```sh
   nano ~/.zshrc
   ```

3. In the `.zshrc` file, set the theme to Powerlevel10k by adding or updating the following line:

   ```sh
   ZSH_THEME="powerlevel10k/powerlevel10k"
   ```

4. Save the changes and exit the text editor.

5. Next, clone this repository to your local machine. 

   ```sh
   git clone https://github.com/username/ShellConfig.my.git
   ```

   **Note:** Replace "username" with your actual GitHub username.

6. Copy the `.pk10.zsh` file to your home directory:

   ```sh
   cp ShellConfig.my/.pk10.zsh ~/
   ```

## Usage

After setting up as described above, you'll start experiencing an improved shell environment on your next terminal session.

Remember, you can customize the `.pk10.zsh` file to further meet your needs. Enjoy your more productive, visually pleasing terminal experience!

## Support

If you encounter any problems or have any suggestions, please open an issue on this repository.

## License

This project is released under the MIT License. See `LICENSE` file for more details.
