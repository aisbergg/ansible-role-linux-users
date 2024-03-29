# Changelog

All notable changes to this project will be documented in this file.

- [2.1.1 (2022-03-31)](#211-2022-03-31)
- [2.1.0 (2022-01-28)](#210-2022-01-28)
- [2.0.0 (2021-10-11)](#200-2021-10-11)
- [1.1.2 (2020-08-22)](#112-2020-08-22)
- [1.1.1 (2020-05-18)](#111-2020-05-18)
- [1.0.0 (2020-03-21)](#100-2020-03-21)

---

<a name="2.1.1"></a>
## [2.1.1](https://github.com/aisbergg/ansible-role-linux-users/compare/v2.1.0...v2.1.1) (2022-03-31)

### Bug Fixes

- syntax for password option

### CI Configuration

- add branch explicitly to make Ansible import action happy
- bump Ansible Galaxy action version

### Chores

- don't use bump2version to include the CHANGELOG in the bump commit, it doesn't do a good job


<a name="2.1.0"></a>
## [2.1.0](https://github.com/aisbergg/ansible-role-linux-users/compare/v2.0.0...v2.1.0) (2022-01-28)

### CI Configuration

- fix automatic release and publish process

### Chores

- include changelog in bump commits
- update changelog template


<a name="2.0.0"></a>
## [2.0.0](https://github.com/aisbergg/ansible-role-linux-users/compare/v1.1.2...v2.0.0) (2021-10-11)

### CI Configuration

- add Github action for automatic releases

### Chores

- update changelog
- update development configs
- **.ansible-lint:** update linter config
- **.pre-commit-config.yaml:** bump pre-commit hook versions
- **CHANGELOG.tpl.md:** update changelog template
- **README.md:** format readme
- **requirements.yml:** add role requirements

### Code Refactoring

- drop support for Ansible < 2.10


<a name="1.1.2"></a>
## [1.1.2](https://github.com/aisbergg/ansible-role-linux-users/compare/v1.1.1...v1.1.2) (2020-08-22)

### Bug Fixes

- YAPF style name

### Chores

- update changelog
- always sign Git tags


<a name="1.1.1"></a>
## [1.1.1](https://github.com/aisbergg/ansible-role-linux-users/compare/v1.0.0...v1.1.1) (2020-05-18)

### Bug Fixes

- linting problem

### Code Refactoring

- clean up


<a name="1.0.0"></a>
## [1.0.0]() (2020-03-21)

Initial Release
