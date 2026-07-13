---
title: "Performance Benchmarks"
url: "https://docs.chef.io/automate/ha_performance_benchmarks/"
date: "2023-07-10"
feed_url: "https://docs.chef.io/index.xml"
---
Overview While the total number of nodes is an important measure, the data processing speeds of Chef Automate will be primarily determined by the rate of Chef Client Runs each minute (CCR/m). This also includes InSpec if configured to do so. The CCR/m rate can be significantly impacted by adjusting the Chef client’s converge interval (how frequently does Chef run) and the splay (level of randomization so that all Chef clients don’t run at the exact second).
