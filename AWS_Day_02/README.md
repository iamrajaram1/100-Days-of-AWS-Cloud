<p align="center">
  <h1 align="center"?<em> 🌍 Day 2 of 100 Days AWS Cloud Challenge- :Unveiling the AWS Global Infrastructure: Powering the Digital World! 💻 </em></h1>
  </p>

## Leveraging AWS Global Infrastructure
Lets Breakdown the AWS global infrastructure to understand in a easiest way.

**AWS Global Infrastructure** — Its a vast network of data centers and services provided by AWS in different locations across the world.

**Data Centers** are commonly known as **regions**, These are spread across various geographic areas such as North America, Asia, Europe, etc.

<img src="https://github.com/iamrajaram1/100-Days-of-AWS-Cloud/blob/main/AWS_Day_02/AWS%20Global%20Infrastructure.jpg" ></br>

**AWS Global Infrastructure**
Now, we will learn more about what are these regions, Availability Regions, and Edge Locations.

## Regions :
>
In AWS there are more than 200+ services and can be launch any service or deploy an application just with few clicks. To launch any service, customer has to choose the region where the service to be launched.

Moreover, Customer prefers launching an service which is very close to the location. Because, When a customer is near to Mumbai Area, the internet connectivity will be easy and Latency will lesser due to shortest distance. In case if customer is launching an service for an application in different region, the latency will be more to access data for customers. The Request and response will take time to serve the users request.

Region Means its a physical location across the globe where we cluster data centers.

> E.g.: Asia Pacific is a geographic location that contains regions like ‘Mumbai’ and ‘Hyderabad’. Each AWS Region consists of a minimum of three Availability Zones, isolated, and physically separate AZs within a geographic area.

<img src="https://github.com/iamrajaram1/100-Days-of-AWS-Cloud/blob/main/AWS_Day_02/Global%20maps.jpg" ></br>

# AWS REGION NAMES AND CODES :
These region names and codes are used to identify easily which is the nearest location to launch the cloud resources.

<img src="https://github.com/iamrajaram1/100-Days-of-AWS-Cloud/blob/main/AWS_Day_02/AWS%20Region%20Names%20and%20Codes.jpg" ></br>

# Region Characteristics :
All the regions are fully independent and isolated. If one Region is impacted , it wouldn't affect the other regions.

<img src="https://github.com/iamrajaram1/100-Days-of-AWS-Cloud/blob/main/AWS_Day_02/AWS%20Region%20Characteristics.jpg" ></br>

* All these regions are isolated and resources has to be manually replicated across each of them.*

**AVAILABILITY ZONES:**
In ASIA PACIFIC — we have two regions (Mumbai & Hyderabad)

**1. Mumbai** and its region code is **“ap-south-1”**, for this region — there are “3 Availability zones” **(ap-south-1A, ap-south-1B, ap-south-1C)**
**2. Hyderabad** and its region code is **“ap-south-2”**, for this region — there are 3 Availability zones **(ap-south-2A,ap-south-2B,ap-south-3C)**

<img src="https://github.com/iamrajaram1/100-Days-of-AWS-Cloud/blob/main/AWS_Day_02/AWS%20Availability%20Zones.jpg" ></br>

Lets, visualize where these Availability zones are located and what does it contains.

As we know, in every **Region : we have minimum 3 Availability zones which are isolated**.

**What do we have in Availability Zones?**
>Region : A Geographical location which has more than two or more Availability zones.

**Availability Zones :** These are the collection of Data Centers within a region. All these AZ are isolated but connected to each other.

<img src="https://github.com/iamrajaram1/100-Days-of-AWS-Cloud/blob/main/AWS_Day_02/AWS%20Asia%20Pacific%20Region.jpg" ></br>

**Why AWS has designed of Availability Zones in region?**
>By Designing this, AWS Provides the High Availability. In case if any of the Data centers gets failed due to Power Supply, Security or Cooling Systems or some intermittent issues. The Other Data centers can still be Available to serve the request. Also, for each Data center to data center a minimum distance of 100KMS is being maintained if any natural disaster occurs.

<img src="https://github.com/iamrajaram1/100-Days-of-AWS-Cloud/blob/main/AWS_Day_02/AWS%20Asia%20Pacific%20AZ.jpg" ></br>

**Edge Location :** End Users will be accessing AWS Services. These edge locations are located for every region to distribute the content to end users to reduce latency by caching the copy of our content using cloud Front (CDN).

<img src="https://github.com/iamrajaram1/100-Days-of-AWS-Cloud/blob/main/AWS_Day_02/AWS%20Asia%20Pacific%20edge%20Locations.jpg" ></br>

## Conclusion :
We have learnt and gained some insights about AWS Global Infrastructure, Regions, Availability Regions, Data Centers and Edge Locations.
