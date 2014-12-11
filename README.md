Ansible Tower Demo-In-A-Box
===========================

## Prerequisites

The following must be installed prior to using this demo:

* [Vagrant](https://www.vagrantup.com/downloads.html) - tested with v1.6.5
* [Virtualbox](https://www.virtualbox.org/wiki/Downloads) - tested with v4.3.20-96996

### Helpful configurations

There are a few very useful Vagrant plugins that might make your life a little easier: 

* [Landrush](https://github.com/phinze/landrush)
* [Vagrant-pristine](https://github.com/fgrehm/vagrant-pristine)

## Running the Demo

To start run: 

```
vagrant up
```

To log into Tower:

If you have the [Landrush Vagrant](https://github.com/phinze/landrush) plugin installed:

```
https://tower.ansible.dev
```

If you do not have Landrush installed:

```
https://10.42.0.10
```

Credentials to log into Tower are:

* username: admin
* password: password