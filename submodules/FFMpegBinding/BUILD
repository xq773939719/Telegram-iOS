
objc_library(
    name = "FFMpegBinding",
    module_name = "FFMpegBinding",
    enable_modules = True,
    srcs = glob([
        "Sources/**/*.m",
        "Sources/**/*.h",
    ]),
    hdrs = glob([
        "Public/**/*.h",
    ]),
    copts = [
        "-Werror",
    ],
    includes = [
        "Public",
    ],
    deps = [
        "//submodules/ffmpeg",
    ],
    visibility = [
        "//visibility:public",
    ]
)
