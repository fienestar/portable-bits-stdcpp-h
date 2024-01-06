# portable bits/stdc++.h

stdc++.h cannot be directly transferred to other compilers. Some modifications have been made for MSVC and Apple Clang.

include any standard library header in IDE and find the path of the header file, then place stdc++.h in the `./bits/`.

or place stdc++.h anywhere/bits and add the path to the include path.

- in apple clang, place stdc++.h in `/Library/Developer/CommandLineTools/usr/include/bits/`
