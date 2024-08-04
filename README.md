# just as planned
make all dlc free and playable in a certain rhythm game (muse dash btw)

# 8/2/2023
added `GameAssembly.dll` patcher, you just have to put the original `GameAssembly.dll` in the same folder as `patch_ga.py` then it will generate `GameAssembly_patched.dll` and put it in Muse Dash directory
currently doesn't have wildcard bytes support

# 8/3/2023
added support for wildcard bytes, so no need to hardcode the whole actual bytes
the `consts.py`, `main.py`, and `utility.py` is not needed if you use the `patch_ga.py` as i am no longer updating the offset for runtime patching

# how to use?
1 put original `GameAssembly.dll` to the same directory as `patch_ga.py`
2 then run `patch_ga.py` (`python patch_ga.py`)
3 wait for a while until it generated `GameAssembly_patched.dll`
4 put `GameAssembly_patched.dll` to your muse dash directory and rename it to `GameAssembly.dll`
