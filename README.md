 ___                   _____           ____
 / _ \ _ __   ___ _ __ |  ___|_ _  __ _/ ___|
| | | | '_ \ / _ \ '_ \| |_ / _` |/ _` \___ \
| |_| | |_) |  __/ | | |  _| (_| | (_| |___) |
 \___/| .__/ \___|_| |_|_|  \__,_|\__,_|____/
      |_|


Manage your OpenFaaS functions from the command line

Usage:
  faas-cli [flags]
  faas-cli [command]

Available Commands:
  build          Builds OpenFaaS function containers
  cloud          OpenFaaS Cloud commands
  deploy         Deploy OpenFaaS functions
  help           Help about any command
  invoke         Invoke an OpenFaaS function
  list           List OpenFaaS functions
  login          Log in to OpenFaaS gateway
  logout         Log out from OpenFaaS gateway
  new            Create a new template in the current folder with the name given as name
  push           Push OpenFaaS functions to remote registry (Docker Hub)
  remove         Remove deployed OpenFaaS functions
  store          OpenFaaS store commands
  template       Downloads templates from the specified github repo
  version        Display the clients version information

Flags:
      --filter string   Wildcard to match with function names in YAML file
  -h, --help            help for faas-cli
      --regex string    Regex to match with function names in YAML file
  -f, --yaml string     Path to YAML file describing function(s)

Use "faas-cli [command] --help" for more information about a command.