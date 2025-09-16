# epkg
The package manager for EmperorOS.

## Installation
1. Clone the repository:
`git clone https://github.com/emperoros/epkg`
2. Move the binary:
`sudo mv ./epkg /usr/bin/epkg`
3. Set up repository:
`sudo git clone https://github.com/emperoros/epkg-repo /opt/epkg-repo`

## Usage
```
COMMANDS:
  add      Add a package
  kill     Kill a package
  update   Update repositories & packages
  list     Display installed packages
  version  Display the version of $(basename "$0")
  help     Display this message

ARGUMENTS:
  -y --yes     Don't ask [Y/n]
  -l --local   Add a local package (don't use the repository)
```