## Spark Source

Spark is a complete, open source, full-stack solution for cloud-connected devices.

The content below includes everything necessary to build a powerful connected device from scratch, including hardware designs, firmware, cloud software, mobile app templates, and development tools.

### Repositories

#### Hardware

<div class="row">
{{#each repos.hardware}}
  {{> repo}}
{{/each}}
</div>

#### Firmware

<div class="row">
{{#each repos.firmware}}
  {{> repo}}
{{/each}}
</div>

#### Transport layer

The transport layer between Spark devices and the Spark Cloud is composed of [CoAP](https://tools.ietf.org/html/draft-ietf-core-coap-18) packets sent over a TCP socket encrypted through an RSA asymmetric key handshake passed off to an AES encrypted tunnel.

#### Cloud software

The Spark Cloud open source repository is currently in development, and will be released in March/April 2014.

#### Mobile app templates

<div class="row">
{{#each repos.mobile}}
  {{> repo}}
{{/each}}
</div>

#### Language wrappers

Official language wrappers are currently in development for Node.js, Ruby, and Python. In the meantime, please visit our [resources page](https://www.spark.io/resources) for community-developed language wrappers.

#### Development tools

<div class="row">
{{#each repos.dev}}
  {{> repo}}
{{/each}}
</div>

### Version control

We use [Git](http://git-scm.com/) for version control, and [Github](http://www.github.com) as our central repository for all of our source code. Anyone can view our open source repositories, and with a free Github account, raise issuea and contribute to our source code.

### Feature requests and bug fixes

We use [Github Issues](https://github.com/features) to track issues for each of our open source repositories, and [Waffle.io](https://waffle.io/) to share our workflow.

Each of the above repositories has a link for issues and a waffle board; feel free to submit feature requests and raise bugs on Github, and star a repository to follow its progress.

### Contributions

We welcome contributions to all of our open source repositories. These contributions come in the form of a [Pull Request](https://help.github.com/articles/using-pull-requests), where you "fork" our repositories and then request that we "pull" your changes back into our repositories. You must have a Github account to make a contribution.

All contributors must first sign the [Spark Individual Contributor License Agreement (CLA)](https://docs.google.com/a/spark.io/forms/d/1_2P-vRKGUFg5bmpcKLHO_qNZWGi5HKYnfrrkd-sbZoA/viewform), which is based on the Google CLA, and provides the Spark team a license to re-distribute your contributions.

Whenever possible, please follow these guidelines for contributions:

- Keep each pull request small and focused on a single feature or bug fix.
- Familiarize yourself with the code base, and follow the formatting principles adhered to in the surrounding code.
- Wherever possible, provide unit tests for your contributions. We use [Mocha](http://visionmedia.github.io/mocha/) to test Javascript and [UnitTest++](http://unittest-cpp.sourceforge.net/) to test C++.

### Other resources

To learn about Spark's other resources, please visit our [resources page](https://www.spark.io/resources), and chat with us in our [community](https://community.spark.io) or through IRC ([#spark on freenode](https://webchat.freenode.net/?channels=%23spark)).
