# tansuasici Claude Code plugins

One marketplace for three discipline kits. Adding it installs nothing; you
pick the kits you want.

```
/plugin marketplace add tansuasici/claude-plugins
```

Then install any of them:

| Kit | Install | For |
| --- | --- | --- |
| [Claude Code Kit](https://claudecodekit.tansuasici.com) | `/plugin install code-kit@tansuasici` | Software work: plan, confirm, implement, verify |
| [Claude Design Kit](https://claudedesignkit.tansuasici.com) | `/plugin install design-kit@tansuasici` | Interface work: brief, direction, build, audit |
| [Claude Research Kit](https://clauderesearchkit.tansuasici.com) | `/plugin install research-kit@tansuasici` | Scholarly writing: evidence, draft, verify, cite |

Each kit lives in its own repository and is also published on npm
(`npx @tansuasici/claude-<name>-kit init`) if you'd rather copy it into a
project than run it as a plugin.

## License

MIT. Each kit carries its own license and notices.
