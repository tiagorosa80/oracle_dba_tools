# Using ansible to install some Oracle DBA tools in linux

Some tools to use on linux for Oracle DBAs.

## What tools will be installed?

```python
iotop
tmux
wget
curl
EPEL package repo
rlwrap
htop
```

## Usage

```python
ansible-playbook -i hosts tools_playbook.yml

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
