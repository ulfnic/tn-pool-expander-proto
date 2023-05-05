# Pool Expander for TrueNAS© 13 - prototype

Expand all pools in the `ui/storage/pools` dashboard after page transition or load.

![Usage demo](https://raw.githubusercontent.com/ulfnic/tn-pool-expander-proto/main/demo.gif)

## Installation
```bash
chmod +x ./tn-pool-expander-proto
./tn-pool-expander-proto --install
```
Note: `tn-pool-expander-proto --install` is safe to run multiple times and automating it to run after updates insures the installation remains persistant.

## Removal
```bash
./tn-pool-expander-proto --remove
```
