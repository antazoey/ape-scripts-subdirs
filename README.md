# For testing sub dirs in scripts

```bash
# From top dir
ape run top_click
ape run top_main
ape run top_none

# From first level subdir
ape run subdir1 middle_click
ape run subdir1 middle_main
ape run subdir1 middle_none

# From second level subdir
ape run subdir1 subdir2 last_click
ape run subdir1 subdir2 last_main
ape run subdir1 subdir2 last_none
```