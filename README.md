# GRACE Marketplace

A Claude Code plugin marketplace that exposes the [GRACE plugin](https://github.com/grace-method/grace-plugin) for install via `/plugin marketplace add`.

> **Status: under development.** GRACE is being actively designed and refined. The methodology, plugin layout, and marketplace structure may change without notice. Anyone who picks this up before a stable release should expect breaking changes. There is no commitment to backwards compatibility at this stage and no obligation to early users.

## Register and install

```
/plugin marketplace add https://github.com/grace-method/grace-marketplace.git
/plugin install grace@grace-marketplace
```

## Update

```
/plugin marketplace update grace-marketplace
```

Followed by `/plugin install grace@grace-marketplace` again if a new version is available.

## What's in this repository

- `.claude-plugin/marketplace.json` — the marketplace manifest. Lists the GRACE plugin and points Claude Code at the plugin's source repository.

## License

MIT. See [LICENSE](./LICENSE).
