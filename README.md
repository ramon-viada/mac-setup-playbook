This playbook installs and configures most of the software I use on my Mac. Manual Task are documented here as well.

## Installation

1. Ensure Apple's command line tools are installed
   - launch installer: `xcode-select --install`
1. Install [Homebrew](https://brew.sh/)
2. Install python
    - `$ homebrew install python@3.12`
    - `$ pip3 install --upgrade pip`
3. Create python virutal environment
    - `$ mkdir $HOME/.venv`
    - `$ python3 -m venv $HOME/.venv/ansible`
4. Activate python venv
    - `$ source $HOME/.venv/ansible/bin/activate`
5. Install ansible-core
    - `(ansible) $ pip3 install ansible-core`
6. Clone Repo && Install Collections and Roles
7. Exit python venv
    - `(ansible) $ deactivate`

## Manual Tasks
