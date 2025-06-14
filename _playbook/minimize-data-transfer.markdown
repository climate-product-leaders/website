---
layout: best-practice
title: "Minimize data transfer"
order: 550
icon: /assets/climate-icons/Icon-Transfert.svg
number: "30"

description: "Reduce data transfer and storage to lower emissions, improve performance, and cut cloud costs with smart formats, caching, and cleanup."

section: Design Frugally
chapter-tag: design-frugally

previous-page: optimize-multimedia-files
next-page: case-study-leboncoin-traffic-reduction


matter: |
  You have probably heard the mantra Data is The New Oil. Collecting or keeping more data than necessary is bad for the environment as it is energy-intensive and results in carbon emissions during the data transmission and storage in data centers. A piece of data travels on average 15,000 km (or 9320 miles). Estimates vary, but some suggest that as much as 80-90% of the data generated by businesses is considered dark data (single-use digital data). Those can make your business operations and products bigger, slower and more costly.

do: |
  - Use a "minimum by default" approach when specifications are absent
  
  - Avoid polling API routinely and consider using REST hooks
  
  - Use lightweight data formats like JSON and use data compression techniques to reduce file sizes
  
  - Choose data centers that are located near your users. The shorter the distance data has to travel, the less energy is consumed.
  
  - Use Content delivery networks (CDN’s) to serve assets such as image files from a network of data centres around the world.
  
  - [Implement caching, batching**, and** offline features](implement-caching-batching-and-offline-features)
  
  - Reduce the package size of your mobile apps updates
  
  - Minimize redundant data and how often you update data. Aim for more user-triggered data refresh.
  
  - Avoid an excessive DOM size and multiple-page redirects
  
  - Maximize data processing and computing operations in the back end and minimize front-end processing
  
  - Connect to a database only when necessary
  
  - Store static data locally
  
  - [Delete **old user accounts and old data**](delete-old-user-accounts-and-old-data)

success: |
  - 🧑💰Efficient utilization of data centers and servers for greener operations
  
  - 🧑Streamlined product performance, exemplified by faster load times
  
  - 🧑💰Enhanced user experience leading to improved conversion rates and overall satisfaction
  
  - 💰Optimization leading to reduced cloud expenditure
  
  - **💰Rigorous data security measures ensuring compliance and protecting user trust**

consider: |
  We recommend you monitor server resource utilization, such as CPU and memory usage, to ensure you effectively conserve resources. If your product relies on third-party hosting services, assess the hosting provider's sustainability metrics, such as their energy sources and carbon neutrality commitments. See more in [Choose a sustainable hosting provider](choose-a-sustainable-hosting-provider).
---