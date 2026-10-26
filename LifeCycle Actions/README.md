# LifeCycle Actions

Life Cycle Actions: Java handlers that run on entity and relation lifecycle hooks. Each generated action is its own Maven project in this folder.

## Expected files

- `<type>-<hook>-<name>-lca/ (one Maven project per Life Cycle Action, for example hcp-beforesave-customerid-lca/)`

## Documentation

https://docs.reltio.com/en/developer-resources/about-developer-resources/developer-resources-at-a-glance/customize-data-tasks-with-lcas/lca-configuration

---

This component is not yet managed by Reltio IDE. Files placed here are **not** fetched from or
applied to the tenant; they are version-controlled alongside the configuration so the repository
describes the whole tenant. This file exists because Git does not track empty directories.
