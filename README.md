<p align="center"><a href="https://www.flaticon.com/free-icons/chameleon" title="chameleon icons"><img src=".github/chameleon.png" height="90" alt="Project Logo"></a></p>
<h2 align="center">ChameleonInstance</h3>

The ChameleonInstance is an instance you can deploy in an AWS account to do some testing within the account and VPC.

Logging in on the instance can be done via SSM via the browser. The instance has an instanceprofile with the following managed policies:
- `AmazonSSMManagedInstanceCore`
- `AmazonEC2RoleforSSM`

The instance needs a public ip address or have a VPC endpoint available.


The ChameleonInstance is a temporary instance which is not meant for running any production systems on it, the instance is not hardened!
