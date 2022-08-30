# Terraform-theory


### Module: Infrastructure As Code
Competency: is able to learn the HashiCorp Configuration Language (HCL) and all the concepts behind terraform.



### Introduction
Terraform manages external resources (such as public cloud infrastructure, private cloud infrastructure, network appliances, software as a service, and platform as a service) with "providers". HashiCorp maintains an extensive list of official providers, and can also integrate with community-developed providers. Users can interact with Terraform providers by declaring resources or by calling data sources. Rather than using imperative commands to provision resources, Terraform uses declarative configuration to describe the desired final state. Once a user invokes Terraform on a given resource, Terraform will perform CRUD actions on the user's behalf to accomplish the desired state. The infrastructure as code can be written as modules, promoting reusability and maintainability.

Terraform supports a number of cloud infrastructure providers such as Amazon Web Services, Microsoft Azure, IBM Cloud, Serverspace, Google Cloud Platform, DigitalOcean, Oracle Cloud Infrastructure, Yandex.Cloud, VMware vSphere, and OpenStack.

### The mission
Once again your mission will be to learn the basics of the HCL language applied to terraform (it can also be used for Packer). The goal is to learn how to use Terraform to describe what your cloud infrastructure should look like. You will therefore learn how to describe each of the different resources that make up your future (virtual machine configuration, network layer, security layer, etc.). That said, it is important to understand how Terraform manages the creation of all these different resources. , I'm obviously talking about terraform state management. You will then continue by learning the different commands around the Terraform executable and their respective function (init, validate, plan, apply, destroy).

#### Here is a list of concepts you should learn when working with terraform:

- Object Types:

Providers

Resources

Data sources

- Syntax
- Workflow

terraform init

terraform plan

terraform apply

terraform destroy
- Variables

Variable declaration

Variable definition

- Terraform Data Types

Primitives:

1)String

2)Number

3)Boolean
- Collection

1)list

2)set

3)map

4)structural
- Terrafrom Locals
- Terraform output
- Terraform State Data


- Terraform Looping Constructs

1)count

2)for

3)for_each

4)Dynamic block

- Terraform Inbuilt Functions

1)Numeric Functions

2)String Functions

3)Collection Functions

4)Encoding Functions

5)Filesystem Functions

6)Date and Time Functions

7)Hash & Crypto Functions

8)IP Network Functions

9)Type Conversion Functions


#### Resources
- Pluralsight: Getting Strated with Terraform 

- [Terraform documentation](https://www.terraform.io/language)

- [Terraform theory in Russian](https://habr.com/ru/post/537808/)

- [Подводные камни Terraform](https://habr.com/ru/company/piter/blog/496820/)
