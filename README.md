# Ansible Role: Kodi on Raspbian

Installs Kodi on Raspbian

## Requirements

Raspberry Pi running Raspbian (Kodi runs much better on the Raspberry Pi 2!)

## Role Variables

Set Kodi to launch on startup:
 - auto_start (set to 1 for startup, 0 for manual startup)

## Example Playbook

    ---
    - hosts: raspberrypi
      sudo: yes
      roles:
       - { role:kodi, auto_start: 1 }

Use ```sudo: yes``` if needed

## License

MIT / BSD
