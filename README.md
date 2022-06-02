# 🧱 Bricks

[Mason][mason_link] bricks I use to build projects.

## Getting started 🚀

### Adding a brick 🫰

To add a brick, use any of the following commands:

```sh
# add from git url
mason add <BRICK_NAME> --git-url https://github.com/marcossevilla/bricks

# add from git url (global)
mason add -g <BRICK_NAME> --git-url https://github.com/marcossevilla/bricks

# add from git url with path
mason add <BRICK_NAME> --git-url https://github.com/marcossevilla/bricks --git-path path/to/<BRICK_NAME>

# add from git url with path and ref
mason add <BRICK_NAME> --git-url https://github.com/marcossevilla/bricks --git-path path/to/<BRICK_NAME> --git-ref tag-name
```

*Note: Be sure to replace `<BRICK_NAME>` with one of the following bricks:*

## Available bricks 🧱

| Brick Name            | Description                                              |
| --------------------- | -------------------------------------------------------- |
| dot_github            | Generate base configuration for a .github folder         |


[mason_link]: https://github.com/felangel/mason
