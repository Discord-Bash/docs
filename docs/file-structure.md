All files and directories are created on every login to the system (mention the bot).

=== "/bin"

    - `/bin` contains all system commands.

=== "/home"

    - `/home` contains user account directories
    - `/home/{user.id}` contains the user files

=== "/home/{user.id}/local"

    - `/home/{user.id}/local` contains the user's autorun/script folders
    - `/home/{user.id}/local/autorun` contains the user's shell scripts to be autoran every login
    - `/home/{user.id}/local/bin` contains the user's shell scripts which can be accessed globally within their account

=== "/packages"

    - `/packages` contains all installed packages
    - `/packages/{package}`  contains all the package files
    - `/packages/{package}/commands`  contains all the package commands

!!! note
    You cannot go to the top of filesystem because of security, so to add a new command you must connect to machine where you run the bot and add it from there, then restart the bot.