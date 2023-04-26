# Starships
Sets up the starship environment with my desired configuration

More information on [starship.rs](https://starship.rs)

## Requirements
- curl should already be installed.

## Dependencies
None

## Example Playbook

    - hosts: localhost
      tasks:
        - name: Starship
          ansible.builtin.include_role:
            name: bartdorlandt.starship

## License

MIT/BSD

## Author Information

This role was created in 2023 by Bart Dorlandt.
