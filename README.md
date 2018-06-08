[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-phtools.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-phtools)

# Ansible Role: marvel-nccr.phtools

An ansible role that installs [tools](https://github.com/pdlotko/topological_pipelines_for_porous_materials) for analyzing the persistence homology of nanoporous materials.

## Installation

`ansible-galaxy install marvel-nccr.phtools`

## Role Variables

See `defaults/main.yml`

## Example Playbook

  - hosts: servers
    roles:
    - role: marvel-nccr.phtools

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
