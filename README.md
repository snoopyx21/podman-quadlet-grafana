# Use Podman Quadlet with grafana

Deploy grafana with Podman Quadlet


## Usage

To start Grafana on your device :
```bash
ansiible-playbook grafana.yaml --tags deploy
```
To stop this installation of Grafana on your device :
```bash
ansible-playbook grafana.yaml --tags cleanup
```

## License

[GPL](https://opensource.org/license/GPL-2.0)
