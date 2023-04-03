<h1> Terraform </h1>


<H3>Terraform is one of the most popular Infrastructure-as-code (IaC) tool, used by DevOps teams to automate infrastructure tasks. It is used to automate the provisioning of your cloud resources. Terraform is an open-source, cloud-agnostic provisioning tool developed by HashiCorp and written in GO language.</h3>


Benefits of using Terraform: <br/>

1. Does orchestration, not just configuration management<br/>
2. Supports multiple providers such as AWS, Azure, Oracle, GCP, and many more<br/>
3. Provide immutable infrastructure where configuration changes smoothly<br/>
4. Uses easy to understand language, HCL (HashiCorp configuration language)<br/>
5. Easily portable to any other provider<br/>

Every Terraform configuration has at least one module called the root module. The root module is any .tf and/or .tf.json files stored in the main working directory.<br/>

Let’s say you have a Terraform configuration saved in a root module folder named web-app consisting of three files:<br/>

main.tf – used to define providers, remote backend state file.<br/>
variables.tf – used to define input variables used in the configuration.<br/>
terraform.tfvars – used to define values for input variables defined in variables.tf<br/>


![image](https://user-images.githubusercontent.com/43515480/229519333-6ae176a2-537e-4db7-a698-74f0979ffbb0.png)

![image](https://user-images.githubusercontent.com/43515480/229513468-8e9f8cb6-814e-42c9-89f1-b407175ea13e.png)

![image](https://user-images.githubusercontent.com/43515480/229514074-699b55c5-368d-4339-860f-2da0e727d5d9.png)

![image](https://user-images.githubusercontent.com/43515480/229516982-c305f099-0a71-461a-b543-4c73ff23be65.png)
