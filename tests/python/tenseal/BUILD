load("@org_openmined_tenseal_python_deps//:requirements.bzl", "requirement")

py_test(
    name = "tenseal_python_tests",
    srcs = [
        "main.py",
        "test_enc_dec.py",
        "test_serialization.py",
        "test_tensealcontext.py",
        "utils.py",
        "tensors/test_bfv_vector.py",
        "tensors/test_ckks_vector.py",
        "tensors/test_perf.py",
        "tensors/test_serialization.py",
            ],
    main = "main.py",
    python_version = "PY3",
    srcs_version = "PY3",
    deps = [
        "//tenseal:tenseal",
        requirement("pytest"),
        requirement("numpy"),
        requirement("pytest-benchmark"),
        requirement("scikit-image"),
    ],
)
