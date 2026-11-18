# JCRCMDS

## Description

The JCRCMDS plug-in is a wrapper plug-in for the JCRCMDS utility of Craig Rutledge. The JCRCMDS command converts fixed format H, F and D specifications into free format DCL-* statements.

Craig Rutledge: http://www.jcrcmds.com/

Further information is available on the [JCRCMDS web site](https://tools-400.github.io/jcrcmds/).

## Features

* Converts the whole source member or only the selected lines in the LPEX editor.
* Runs the command JCRHFD of JCRCMDS on the IBM i and replaces the lines with the result.
* The product library, the work library, the work file and the JCRHFD command can be set in the preferences.

## Installation

JCRCMDS requires RDi 9.6.0.13 or later.

1. Select **Help > Install New Software...** in RDi.
2. Enter the update site `https://tools-400.github.io/jcrcmds/update-site/eclipse/rdi8.0/` and select **JCRCMDS for RDi 8.0+**.
3. Finish the wizard and restart RDi.

## Usage

How to convert a source with the plug-in is described in [USAGE.md](USAGE.md).

## Liability

This software is free and provided without warranty. You use it at your own risk: test it with non-critical data first, and back up your data before you use it. The [license](LICENSE) applies in addition.

## See Also

* [JCRCMDS Update Site](https://github.com/tools-400/jcrcmds)
