



https://www.hashicorp.com/blog/infrastructure-as-code-in-a-private-or-public-cloud

https://chocolatey.org/install

https://developer.hashicorp.com/terraform/cli/commands/plan

https://developer.hashicorp.com/terraform/cli/state/resource-addressing

-----------------------------

Terraform: What Is It?
Terraform is an IT automation solution that automates configuration management. Besides being easy to use, it can also help to provision infrastructure across multiple cloud platforms, making it one of the most popular IT automation tools. Through open-source IaC, it allows the control of multiple cloud services through a command-line interface (CLI).

It comes with an out-of-the-box HashiCorp Configuration Language (HCL) support, which provides a declarative language for managing data centers.

The Features And Benefits Of Terraform Include:
As a cross-platform solution, Terraform is compatible with Linux, Windows, Mac OS X, FreeBSD, Solaris, and OpenBSD.
Terraform includes the HCL language as a means to provide concise resource descriptions using expressions, arguments, and blocks.
Can be used to develop new resources or manage existing ones during lifecycle processes.
Automates resource provisioning and reduces human error.
Manages several services and public clouds through a unified workflow.

Infrastructure as Code (IaC):
This means expressing our infra needs in the form of some template.
While creating/realizing the infra, pass the dynamic values.

------------------------------------------------------
    # Terraform:
IaC which runs on any virtual platform
What do we have to do
Define your infrastructure as a template in Terraform
Execute the template to create infrastructure.
In which Language do we need to write these templates?
Hashicorp Configuration Language (HCL)
Here we express what we want in the template which is referred as Desired State
Now when execute terraform will try to create infra to match your Desired State.
Idempotence: This is property which states that executing once or multiple times will have the same result
For infra-provisioning we need a template which helps in meeting desired state and is idempotent.
There are two popular tools
  * Terraform
  * Pulumi
