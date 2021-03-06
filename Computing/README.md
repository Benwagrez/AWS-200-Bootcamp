<!-- PROJECT LOGO -->
<br />
<div align="left">
  <a href="https://github.com/Benwagrez/AWS-200-Bootcamp/">
    <img src="../Setup/images/wmlogo.png" alt="Logo" width="540" height="100">
  </a>
</div>
<h1> AWS 200 Networking Lab </h1>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#lab-overview">Lab Overview</a>
      <ul>
        <li><a href="#business-case">Business Case</a></li>
        <li><a href="#object-creation-overview">Object Creation Overview</a></li>
        <li><a href="#guide">Guide</a>
        <ul>
          <li><a href="#terraform-object-creation">Terraform Object Creation</a></li>
          <li><a href="#aws-console-overview">AWS Console Overview</a></li>
        </ul>
        </li>
      </ul>
    </li>
  </ol>
</details>

## Lab Overview

Welcome to the Networking lab. 

### Business Case
West Monroe needs to spin up three Virtual Private Clouds (VPCs) for increased isolation and regulatory concerns. Two of those VPCs will need a VPC peering connection between them, allowing duplex traffic flow. In addition, they would like a Transit Gateway (TGW) to serve as a central hub for the VPCs.

### Object Creation Overview

In this lab we will create the following:
* 3 x VPC objects
* 1 x VPC peering connection
* 1 x AWS Transit Gateway object
* 3 x AWS Transit Gateway connections
* AWS Subnets, routing tables, and routes

A diagram is included below for convenience:
<div align="center">
<img src="../Setup/images/NetLabDiagram.jpg" alt="Logo" width="600" height="400">
</div>

### Guide

Follow this guide to complete the networking lab portion of the AWS-200-bootcamp, the guide will focus on how to create the objects through Terraform, then it will overview how to review the objects created in the console and provide a high-level explanation on how to replicate this lab through console.

#### Terraform Object Creation

<ol>
  <li>
    First, we will provide example Terraform code for: VPC object, AWS Subnets, routing tables, and routes.
    <ol type="a">
      <li>
        VPC Object
        <ol type ="i">
          <li>
            things
          </li>
        </ol>
      </li>
      <li>
        AWS Subnet
        <ol type ="i">
          <li>
            things
          </li>
        </ol>
      </li>
    </ol>
  </li>
  <li>
    Let's look at the objects you will have to create on your own.
    <ol type="a">
      <li>
        things
        <ol type ="i">
          <li>
            things
          </li>
        </ol>
      </li>
      <li>
        things
        <ol type ="i">
          <li>
            things
          </li>
        </ol>
      </li>
    </ol>
  </li>
</ol>

#### AWS Console Overview

stuff
<!-- make sure your console view is on the correct region as well

Initialise the configuration
terraform init -input=false
terraform fmt
terraform validate
Plan and deploy
terraform plan -input=false -var=hostname=geekbench -var=plan=5USD -out=tfplan
terraform apply tfplan

Terraform will run the above script to benchmark the server
Find your results in the Terraform output

 Once finished, destroy the server
terraform plan -destroy -out=tfdestroy
terraform apply tfdestroy

talk about IPAM addressing for VPCs
talk about availability zones/regions

Set variable values in tfvars -->