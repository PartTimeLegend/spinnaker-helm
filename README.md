# Spinnaker Chart

Forked to allow for Spinnaker 1.27.0 to use Halyard 1.45.0

[Spinnaker](http://spinnaker.io/) is an open source, multi-cloud continuous delivery platform.

## Chart Details
This chart will provision a fully functional and fully featured Spinnaker installation
that can deploy and manage applications in the cluster that it is deployed to.

Redis and Minio are used as the stores for Spinnaker state.

For more information on Spinnaker and its capabilities, see it's [documentation](http://www.spinnaker.io/docs).

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm repo add spinnaker https://parttimelegend.github.io/spinnaker-helm/
$ helm install --name my-release spinnaker/spinnaker --timeout 600
```

