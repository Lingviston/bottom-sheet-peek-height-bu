# bottom-sheet-peek-height-bu
Demo of the BottomSheet peekHeight bug

When edge-to-edge is enabled and `paddingBottomSystemWindowInsets=true` the first layout of the `BottomSheet` results in incorrect `peekHeight`. It is enought to expand/collapse it once to fix the bug.

See demo in the /demo folder.

