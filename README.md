# Automated Workstation Setup & Management
![Automate All The Things!](https://github.com/drafael/osx-bootstrap/raw/master/aatt.jpeg)

1. Install command line tools `xcode-select --install`
2. Install [Homebrew](http://brew.sh)
3. Install [Ansible](https://www.ansible.com/)
`brew install ansible`
4. Check Mode (“Dry Run”)
`ansible-playbook site.yml --check`
5. Automated workstation setup
`ansible-playbook site.yml`

*See also*:
  - [Mac Development Ansible Playbook](https://github.com/geerlingguy/mac-dev-playbook)