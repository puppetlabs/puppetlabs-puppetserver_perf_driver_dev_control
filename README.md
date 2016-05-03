# puppetlabs-puppetserver_perf_driver_dev_control
## r10k control repo for Puppet Server perf testing dev environment

This repo is an r10k control repo that is used for setting up a
Puppet Server performance testing driver machine in a sandbox
environment (specifically, tested with vmpooler cent7 nodes.)

It is intended for use when doing development work in the
[gatling-puppet-load-test](https://github.com/puppetlabs/gatling-puppet-load-test/)
repo, when you want to set up a sandbox driver node (with a jenkins instance that
can be used to run gatling jobs), rather than developing against the production
driver instance.

For more information, see the
[`README` in the `jenkins-integration` directory](https://github.com/puppetlabs/gatling-puppet-load-test/tree/master/jenkins-integration)
of the `gatling-puppet-load-test` project.
