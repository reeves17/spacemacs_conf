# spacemacs_conf
Ya know... it's my spacemacs config
## set up
1. Install emacs 26 or later, probably like this:  
`sudo add-apt-repository ppa:kelleyk/emacs
sudo apt-get update
sudo apt install emacs26`
1. Clone the Spacemacs develop branch using `git clone -b develop https://github.com/syl20bnr/spacemacs.git ~/.emacs.d`
1. Copy the `.spacemacs` file from this repo as `~/.spacemacs`
1. Do some stuff to enable extentions that are not readily available spacemacs layers
    1. emms  
    `mkdir ~/.emacs.d/private/emms`  
    `cd ~/.emacs.d/private/emms`  
    `git clone https://github.com/K0HAX/spacemacs-emms.git`  
    `mv spacemacs-emms/packages.el .`  
    `rm -rf spacemacs-emms`  
    1. [TODO]
