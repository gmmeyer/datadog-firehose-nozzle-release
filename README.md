# datadog-firehose-nozzle-release

BOSH release for datadog-firehose-nozzle

[Link to Cloud Foundry documentation on installing a nozzle](https://docs.cloudfoundry.org/loggregator/nozzle-tutorial.html)

wget https://storage.googleapis.com/golang/go1.7.3.linux-amd64.tar.gz
bosh add blob go1.7.3.linux-amd64.tar.gz golang
bosh create release --force
bosh upload release
