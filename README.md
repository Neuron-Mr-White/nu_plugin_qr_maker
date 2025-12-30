# nu_plugin_qr_maker

A [nushell](https://www.nushell.sh/) plugin to create qr code in terminal.

**Compatible with Nushell 0.109.1+**

## Examples

```bash
~> "https://google.com" | to qr
```

![image](https://github.com/FMotalleb/nu_plugin_qr_maker/assets/30149519/1771961a-b06b-4310-81ed-63865e8d2f8e)

## Installing

* using [nupm](https://github.com/nushell/nupm)

```bash
git clone https://github.com/Neuron-Mr-White/nu_plugin_qr_maker.git
nupm install --path nu_plugin_qr_maker -f
```

* or compile manually

```bash
git clone https://github.com/Neuron-Mr-White/nu_plugin_qr_maker.git
cd nu_plugin_qr_maker
cargo build
plugin add target/debug/nu_plugin_qr_maker.exe
```

* or using cargo

```bash
cargo install nu_plugin_qr_maker
plugin add ~/.cargo/bin/nu_plugin_qr_makern.exe
```
