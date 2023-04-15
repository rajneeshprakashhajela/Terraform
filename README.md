<h1> Terraform </h1>

<img width="740" alt="image" src="https://user-images.githubusercontent.com/43515480/229695559-50f363d7-1195-41c8-8893-e24a9ef9c654.png">

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


•	2. Providers – AWS, Azure
•	3. Resources
•	4. Data Sources and Outputs
•	5. Variables and Locals
•	6. Provisioners and Null Resources
•	7. Count, For_Each, Ternary Operators
•	8. Terraform CLI Commands
•	9. Terraform functions
•	10. Working with files
•	11. Terraform state
•	12. Depends_On and LifeCycle Block
•	13. Dynamic Blocks
•	14. Modules
•	15. Best Practices for Modules — 1
•	16. Best Practices for Modules — 2

![image](https://user-images.githubusercontent.com/43515480/229519333-6ae176a2-537e-4db7-a698-74f0979ffbb0.png)

![image](https://user-images.githubusercontent.com/43515480/229513468-8e9f8cb6-814e-42c9-89f1-b407175ea13e.png)

![image](https://user-images.githubusercontent.com/43515480/229514074-699b55c5-368d-4339-860f-2da0e727d5d9.png)

![image](https://user-images.githubusercontent.com/43515480/229516982-c305f099-0a71-461a-b543-4c73ff23be65.png)


1-Click WebServer Provisioning on AWS using Terraform,Ansible,Docker
![image](https://user-images.githubusercontent.com/43515480/229520608-78a56104-9feb-4d89-987e-d6fac3befe47.png)

<img width="765" alt="image" src="https://user-images.githubusercontent.com/43515480/229696622-c2c2f765-79b4-40a1-b200-0cd2dded8e61.png">
<img width="748" alt="image" src="https://user-images.githubusercontent.com/43515480/229696777-9162db92-dd9a-4e10-adb2-156e00707ca6.png">

<img width="770" alt="image" src="https://user-images.githubusercontent.com/43515480/229697329-7cf159d5-a5b9-4c74-97dd-6b41f6b3b0ac.png">

for Windows machine
Hashicorp terramform 
VSCode

and for connect via azure cli use below command in screenshot

![image](https://user-images.githubusercontent.com/43515480/232256481-893b8a0e-3943-4900-a1e1-aea7c59162c2.png)
