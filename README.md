# snapper-emerge

A wrapper for the gentoo command `emerge` that prompts the user whether a pre post btrfs snapper snapshot is created:

## Would you like to create snapper snapshot? [Yes/No]

The following if yes:
```
snapper create --command "CMD" --description "CMD"
```
Otherwise `CMD` is invoked as per usual.

## TODO

- exit early if not root and the command requires root
