# AWS-CLOUD
EC2 inline policy
inline policy is just assigned to one user or group
view info about ec2 and ability to start and stop instances
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Action": [
        "ec2:Describe*",
        "ec2:StartInstances",
        "ec2:StopInstances"
      ],
      "Resource": [
        "*"
      ],
      "Effect": "Allow"
    }
  ]
}
