# LSF maintained action security fork

Based on actions/attest v4.2.1 at 508db95dd578ae2727ebd6217d5ba78e4fbda05d.

The runtime dependency graph is pinned to patched package versions and the action bundles are rebuilt from that lock. The public npm registry is used for mirrored development tarballs with their original integrity retained.

Validation: Node 24.19.0 on Linux, locked installation, upstream build and the available upstream unit-test suite. Runtime OSV scan: zero findings in 148 packages. Exact bundle hashes and dependency selections are recorded in LSF-SECURITY.json.

This work was discovered while hardening CI for [Latent Service Fabric (LSF)](https://github.com/KirilsTurkins/latent-service-fabric) and is being contributed upstream. Upstream licenses and source history are retained.
