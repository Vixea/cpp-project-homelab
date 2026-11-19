# Homelab Monitor (Dashboard)

Monitor the status of devices in homelab.

## Capabilities

- Dashboard: Browser based, access within the tailnet
    - Allow terminal for Proof of Concept
    - Future gui through a virtual display much like ip kvms but without having to have an ip kvm

### Available Metrics/Dashboard Functions

- CPU Usage/Thermal
- Process Monitoring? Kill? 
- Memory Monitoring
- GPU Utilization
- Network Monitoring/Utilization/Config
    - intrusion detection?
- Package Update Notifications?

### Supported Devices

- (Arch) Linux Servers/NAS freenas

### Stretch

- Potential CVE Vuln on Server Warning? patchmon

### Unknowns

- Security? Tailscale exists

### Must Have

- Authentication - use tailscale api for basic access into the dashboard with pin/webauthn(hardware keys) for privileged access to tools

### Technology

- C++23, Clang22 or 23 maybe. (bazel)
- Webassembly emscripten (also clang)
- Typescript (vite)
    - Vanilla TS
- Server? Python? Nodejs? Something else  --> Try HONO.js <--


## TODO

- Figure out tests