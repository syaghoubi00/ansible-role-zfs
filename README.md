# ZFS

An Ansible role to install [OpenZFS](https://openzfs.org/wiki/Main_Page) ([GitHub](https://github.com/openzfs/zfs))

## Requirements

None.

## Role Variables

`zfs_kabi:` - Use kABI instead of DKMS

## Dependencies

`syaghoubi00.epel` - To install EPEL

## Example Playbook

```yaml
- hosts: zfs
  roles:
    - syaghoubi00.zfs
```

## License

GPL-3.0-or-later

## Author Information

Created by Sebastian Yaghoubi
