TO GET STARTED
==============

Please do this before the workshop starts, 
like when I'm saying something boring or incomprehensible.

Please visit the [wiki](https://github.com/eteeselink/dwsfh/wiki/Participants) and add your GitHub username there.

Now, clone this code. Then, from the repository root directory:

    npm install

All dependencies and fancy developer tooling will now be installed. 
You will need to redo this every time someone adds a dependency. 

Now, start the local auto-refreshing auto-filewatching webserver with:

    ./js-watch.sh

or

    js-watch.cmd

Now open <http://localhost:54321> and there you go!

Troubleshooting:
* You might need to `sudo` that, not sure.
* If you're on Windows and it doesn't work, your Git directory might not be on the system PATH. The `.cmd` just calls the `.sh` so you have to have sh (which comes with Git)
* Try fiddling with firewalls if the server starts but you can't reach it. I'm sure the internet is very trustworthy today.
