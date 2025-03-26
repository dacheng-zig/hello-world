# hello world

This zig project was created by:

```shell
$ zig init
```

How to build from cli:

```shell
$ zig build
```

When built done, you will get the artifacts:

```shell
$ tree .

.
├── README.md
├── build.zig
├── build.zig.zon
├── src
│   ├── main.zig
│   └── root.zig
└── zig-out
    ├── bin
    │   └── hello_world
    └── lib
        └── libhello_world.a

5 directories, 7 files

```

Run it:

```shell
$ ./zig-out/bin/hello_world
```