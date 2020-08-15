Single server Stop use ansible

- hosts:
  - localhost
  vars:
    region: us-east-1
  roles:
  - role: ec2-stop
    server_instance_ids:
      - i-0f07bad58761d2cb0

MultiServer Stop use Ansible

---
- hosts:
  - localhost
  vars:
    region: us-east-1
  roles:
  - role: ec2-stop
    server_instance_ids:
      - i-0f07bad58761d2cb0
      - i-0f07bad58761d2cb1
      - i-0f07bad58761d2cb2
      - i-0f07bad58761d2cb3
      - i-0f07bad58761d2cb4