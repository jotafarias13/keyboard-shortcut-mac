# Setting Up Keyboard Shortcut to Open Mac Apps

# Overview

This tutorial is based on wikiHow [How to Set a Keyboard Shortcut to Open Mac Apps](https://www.wikihow.com/Set-a-Keyboard-Shortcut-to-Open-Mac-Apps).

# Setup Automator Service

Open Automator.app, click File, New, Quick Action.

# Add the Launch Application Action to an App

In `Workflow receives` select `no input`. Then, on the Actions tab search for `Launch Application` and drag to the right side. Select the Application you want to launch. In my case, I created one service for Emacs and another for iTerm. Each one needs a separate Automator Quick Action. Next, save the Quick Action and choose a name. In my case, I chose `Open Emacs` for the first one and `Open iTerm` for the second one.

# Creating the shortcut

Open System Preferences, go to Keyboard and Keyboard Shortcuts. Go to the Services panel and open the General dropdown. There you should find the Automator Services you created. On the far right of the desired service, there's a field for adding the shortcut. For me, I set `F4` for `Open Emacs` and `F5` for `Open iTerm`. Finally, click Done, close everything and you're good to go.
