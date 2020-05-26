# psiturk-harp-template

Template for creating a new PsiTurk experiment for data collection

To use, please:
* Clone this directory to a repository on eve.pr
* `cd` to within this directory
* Type the command `psiturk`
* Once within the psiturk terminal, type `server on`. You should see the server status successfully update
* The public view of your website can be seen [here](http://dashboard.personalrobotics.ri.cmu.edu/)

To check if another PsiTurk project is already running there, use `ps aux | grep psiturk`.
`pkill gunicorn` kills all servers of this kind on the machine, which can be verified with the previous command.

Please remember to use relative paths only when accessing resources, otherwise when mirroring your local site, the server will get confused and be unable to find your content.
