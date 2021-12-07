
<!-- markdownlint-disable -->
# Confluent on OpenShift GitOps Demo
<!-- markdownlint-restore -->

[![README Header][readme_header_img]][readme_header_link]

<!--




  ** DO NOT EDIT THIS FILE
  **
  ** This file was automatically generated by the `build-harness`.
  ** 1) Make all changes to `README.yaml`
  ** 2) Run `make init` (you only need to do this once)
  ** 3) Run`make readme` to rebuild this file.
  **
  ** (We maintain HUNDREDS of open source projects. This is how we maintain our sanity.)
  **





-->
A end to end demo of setting up Confluent Operator on OpenShift 4

---






## Usage

### Overview
TODO

### Diagram




## Examples

### Getting Started
#### Requirements
* [Red Hat login](https://sso.redhat.com/auth/realms/redhat-external/login-actions/registration?client_id=cloud-services&tab_id=DeYAMfKt5Mo)
* [OpenShift CLI](https://formulae.brew.sh/formula/openshift-cli)
* [Flux CLI](https://fluxcd.io/docs/cmd/)
* [k9s](https://github.com/derailed/k9s) (optional but good idea)
* AWS Account ID
* Permission to create a new IAM user with access key and secret

### Pre-Deployment Tasks
* Login to your AWS account and create a new user with the username `osdCcsAdmin`` and attached administrator permissions. NOTE: The username has to be exactly that value. Enable programmatically access and download the access key and secret - you will need them in part 1. 
* Fork [confluent-openshift-gitops-demo](https://github.com/osodevops/confluent-openshift-gitops-demo) repository into your own GitHub account and clone to your local machine
* Fork [team-alpha-resources](https://github.com/osodevops/confluent-openshift-team-alpha-resources) repository into your own GitHub account and clone to your local machine

### 1. Create a OpenShift cluster
 Login and navigate to the [Clusters](https://console.redhat.com/openshift) section in the Red Hat Console. Here you can create a trial cluster on AWS or GCP, for this example we will be using AWS:
  - Click Create trial cluster and select AWS.
  - View and accept the terms and conditions. (this is mandatory to proceed) 
  - Complete the form with mandatory information (AWS account ID / Access key and secret / Cluster name / Region)
  - Select Single zone and 8 vCPU 32GiB RAM
  - Keep everything else as default and and click create. Kick back and make yourself a coffee or three - creating the cluster takes around ~30 minutes.





## Related Projects

Check out these related projects.

- [Confluent for Kubernetes (CFK) examples](https://github.com/osodevops/confluent-kubernetes-playground) - Playground for Kafka / Confluent Kubernetes experimentations



## Need some help

File a GitHub [issue](https://github.com/osodevops/confluent-openshift-gitops-demo/issues), send us an [email][email] or [tweet us][twitter].

## The legals

Copyright © 2017-2021 [OSO](https://oso.sh) | See [LICENCE](LICENSE) for full details.

[<img src="https://oso-public-resources.s3.eu-west-1.amazonaws.com/oso-logo-green.png" alt="OSO who we are" width="250"/>](https://oso.sh/who-we-are/)

## Who we are

We at [OSO][website] help teams to adopt emerging technologies and solutions to boost their competitiveness, operational excellence and introduce meaningful innovations that drive real business growth. Our developer-first culture, combined with our cross-industry experience and battle-tested delivery methods allow us to implement the most impactful solutions for your business.

Looking for support applying emerging technologies in your business? We’d love to hear from you, get in touch by [email][email]

Start adopting new technologies by checking out [our other projects][github], [follow us on twitter][twitter], [join our team of leaders and challengers][careers], or [contact us][contact] to find the right technology to support your business.[![Beacon][beacon]][website]

  [logo]: https://oso-public-resources.s3.eu-west-1.amazonaws.com/oso-logo-green.png
  [website]: https://oso.sh?utm_source=github&utm_medium=readme&utm_campaign=osodevops/confluent-openshift-gitops-demo&utm_content=website
  [github]: https://github.com/osodevops?utm_source=github&utm_medium=readme&utm_campaign=osodevops/confluent-openshift-gitops-demo&utm_content=github
  [careers]: https://oso.sh/careers/?utm_source=github&utm_medium=readme&utm_campaign=osodevops/confluent-openshift-gitops-demo&utm_content=careers
  [contact]: https://oso.sh/contact/?utm_source=github&utm_medium=readme&utm_campaign=osodevops/confluent-openshift-gitops-demo&utm_content=contact
  [linkedin]: https://www.linkedin.com/company/oso-devops?utm_source=github&utm_medium=readme&utm_campaign=osodevops/confluent-openshift-gitops-demo&utm_content=linkedin
  [twitter]: https://twitter.com/osodevops?utm_source=github&utm_medium=readme&utm_campaign=osodevops/confluent-openshift-gitops-demo&utm_content=twitter
  [email]: mailto:enquiries@oso.sh?utm_source=github&utm_medium=readme&utm_campaign=osodevops/confluent-openshift-gitops-demo&utm_content=email
  [readme_header_img]: https://oso-public-resources.s3.eu-west-1.amazonaws.com/oso-animation.gif
  [readme_header_link]: https://oso.sh/what-we-do/?utm_source=github&utm_medium=readme&utm_campaign=osodevops/confluent-openshift-gitops-demo&utm_content=readme_header_link
  [beacon]: https://github-analyics.ew.r.appspot.com/G-WV0Q3HYW08/osodevops/confluent-openshift-gitops-demo?pixel&cs=github&cm=readme&an=confluent-openshift-gitops-demo