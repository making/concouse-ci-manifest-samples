# concouse-ci-manifest-samples

**Replace TODO properties for your environment**


## AWS

``` console
$ bosh-init deploy bosh-aws.yml
$ bosh target xxx.xxx.xxx.xxx
$ bosh update cloud-config aws.yml
$ bosh upload stemcell xxx
$ bosh upload release xxx
$ bosh deployment concourse.yml
$ bosh deploy
```

## Azure

Deploy BOSH with template
https://azure.microsoft.com/en-us/documentation/templates/bosh-setup/

in devbox

``` console
$ bosh update cloud-config azure.yml
$ bosh upload stemcell xxx
$ bosh upload release xxx
$ bosh deployment concourse.yml
$ bosh deploy
```
