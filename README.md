# Role Name

The role is designed to allow one to turn off interfaces with public IP addresses. This is useful in the cases where a server has one public and one private interface (such as DigitalOcean) and you don't want public interface to be exposed to the Internet.

The role has been tested to work with Ubuntu and CentOS. Although, it may work with other compatible flavors as well.

## Requirements

None

## Role Variables

None

## Dependencies

None

## Example Playbook

Sample usage:

    - hosts: servers
      roles:
         - { role: private-only-ip-nix }

## License

MIT

## Author Information

Rahil Parikh
