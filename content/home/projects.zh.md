+++
# Projects widget.
# This widget displays all projects from `content/project/`.
widget = "projects"
active = true
date = "2017-07-20T00:00:00"

title = "科研项目"
subtitle = ""

# Order that this section will appear in.
weight = 10

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "全部"
  tag = "*"

[[filter]]
  name = "内核边界"
  tag = ".inner-core-boundary"

[[filter]]
  name = "核试验"
  tag = ".nuclear-test"

+++

