  
  
  # 

  - hosts:
    - localhost
    vars:
      region: us-east-1
    roles:
    - role: ec2-stop
      server_instance_ids:
        - i-0f07bad58761d2cb0

  # MULTIHOST STOPS IN AWS 

  ---
  - hosts:
    - localhost
    vars:
      region: us-east-1
    roles:
    - role: ec2-stop
      server_instance_ids:
        - i-0f07bad58761d2cb0
        - i-0f07bad58761d2cb0
        - i-0f07bad58761d2cb0
        - i-0f07bad58761d2cb0
        - i-0f07bad58761d2cb0