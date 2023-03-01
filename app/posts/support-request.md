---
layout: collection
title: Support query
description: A support request service where schools can request help for the things they're buying
pagination:
  data: collections.support-request
  reverse: true
  size: 50
permalink: "support-request/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
---