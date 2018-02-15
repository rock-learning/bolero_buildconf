# bolero_buildconf

Bootstrapping repository, used to setup a BOLeRo working environment.
You can use [pybob](https://github.com/rock-simulation/pybob) or
[autoproj](https://github.com/rock-core/autoproj) to set up BOLeRo.

## pybob

See [pybob's readme](https://github.com/rock-simulation/pybob) for details.

## autoproj

1. install ruby, ruby-dev (on Ubuntu), git, and wget
1. `wget http://www.rock-robotics.org/autoproj_bootstrap`
1. `ruby autoproj_bootstrap git git@github.com:rock-learning/bolero_buildconf.git`
1. `source env.sh`
1. `aup`
1. `amake`
