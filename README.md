.
├── README
├── README.md
├── group_vars
│   └── all
├── hosts
├── roles
│   ├── common
│   │   ├── default
│   │   │   └── main.yml
│   │   ├── handlers
│   │   │   └── main.yml
│   │   ├── tasks
│   │   │   ├── install_docker.yml
│   │   │   ├── install_docker_compose.yml
│   │   │   ├── install_util.yml
│   │   │   ├── install_zsh.yml
│   │   │   ├── install_zsh_autosuggest.yml
│   │   │   └── main.yml
│   │   └── templates
│   │       └── zshrc.j2
│   └── jenkins
│       ├── README.md
│       ├── defaults
│       │   └── main.yml
│       ├── files
│       ├── handlers
│       │   └── main.yml
│       ├── meta
│       │   └── main.yml
│       ├── tasks
│       │   └── main.yml
│       ├── templates
│       ├── tests
│       │   ├── inventory
│       │   └── test.yml
│       └── vars
│           └── main.yml
├── site.jenkins.yml
└── site.yml

16 directories, 23 files
