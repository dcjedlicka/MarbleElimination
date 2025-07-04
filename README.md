# MarbleElimination
Marble Elimination Simulation

To build web version
- set IS_EMSCRIPTEN = True in main.py
- from one directory up, run `uv tool run pygbag --can_close=1 --ume_block=0 --build MarbleElimination`
- output files are in `build/web`