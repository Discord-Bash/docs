All files and directories are created on every login to the system (mention the bot).

=== "/bin"

    - `/bin` is a place where all system commands are kept.

=== "/home"

    - `/home` contains user account directories
    - `/home/{user.id}` is a user folder

=== "/home/{user.id}/local"

    - `/home/{user.id}/local` is where your autorun/script folders are stored
    - `/home/{user.id}/local/autorun` is where you place shell scripts to be autoran every login
    - `/home/{user.id}/local/bin` is where you place shell scripts to be accessed globally withn your account

=== "/packages"

    - `/packages` is where all command packages are kept
    - `/packages/{package}`  contains all the package files
    - `/packages/{package}/commands`  contains all the package commands

!!! note
    You cannot go to the top of filesystem because of security, so to add a new command you must connect to machine where you run the bot and add it from there, then restart the bot.