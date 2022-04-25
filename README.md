# adhd-project-management
A shell-based project management tool for the engineer whom has a short attention span.

> It might be limited to small teams, but there is no learning curve, no outdated versions, and no installation overhead.

# Installation
If you keep a directory structure like I do, which is:

```
~/code
   |- work
   |--- app_one
   |--- app_two
   |- projects
   |--- derpin_around
   |--- cant_get_outta_this_rabbithole
```

`cd ~/code && wget https://raw.githubusercontent.com/mculp/adhd-project-managment/main/todos && chmod +x todos`



# Usage
1. Use comments like `# TODO: Some urgent task` in your sources.
2. Add `~/code` to your `$PATH`
3. Run `./todos` to list your todos.

# Language support
- Ruby
- Markdown (check the raw contents of this file ;)

[//]: # (TODO: # Prioritization)
[//]: # (TODO: Add `priority N` somewhere in the comment, where N is an integer. Your todos will be ordered by priority descending.)
[//]: # (TODO: More language support)
[//]: # (TODO: Code golf it into an alias?)
[//]: # (TODO: Maybe start a suite of adhd tools, such as `git recent`)
[//]: # (TODO: https://rubydoc.info/gems/yard/file/docs/Tags.md#todo)
