# My Tmux Configuration

This is my personal tmux configuration. It's designed to be a good starting point for anyone looking to customize their tmux environment, and it includes a number of features that I find useful in my daily workflow.

## What is Tmux?

Tmux is a terminal multiplexer. It lets you switch easily between several programs in one terminal, detach them (they keep running in the background) and reattach them to a different terminal. And do a lot more.

## Features

This configuration includes a number of features and customizations, including:

*   **Reduced escape time:** for a more responsive feel, especially when using Vim.
*   **Window and pane indexing starts at 1:** instead of the default 0.
*   **Vim-like pane navigation:** Use `Ctrl-h/j/k/l` to navigate between panes, similar to Vim's window navigation.
*   **Vim-Tmux Navigator integration:** Seamlessly navigate between Vim splits and tmux panes.
*   **Easy config reload:** Press `Prefix + r` to reload your tmux configuration.
*   **Intuitive pane splitting:**
    *   `Prefix + \` to split vertically.
    *   `Prefix + -` to split horizontally.
*   **Mouse support:** for scrolling and pane selection.
*   **Increased history limit:** to keep more of your scrollback history.

## Installation

1.  **Install tmux:**
    *   **macOS:** `brew install tmux`
    *   **Linux (Ubuntu/Debian):** `sudo apt-get install tmux`
    *   **Linux (Fedora/CentOS):** `sudo yum install tmux`

2.  **Clone this repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git ~/.tmux
    ```

3.  **Create a symbolic link to the configuration file:**
    ```bash
    ln -s ~/.tmux/tmux.conf ~/.tmux.conf
    ```

4.  **Start tmux:**
    ```bash
    tmux
    ```

## Contributing

Feel free to open an issue or submit a pull request if you have any suggestions or improvements!

## Personal Tips 
* Once you have the amount of panes you want, press C-space to see some pre-defined layouts. 
* I always have a running log of my API in one of my windows for easy access. 

