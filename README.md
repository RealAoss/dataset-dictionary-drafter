# Dataset Dictionary Drafter

Draft a field dictionary from an example dataset, source notes and known constraints.

Copy the instructions in [SKILL.md](SKILL.md) into ChatGPT or Claude and supply the material you want reviewed. In an Agent Skills environment, install the folder with its original name.

## Example

A column named amount has numeric values but no currency field or notes.

Expected behavior: Document numeric observations and flag currency and gross-versus-net meaning as unresolved.

## Limitations

Results depend on the supplied material and the assistant's interpretation. Use the worked example to inspect the output before applying it to new material.

## Development

See [CONTRIBUTING.md](CONTRIBUTING.md) for setup and test commands, and the [changelog](CHANGELOG.md) for project history.

## License

[MIT License](LICENSE). Copyright (c) 2026 dataset-dictionary-drafter contributors.
