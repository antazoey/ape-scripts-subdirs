# For testing sub dirs in scripts

```bash
# From top dir
ape run top_click
ape run top_main

# From first level subdir
ape run subdir1 middle_click
ape run subdir1 middle_main

# From second level subdir
ape run subdir1 subdir2 middle_click
ape run subdir1 subdir2 middle_main
```