# Vireon Architecture Overview

Vireon is modular Face ID system for Linux written in Rust/usr/lib/qt6/plugins/kf6/parts/katepart.so
/usr/lib/qt/plugins/kf5/parts/katepart.so. Its goals are:
- Privacy-preserving biometric auth;
- Secure storage of face embedding;
- Extensibility via modules;
- PAM integration for login and sudo;
- Fill local processing, no cloud;

## Modules
- vireon-core: Shared traits and types
- vireon-engine: Face embedding generation
- vireon-storage: Encrypted vector storage
- vireon-daemon: Auth daemon (IPC interface)
- vireon-cli: User interface CLI 
- vireon-pam: PAM auth module
