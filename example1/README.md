# Example 1

This is a basic & minimal example, showing how to compile a program using MSVC.
Tested & working with Microsoft Visual Studio 2017.


# Getting Started

- Open a 'Visual Studio 2017 Developer Command Prompt'
- Change into this directory
- Execute
```
$ fbuild
```

You should now see the executable `helloworld.exe` inside the `_bin/` folder.


# Troubleshooting

### I'm getting `Could not import environment variable 'VSCMD_ARG_TGT_ARCH'`

Open a Visual Studio command prompt, by executing the following .bat in a `cmd.exe`
window: `C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Auxiliary\Build`.
This is assuming a default Visual Studio installation, the path might be different if you
changed the install location.

