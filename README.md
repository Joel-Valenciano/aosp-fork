# aosp-fork
Simply put, this is a compatibility layer for running Android apps on GNU/Linux

The goal is to implement the parts of Android required by
the Android Compatibility Definition Document (CDD) in a way that:
- allows compatibility with existing Linux/GNU, and
- avoids duplicating functionality

For information on AOSP, see:
- AOSP Homepage: https://source.android.com/ 
- CDD Page: https://source.android.com/compatibility/cdd 

The AOSP Repostories are hosted at https://android.googlesource.com/

## Suggestions
Not much work has actually been done yet, but here are some ideas I came up with:
- lower the amount of external dependencies (i.e., shorten the manifest)
- use Cairo instead of Skia for graphics (or the other way around)
