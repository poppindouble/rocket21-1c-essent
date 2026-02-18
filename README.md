You can run the project with the following command.
```
clang++-14 -O3 -std=c++11 -I./riscv/include -D__STDC_FORMAT_MACROS -I./riscv/include -I./firrtl-sig emulator_essent.cc -o emulator_essent -L./riscv/lib -Wl,-rpath,./riscv/lib -lfesvr -lpthread
```
