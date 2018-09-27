# kong_cf

CompleteKong.yml contains the yaml file that builds an RDS instance in an existing vpc with the RDS instance and Kong instance in the private subnet and then builds the loadbalancer in the public subnet.

VPC.yml builds the VPC with two public and two private subnets and a default SG.

RDS.yml is the stripped out RDS creation from the CompleteKong.yml

kong-infra.yml has the created of everything but the auto-scaling groups which create the kong instance.

