<div align="center">
    <img src="https://www.mvpskill.com/wp-content/uploads/2021/06/PowerApps-Logo-SG-1110x590-1.png" alt="Logo" width="150" height="80">
     <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRObhoMc2Qp8825dSDlSjeraTW1p5H3sCuCkQ&usqp=CAU" alt="Logo" width="150" height="80">

  <h3 align="center">Best-README</h3>

</div>

[![Status](https://img.shields.io/badge/status-successed-success.svg)]()

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#PI Web API Best Practices">PI Web API Best Practices</a></li>
        <li><a href="#Test web API">Test Web API</a></li>
        <li><a href="#Create Connector">Create Connector</a></li>
        <li><a href="#Create App Demo">Create App Demo</a></li>
      </ul>
    </li>
    <li><a href="#Experiment App">Experiment App</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

<p align= "left">This project aim to connect power apps application that is hosted in the cloud but PI system is located somewhere on permises your pi Web API instance is behind sort of DMZ so in order for powerapps to be able to retrieve your pi system data need some communication via something called the <b>on-premises data gatway.</b> </p>
<p align="center">
 <img  width=400px height=250px src="https://raw.githubusercontent.com/watthanai/PowerApp-PIWebAPI/master/Architecture.png"><br></p>

### Prerequisites

In this case I assumed you installed configure PI API successfully you should be able to access pi web API using the URL and use any web brower

<ul>
<li><a href="https://docs.microsoft.com/en-us/data-integration/gateway/service-gateway-install">Install an on-premises data gateway</a></li>
<li><a href="https://www.postman.com/downloads/">Install Postman</a></li>
</ul>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

This instances will be splitting the demo of buildding in ther application of 2 parts

<ul>
<li>Search Screen Payload</li>
<li>Post Payload</li>
</ul>

First of all I'm going to explan how do i actually retrieve information to be a PI Web API <a href="#PI Web API Best Practices">Pi Web API Best Practices</a>
