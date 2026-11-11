# JCRCMDS Plug-in

## Description

The JCRCMDS plug-in is a wrapper plug-in for the JCRCMDS utility of Craig Rutledge. The JCRCMDS command converts fixed format H, F and D specifications into free format DCL-* statements.

Craig Rutledge: http://www.jcrcmds.com/

Further information is available on the [JCRCMDS web site](https://tools-400.github.io/jcrcmds/).

## Installation

JCRCMDS requires RDi 9.6.0.13 or later.

1. Select **Help > Install New Software...** in RDi.
2. Enter the update site `https://tools-400.github.io/jcrcmds/update-site/eclipse/rdi8.0/` and select **JCRCMDS for RDi 8.0+**.
3. Finish the wizard and restart RDi.

## Usage

1) Load a RPG source member into the Lpex editor.
2) Right-click into the source member to open the context menu.
3) Select "JCRCMDS -> Convert all" or "JCRCMDS -> Convert selection" to start the conversion.

Then the plug-in uploads the entire source member or the selected lines to the host, executes command JCRHFD, downloads the converted source lines and updates the source member.

## Liability

This software is free and provided without warranty. You use it at your own risk: test it with non-critical data first, and back up your data before you use it. The [license](LICENSE) applies in addition.
