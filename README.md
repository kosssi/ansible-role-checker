# ansible-role-checker

[![Build Status](https://travis-ci.org/kosssi/ansible-role-checker.svg?branch=master)](https://travis-ci.org/kosssi/ansible-role-checker)

This role allows you to check the versions of roles locally installed.

## Role Defaults Variables

    check_roles: false

## Example

    check_roles:
      - { name: kosssi.apt, md5: a0cf9a33823e83fd19412a90df4f2412 }

## Tests

For local test:

    ansible-playbook -i tests/inventory tests/local_playbook.yml

## License

Licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
