# Kitty Terminal Configuration

This repository contains my personal configuration files for the **Kitty terminal emulator**.

### Files

* `kitty.conf`: The main configuration file.
* `theme.conf`: A separate file containing the color scheme.

---

### Installation

To set up this configuration on your system:

1.  **Locate your Kitty config directory.** On most systems, this is `~/.config/kitty/`. If it doesn't exist, you can create it with the following command:
    ```bash
    mkdir -p ~/.config/kitty/
    ```

2.  **Place the files.** Copy both `kitty.conf` and `theme.conf` into the `~/.config/kitty/` directory.

3.  **Verify the `include` line.** Make sure your `kitty.conf` file contains the following line at the end to properly load the theme:
    ```conf
    include ./theme.conf
    ```

4.  **Restart Kitty.** Quit and reopen Kitty.
