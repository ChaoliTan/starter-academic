---
title: online shopping mall system
summary: A project to demonstrate microservice using Spring Boot, Spring Cloud, and Docker.
tags:
- Spring Cloud 
- Microservice
- Kubernetes
date: "2020-12-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

<!-- links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/ChaoliTan -->
url_code: "https://github.com/ChaoliTan/gulimall"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

# Guli Mall

It is a practice project, which presents Microservice Architecture using Spring Cloud, Docker. It introduces Nginx to implement dynamic and static sepatation, load balancer, and reverse proxy. Alicloud Nacos is used as service discovery and configuration center. Elasticsearch and Kibana are integrated to accelerate the search service. High concurrency is imporved by using RabbitMQ and final consistency is achieved. Redis is deployed to store cache for the system. Alicloud OSS (Object Storage Service) is used to store data for internal employees. Task scheduler is set up using Cron (Command Run On) when the system is not busy. Current limiting and Fuse Downgrade are implemented via Alicloud Sentinel. Distributed Service Tracing is imported through Spring Cloud Sleuth and Zipkin.

In the cluster part, CI/CD (continuous integration / continuous deployment) is presented through Kubernetes and Jenkins.

The following diagram is the whole architecture of the gulimall system.

![gulimall-MicroserviceArchitecture](gulimall-MicroserviceArchitecture.png)

