# Vireon

Secure FaceID authentication for Linux, written in Rust.

Vireon is a modular authentication daemon that uses facial recognition to grant or deny access to sensitive operations such as sudo, login, or desktop unlock.

✨ Features

    🔐 FaceID authentication with ONNX-based models (ArcFace, FaceNet)
    📷 Camera capture via V4L2
    ⚡ Fast and secure inference using ONNX Runtime
    🧠 Compares embeddings to stored face profiles
    🔌 Future: PAM module, multi-factor auth (USB key, fingerprint)

📦 Installation

    Currently under development. To build:

git clone https://github.com/ret2gl1ch/vireon.git
cd vireon
cargo build --release
