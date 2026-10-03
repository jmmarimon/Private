# Remote Control base

This folder is a dummy workspace. It exists so Cursor Remote Control has a small git repository to open instead of Veyra-NRVideo.

Veyra is a Windows C++ / D3D12 app. A cloud or setup agent cannot configure it: it needs MSVC, a local FFmpeg tree, Qt, and files that are not in git. This repository has none of that.

Use the repository root, not a subfolder by itself:

1. On your PC, clone `https://github.com/jmmarimon/private`.
2. In Cursor, open the Agents Window (`Ctrl+Shift+P`, then **Open Agents Window**).
3. Set this clone as the agent workspace.
4. Turn on **Settings → Agents → Remote Control**.
5. In the agent input, run `/remote-control`, then send your next message.
6. Leave the PC awake and online.

`notes.txt` is a scratch file. Edit it freely. Nothing here builds or installs software.
