---
title: "Inside terraform-provider-archive: A Memory Pattern From 2016 That Scales With Your Lambdas"
url: "https://feeds.dzone.com/link/23561/17435593/inside-terraform-provider-archive"
date: "2026-08-31"
author: "Oleg Mamiev"
feed_url: "https://feeds.dzone.com/cloud-architecture"
---
A CI Runner That Shouldn't Have Died If you deploy AWS Lambdas through Terraform, you almost certainly use archive_file . With enough lambdas, a single terraform apply can kill the CI runner with OOM. The trickiest part is that you will not see any errors in Terraform output and have no clue what just happened.
