---
layout: post
title: Serverless!
---
Serverless Framework:
1. Chalice (Python)
Chalice is a framework by AWS for writing serverless applications in Python, and allows to quickly create and deploy applications that use AWS Lambda. Chalice provides a command line tool for creating, deploying, and managing apps, integration with common AWS services, and automatic IAM policy generation. Chalice is [available on GitHub](https://github.com/aws/chalice).
2. Zappa (Python)
Probably the most popular tool for deploying serverless web services in Python, Zappa enables to easily deploy web applications, usually written in Flask or Django. Zappa wraps the standard application and deploys a Lambda function to enable a serverless, scalable experience. Zappa is [available on GitHub](https://github.com/Miserlou/Zappa).
3. Sparta (Go)
The Go programming language is becoming more and more popular, and together with the announcement of Go support for AWS Lambda earlier this year, Sparta is a framework that transforms a standard Go application into a self-deploying AWS Lambda powered service, while all configuration and infrastructure requirements are written as Go types as well. Sparta is [available on GitHub](https://github.com/mweagle/Sparta).
4. Apex (Go)
Apex is a framework which aims to let you easily build, deploy, and manage AWS Lambda. One of the key features of Apex is the ability to use languages that are not natively supported by AWS Lambda through the use of a Node.js shim injected into the build. In addition to building and deploying the functions, other related tools provide testing, deployment roll-backs, and log tailing. Apex is [available on GitHub](https://github.com/apex/apex).

Serverless Patterns:
1. Command Pattern
2. Messaging Pattern
3. Legacy API wrapper
4. Fan-out pattern
5. Pipes and filters pattern
