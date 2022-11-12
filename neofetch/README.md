**CUSTOMIZATION**

If you want to customize neofetch like me, you have to replace your config.conf file with this file inside your "/home/$USER/.config/neofetch/" folder.

**IMPORTANT**

Remember to indicate the path of the image to load in neofetch.

You can indicate that in 2 ways:

1. by going to the neofetch config.conf file at line 711, where it says "image_source: path/to/img" and replacing the "path/to/img" with the actual path to your image
2. by creating an alias in your .bashrc or .zshrc file, appending the line: ***alias neo="neofetch --w3m --source path/to/img"***, where path/to/img is the actual path to your image file

**Reminder 1**

If you are using **kitty** terminal (like me) just replace the "--w3m" option with "*--kitty*", because kitty terminal has a built-in program that renders the image.
For more information visit here: https://github.com/dylanaraps/neofetch/wiki/Images-in-the-terminal and here https://github.com/dylanaraps/neofetch/wiki/Image-Backends

**Reminder 2**

*At line 697* of neofetch *config.conf* file, where it says "**image_backend=**", I write " *"kitty"* " because of the reason mentioned in the first reminder.
So, if you are on another terminal , please refer to the links that I have provided before, otherwise it will not work.

**Information/Suggestion**

I tried to render a custom image both in Gnome-Terminal and Alacritty, but these two terminals did not support the render, so I switched to kitty.
If you find a way to make it work, inform me, please.
