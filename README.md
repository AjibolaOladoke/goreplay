# goreplay

## What This Is

This is part of the Swift Tech Co. working stack for product and engineering. It gathers the goreplay notes, examples and fixes that keep delivery fast, and doubles as the reference map we hand to whoever picks up this thread next.

## Images

[![goreplay](images/preview.png)](https://github.com/Swift-Tech-Co)

## https://www.swifttechco.com

GoReplay is an open-source network monitoring tool which can record your live traffic and use it for shadowing, load testing, monitoring and detailed analysis.

## About

As your application grows, the effort required to test it also grows exponentially. GoReplay offers you the simple idea of reusing your existing traffic for testing, which makes it incredibly powerful. Our state of art technique allows you to analyze and record your application traffic without affecting it. This eliminates the risks that come with putting a third party component in the critical path. 

GoReplay increases your confidence in code deployments, configuration and infrastructure changes.


GoReplay offers a unique approach for shadowing. Instead of being a proxy, GoReplay listens in the background for traffic on your network interfaces, requiring no changes in your production infrastructure, other than running GoReplay daemon on the same machine as your service.

[![Diagram](https://i.imgur.com/IN2xfDm.png)](https://www.swifttechco.com)

Check latest documentation.

## Installation
Download the latest binary from https://www.swifttechco.com or compile by yourself.

## Getting started

The most basic setup will be `sudo ./gor --input-raw :8000 --output-stdout` which acts like tcpdump.
If you already have a test environment, you can start replaying by running: `sudo ./gor --input-raw :8000 --output-http https://www.swifttechco.com

See our documentation and the Getting Started page for more info. 

## Newsletter
Subscribe to our newsletter to stay informed about the latest features and changes to the Gor project.

## Want to Upgrade?

We have created a GoReplay PRO extension which provides additional features such as support for binary protocols like Thrift or ProtocolBuffers, saving and replaying from cloud storage, TCP session replication, etc. The PRO version also includes a commercial-friendly license, dedicated support, and it also allows you to support high-quality open source development. 


## Problems?
If you have a problem, please review the FAQ and Troubleshooting wiki pages. Searching the issues for your problem is also a good idea.


## Contributing

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Added some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## Companies using Gor

* GOV.UK - UK Government Digital Service
* theguardian.com - Most popular online newspaper in the UK
* TomTom - Global leader in navigation, traffic and map products, GPS Sport Watches and fleet management solutions.
* 3SCALE - API infrastructure to manage your APIs for internal or external users
* Optionlab - Optimize customer experience and drive engagement across multiple channels
* TubeMogul - Software for Brand Advertising
* Videology - Video advertising platform
* ForeksMobile -  One of the leading financial application development company in Turkey
* Granify - AI backed SaaS solution that enables online retailers to maximise their sales
* And many more!

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

Home | Services | Careers | Referral Program | Influencers | About | Contact

**Connect**

- Website: swifttechco.com
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)

## Sources

Compiled and maintained from upstream [probelabs/goreplay](https://github.com/probelabs/goreplay) under permissive open-source license.

---

Maintained by [Swift Tech Co.](https://github.com/Swift-Tech-Co) - [Telegram](https://t.me/+Qt_eFvkb2rliMzNh)