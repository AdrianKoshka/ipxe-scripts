# ipxe-scripts
Various chain/boot scripts for ipxe

## Example

to see an example of what these scripts look like [click here](menu.md)

## Structure

```
boot
├── efi_shell.ipxe
├── linux
│   ├── dban.ipxe
│   ├── debian.ipxe
│   ├── deb-webboot
│   │   ├── 586-kern.ipxe
│   │   └── 686-kern.ipxe
│   ├── deb-webboot.ipxe
│   ├── fed
│   │   ├── centos.ipxe
│   │   ├── fedora.ipxe
│   │   └── scientific.ipxe
│   ├── fed.ipxe
│   ├── opensuse
│   │   └── stable.ipxe
│   ├── opensuse.ipxe
│   └── ubuntu.ipxe
├── linux.ipxe
├── menu.ipxe
└── winpe.ipxe
```

## Changelog

[CHANGELOG](CHANGELOG.md)

## License ![GPLv3 logo](https://www.gnu.org/graphics/gplv3-127x51.png)

This project is under the [GPLv3](LICENSE) license unless otherwise stated in
individual files.

## Auhtors

- [Theodore Seán Tubbs](https://github.com/AdrianKoshka)
