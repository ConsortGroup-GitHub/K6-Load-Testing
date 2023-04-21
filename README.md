# Grafana K6-Load-Testing

#### What is k6?

Grafana k6 is an open-source load testing tool that makes performance testing easy and productive for engineering teams. k6 is free, developer-centric, and extensible.

Using k6, you can test the reliability and performance of your systems and catch performance regressions and problems earlier. k6 will help you to build resilient and performant applications that scale.

They use k6 for **testing the performance and reliability of APIs, microservices, and websites.** Common k6 use cases are:

##### _Load testing_
k6 is optimized for minimal resource consumption and designed for running high load tests (spike, stress, soak tests).

##### _Browser testing_
Through k6 browser, you can run browser-based performance testing and catch issues related to browsers only which can be skipped entirely from the protocol level.

##### _Chaos and resilience testing_
You can use k6 to simulate traffic as part of your chaos experiments, trigger them from your k6 tests or inject different types of faults in Kubernetes with xk6-disruptor.

##### _Performance and synthetic monitoring_
With k6, you can automate and schedule to trigger tests very frequently with a small load to continuously validate the performance and availability of your production environment.

#### K6 Installation 

**On Debian and Ubuntu** : 

- _sudo gpg -k_.
- _sudo gpg --no-default-keyring --keyring /usr/share/keyrings/k6-archive-keyring.gpg --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys C5AD17C747E3415A3642D57D77C6C491D6AC1D69_.
- _echo "deb [signed-by=/usr/share/keyrings/k6-archive-keyring.gpg] https://dl.k6.io/deb stable main" | sudo tee /etc/apt/sources.list.d/k6.list_.
- _sudo apt-get update_.
- _sudo apt-get install k6_.

**With docker** :
- _pull grafana/k6_. 


**On MacOs** : 
- _brew install k6_.

**On Windows** :
- _winget install k6_. (**official k6 package**) / _choco install k6_. (**unofficial k6 package**)    
