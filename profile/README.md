# Research Projects on AMD SEV-SNP platform

## Cabin: Confining Untrusted Programs within Confidential VMs

Cabin is a system aiming at protecting the guest OS from the untrusted program within confidential VMs. Cabin is built on top of [AMD SEV-SNP](https://developer.amd.com/sev/) platform.

TODO:

- ✅ Implement the basic functionality of Cabin
- ✅ Support anonymous memory management
- ✅ Support asynchronous forwarding of system calls
- ❌ Support fork/clone system calls
- ❌ Support multi-threading
- ❌ Support thread-migration
- ✅ Support zpoline
- ❌ Support lazypoline
- ❌ Support passthru-libos
