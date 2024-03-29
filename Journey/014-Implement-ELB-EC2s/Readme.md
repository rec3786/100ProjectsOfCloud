<br />

<p align="center">
    <a href="img/">
        <img src="Implement_ELB_EC2s.png">
    </a>
    <h3 align="center">100 Projects in Cloud</h3>
<p align="center">
    Implement Elastic Load Balancing Between EC2 Instances
        <br />
        Lab 14
        <br/>
    </p>
</p>

<details open="open">
  <summary><h2 style="display: inline-block">Lab Details</h2></summary>
  <ol>
    <li><a href="#services-covered">Services covered</a></li>
    <li><a href="#lab-description">Lab description</a></li>
    <li><a href="#learning-objectives">Lab objectives</a></li>
    <li><a href="#lab-date">Lab date</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>    
    <li><a href="#lab-steps">Lab steps</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

## Services Covered

<img src="EC2.png"> Elastic Cloud Computing
<br> <img src="ELB.png"> Elastic Load Balancer <br/>

## Lab Description

In this challenge, Elastic Load Balancing for two Amazon Elastic Compute Cloud (Amazon EC2) instances were configured. First, two EC2 instances as web servers were configured. Next, I created a targeoup that included the EC2 instances. Finally, I created a load balancer for the EC2 instances.

## Learning Objectives

⭐ Create Elastic Compute Clouds
⭐ Implement an Elastic Load Balancer to switch between the two EC2s

## Lab date
   2024.01.23

## Prerequisites
*AWS Account or *DigitalCloud Training Challenge Lab subscription

## Lab Steps

    1. Create (2) EC2 instances that are running in the same AWS region. 
<p align="center">
    <a href="img/">
        <img src="2-EC2_Created.png">
    </a>
</p>
    2. Create an Elastic Load Balancer.
<p align="center">
    <a href="img/">
        <img src="LoadBalancerCreated.png">
    </a>
</p>
    3. Configure the routing by creating a "Target Group". 
<p align="center">
    <a href="img/">
        <img src="Registered_Targets.png">
    </a>
</p>
    4. Test the EC2s with the ELB implemented. The Elastic Load Balancer is now set up with (2) EC2 instances,and can now distribute incoming traffic evenly between them.
<p align="center">
    <a href="img/">
        <img src="EC2_1.png">
    </a>
</p>
<p align="center">
    <a href="img/">
        <img src="EC2_2.png">
    </a>
</p>

## Acknowlegements

⭐ [Digital Cloud Challenge Labs](https://digitalcloud.training/hands-on-challenge-labs/)
