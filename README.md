# Elixir Enum.each Modification Bug

This example demonstrates a common pitfall in Elixir when trying to modify a list during iteration using `Enum.each`. The code attempts to remove the element `3` from the list while iterating, but it doesn't work as expected because lists are immutable in Elixir.

The solution involves using other functions like `Enum.filter` or `Enum.reduce` for modifying lists during iteration.