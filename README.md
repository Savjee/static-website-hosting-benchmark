# Cloud storage performance test results

Raw results of a benchmark I ran to indentify which cloud provider is the fastest to host a static website.

This repository contains the raw data that was exported from both services. Feel free to use it to do your own analysis!

The experiment was conducted in 2017 and 2020. Results & analysis can be found on my blog:
* 2017: [https://savjee.be/2017/10/Static-website-hosting-who-is-fastest/](https://savjee.be/2017/10/Static-website-hosting-who-is-fastest/)
* 2020: [https://savjee.be/2020/05/benchmarking-static-website-hosting-providers/](https://savjee.be/2020/05/benchmarking-static-website-hosting-providers/)

## Tested services
These services were tested for performance:

* Amazon S3
* Amazon CloudFront (with S3 bucket as origin)
* Google Cloud Regional bucket
* Google Cloud Multiregion bucket
* GitHub Pages
* Netlify
* Firebase hosting
* Cloudflare Workers Sites
* Cloudflare CDN

## Test setup
* I used [Pingdom](https://www.pingdom.com) and [Oh Dear](https://ohdear.app) to check response times of each service every minute.
* [Oh Dear](https://ohdear.app) also kept track of download speeds, time to first byte, TLS handshake timings, ...
