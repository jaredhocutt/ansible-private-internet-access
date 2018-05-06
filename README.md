# Private Internet Access VPN

Installs Private Internet Access VPN profiles in NetworkManager.

## Requirements

None

## Role Variables

| Variable       | Required           | Default | Description                          |
| -------------- | ------------------ | ------- | ------------------------------------ |
| `pia_username` | :heavy_check_mark: | `''`    | The Private Internet Access username |

## Dependencies

None

## Example Playbook

```yaml
- hosts: localhost
  vars:
    pia_username: p1234566789
  roles:
      - jaredhocutt.private-internet-access
```
