# Create a Custom VM Image for Google Compute Engine

## Overview

The code here serves to illustrate the article [Use HashiCorp's Packer to create a Custom VM Image for Cloud Provider](https://andyboyle.io/2017/03/02/use-hashicorps-packer-to-create-a-custom-vm-image-for-cloud-provider/)

The article is a simple step-by-step process to build a Google Custom VM with Apache Kafka preinstalled and configured with a couple of topics already created.

If you follow through the code examples on the page you should arrive at the same files etc.

In fact the difference in code between this one and the [previous blog](https://andyboyle.io/2017/02/23/create-a-vm-image-with-apache-kafka-configured-using-vagrant-and-ansible/) is one file - _kafka-instance-template.json_ - which has around 25 lines. Not much.

You will have to install [Packer](https://www.packer.io/) for this to work.

