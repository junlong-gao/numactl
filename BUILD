cc_library(
    name = "numactl",
    srcs = [
        "affinity.c",
        "clearcache.c",
        "distance.c",
        "libnuma.c",
        "mt.c",
        "rtnetlink.c",
        "shm.c",
        "stream_lib.c",
        "syscall.c",
        "sysfs.c",
        "util.c",
    ] + glob(["*.h"]),
    hdrs = [
        "numa.h",
        "numaif.h",
    ],
    linkstatic = True,
    visibility = ["//visibility:public"],
)
