---
layout: layout.pug
navigationTitle:  Quick Start
title: Quick Start
menuWeight: 40
excerpt:
enterprise: false
---

<!-- This source repo for this topic is https://github.com/mesosphere/dcos-kubernetes -->


# Prerequisite

- [DC/OS installed on your cluster](/latest/administration/installing/).

# Steps

## Open Source DC/OS

1. If you are using Open Source DC/OS, install a Kubernetes cluster with the following command from the DC/OS CLI.

    ```shell
    dcos package install beta-kubernetes
    ```

    Alternatively, you can install Kubernetes from [the DC/OS web interface](/latest/usage/webinterface/).

1. The service will now deploy with a default configuration. You can monitor its deployment via the **Services** tab of the DC/OS web interface.

## Enterprise DC/OS

If you are using Enterprise DC/OS, follow the same steps as for Open-Source DC/OS. However, you should read the [Install and Customize](/services/beta-kubernetes/0.4.0-1.9.0-beta/install/) section for more information.
