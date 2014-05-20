AnimFix_OnPlayerRequestClass
============================

This is a fix for a bug on ApplyAnimation function. If the player reaches the spawn class for the first time since connection, the first model at the first time won't be performing any animation if ApplyAnimation is called under OnPlayerRequestClass. This include fixes that bug.
