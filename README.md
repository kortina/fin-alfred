Send an email to Fin from your Desktop, using [Alfred](https://www.alfredapp.com/).

![screenshot](https://raw.githubusercontent.com/kortina/fin-alfred/master/screenshot.png)

## Setup

Download and double-click the Alfred Workflow to install.

You must configure a few environment variables to use Fin Alfred.
You can either edit the Alfred Script itself,
or define these in your `~/.bash_profile`, 
which the Alfred script will source.


    export FIN_FROM_EMAIL="your from email, eg you@gmail.com"
    export FIN_TO_EMAIL="your Fin email, eg you@fin.com" # ask Fin for this if you don't know it
    export FIN_ALFRED_LOG=" file to log notes sent (set this to /dev/null to skip logging)"


See also [ses-emailer-cli](https://github.com/kortina/ses-emailer-cli) for a
similar script with more robust email support using Amazon SES.
