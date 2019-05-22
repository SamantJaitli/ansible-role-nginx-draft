# ansible-role-nginx-draft
Simple Ansible role to install nginx web server with configurable home page.

This role could use some serious improvements.

1. Use [`ansible-lint`](https://github.com/ansible/ansible-lint) to enforce best practices.
1. Use [`yamllint`](https://github.com/adrienverge/yamllint) to enforce consistency.
1. Use [Travis CI](https://travis-ci.org/) to continuously test development.
1. Read about [Ansible testing strategies](https://docs.ansible.com/ansible/latest/reference_appendices/test_strategies.html), and write integration tests which verify that:
    * services are listening on the expected ports
    * requests to the services return expected results
