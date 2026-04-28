# sim-plugin-pandapower

Pandapower driver for [sim-cli](https://github.com/svd-ai-lab/sim-cli),
distributed as an out-of-tree plugin.

pandapower driver for sim.

## Install

```bash
sim plugin install pandapower
```

Other paths:

```bash
pip install git+https://github.com/svd-ai-lab/sim-plugin-pandapower@v0.1.0
pip install https://github.com/svd-ai-lab/sim-plugin-pandapower/releases/download/v0.1.0/sim_plugin_pandapower-0.1.0-py3-none-any.whl
pip install -e .
```

After install:

```bash
sim plugin doctor pandapower
sim plugin sync-skills
```

## Development

```bash
git clone https://github.com/svd-ai-lab/sim-plugin-pandapower
cd sim-plugin-pandapower
uv sync
uv run pytest
```

## License

Apache-2.0.
