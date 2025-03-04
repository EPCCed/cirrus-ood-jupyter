# Cirrus Open OnDemand - Jupyter Lab Server

![GitHub Release](https://img.shields.io/github/release/EPCCed/cirrus-ood-jupyter.svg)
![GitHub License](https://img.shields.io/github/license/EPCCed/cirrus-ood-jupyter.svg)

An Open OnDemand Batch Connect app for Cirrus that launches a Jupyter Lab
server within a batch job.

## Prerequisites

This Batch Connect app requires the following software be installed on the
**compute nodes** that the batch job is intended to run on (**NOT** the
OnDemand node):

- [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/) 4.2.3+ (earlier
  versions are untested but may work for you)
- [OpenSSL](https://www.openssl.org/) 1.0.1+ (used to hash the Jupyter Notebook
  server password)

**Optional** software:

- [Lmod](https://www.tacc.utexas.edu/research-development/tacc-projects/lmod)
  6.0.1+ or any other `module restore` and `module load <modules>` based CLI
  used to load appropriate environments within the batch job before launching
  the Jupyter Notebook server.

## Contributing

1. Fork it ( https://github.com/EPCCed/cirrus-ood-jupyter/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
