workspace(name = "org_openmined_psi")

load("@org_openmined_psi//private_set_intersection:preload.bzl", "psi_preload")

psi_preload()

register_toolchains("//private_set_intersection/python/toolchain:python_toolchain")

load("@org_openmined_psi//private_set_intersection:deps.bzl", "psi_deps")

psi_deps()
