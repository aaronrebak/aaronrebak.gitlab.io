---
layout: post
title:  "Streaming with Jsoniter (Json Iterator)"
subtitle: "Processing json on the fly"
date:   2019-02-18 23:25:00
categories: [tutorial]
---

It is not unusual to split large datasets into individual messages that can be written/read from a Comms Bus such as Kafka, or Rabbitmq by our applications. This is great most of the time and has many benefits...  

Sometimes this is not possible and our applications end up having to handle large response bodies over http. 

[json-iter]:		https://jsoniter.com/