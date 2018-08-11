How to RUN the Ansible Playbook

EXAMPLE:

ansible-playbook -e "bucket=apss1-web-test1 region=us-east-2 vpc_id=vpc-b99ad2d1 sg_name=pradeepsg" playbooks/ec2/ec2.yml
