# Repository
My own repository instructions

### Adding the repository to /etc/pacman.conf
Follow this structure

[name of the repository]
SigLevel = Optional TrustedOnly (this is the default)
Server = https://cookiesource.github.io/$repo/$arch

$arch stands for x86_x64
$repo stands for 
Server is the link of github pages /name and then adding $repo/$arch

### Signatures



### add new packages
use repo-add where repository is the name of the database and then the package you want to add to the database
repo-add repository *.pkg.tar.xz 