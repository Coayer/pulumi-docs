---
title: "pulumi state"
aliases:
  - /docs/reference/cli/pulumi_state/
---



Edit the current stack's state

## Synopsis

Edit the current stack's state

Subcommands of this command can be used to surgically edit parts of a stack's state. These can be useful when
troubleshooting a stack or when performing specific edits that otherwise would require editing the state file by hand.

## Options

```
  -h, --help   help for state
```

## Options inherited from parent commands

```
      --color string                 Colorize output. Choices are: always, never, raw, auto (default "auto")
  -C, --cwd string                   Run pulumi as if it had been started in another directory
      --disable-integrity-checking   Disable integrity checking of checkpoint files
  -e, --emoji                        Enable emojis in the output
  -Q, --fully-qualify-stack-names    Show fully-qualified stack names
      --logflow                      Flow log settings to child processes (like plugins)
      --logtostderr                  Log to stderr instead of to files
      --memprofilerate int           Enable more precise (and expensive) memory allocation profiles by setting runtime.MemProfileRate
      --non-interactive              Disable interactive mode for all commands
      --profiling string             Emit CPU and memory profiles and an execution trace to '[filename].[pid].{cpu,mem,trace}', respectively
      --tracing file:                Emit tracing to the specified endpoint. Use the file: scheme to write tracing data to a local file
  -v, --verbose int                  Enable verbose logging (e.g., v=3); anything >3 is very verbose
```

## SEE ALSO

* [pulumi](/docs/cli/commands/pulumi/)	 - Pulumi command line
* [pulumi state delete](/docs/cli/commands/pulumi_state_delete/)	 - Deletes a resource from a stack's state
* [pulumi state move](/docs/cli/commands/pulumi_state_move/)	 - Move resources from one stack to another
* [pulumi state rename](/docs/cli/commands/pulumi_state_rename/)	 - Renames a resource from a stack's state
* [pulumi state unprotect](/docs/cli/commands/pulumi_state_unprotect/)	 - Unprotect resources in a stack's state
* [pulumi state upgrade](/docs/cli/commands/pulumi_state_upgrade/)	 - Migrates the current backend to the latest supported version

###### Auto generated by spf13/cobra on 26-Sep-2024
