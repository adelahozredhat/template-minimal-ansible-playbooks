If need create file requirements.yml

Example:

---
roles:
  - src: git://gitsrv.svb.test.es/iexample.git
    scm: git
    version: "0.0.0"

Or add local roles to add function of playbook. If this role use in general please generate project role