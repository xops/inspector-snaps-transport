# Inspector Snaps Transport

This adds [Metamask Snaps](https://github.com/MetaMask/metamask-snaps-beta) support to the [OpenRPC inspector](http://inspector.open-rpc.org).

## Install Instructions

1. Go to http://inspector.open-rpc.org
2. Click `HTTP` transport dropdown
3. Select `+ Add Transport`
4. Add plugin name: `Snaps`
5. Add plugin url: `https://xops.github.io/inspector-snaps-transport`
6. Select `POSTMESSAGE` as the transport type
7. Click `Add Transport`

![add_transport](https://user-images.githubusercontent.com/364566/77793417-40b72000-7027-11ea-9acb-615d2196848e.png)

8. use your snap id as the url: `wallet_plugin_http://localhost:8081/package.json`

![image](https://user-images.githubusercontent.com/364566/77793507-6f34fb00-7027-11ea-8201-fb5c64b644b8.png)

### Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.
