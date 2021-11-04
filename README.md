# Windows Cloud Image

**Windows Cloud Image** is a Packer project for building and provisioning `Microsoft Windows Server` and install `Cloudbase-init` on it

## Installation

Install the Packer, VirtualBox, QEMU binary on your system:

-   [Packer CLI](https://www.packer.io/downloads)
-   [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
-   [QEMU](https://www.qemu.org/download/)

Alternatively you can install them using your package manager:

```bash
# Install on Windows
choco install packer virtualbox qemu
```

## Usage

```bash
# Install dependencies
packer init .

# Build images
packer build .
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

---
