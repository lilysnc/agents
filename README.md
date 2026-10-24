# agents

```
axterm config set sources https://github.com/lilysnc/agents   # one line (replaces the list)
axterm sources add https://github.com/lilysnc/agents          # adds to the existing list

axterm sources list
axterm sources update   # sync all active sources

axterm kill <session-id>
axterm resume <session-id>
```

Shared OMP configuration.

- `omp/model-presets.yml` — model presets consumed by the `omp-remote-presets` extension.
