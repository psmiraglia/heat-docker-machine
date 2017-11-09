# heat-docker-machine

OpenStack Heat template to bootstrap a Docker machine.

## How to use it

Deploy the template using the OpenStack CLI

    $ openstack stack create --enable-rollback \
        -t docker-machine.yml -e docker-machine.env.yml \
        docker-machine

## References

*   [OpenStack Heat](https://docs.openstack.org/developer/heat/)
*   [Heat Resource Types](https://docs.openstack.org/developer/heat/template_guide/openstack.html)
*   [Heat Template Guide](https://docs.openstack.org/developer/heat/template_guide/)
*   [Heat Environments](https://docs.openstack.org/developer/heat/template_guide/environment.html)
*   [Get Docker CE for Ubuntu](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu)
*   [docker-openstackclients](https://github.com/psmiraglia/docker-openstackclients)

