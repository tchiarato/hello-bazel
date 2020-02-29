java_binary(
    name = "hello-world",
    srcs = glob(["*.java"]),
    main_class = "helloworld.HelloWorld",
    deps = [
        "//core/greeting/src/main/java/greeting:greeting",
        "@maven//:joda_time_joda_time",
    ],
)
