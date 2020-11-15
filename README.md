A simple example of embedding Servo in a a non-browser application using OpenGL.

Status:
* [x] Simple glutin-based application can render Servo content (no interaction yet)
* [ ] GTK-based application can run Servo but GLArea integration does not work yet

Prerequisites for embedding Servo:
* a servo revision that includes https://github.com/servo/servo/pull/2776
* a Cargo.toml that overrides webrender, webrender_api, mio, and raqote (https://github.com/servo/servo/blob/c661cc87bac22c20f2d59659ef705267aee397a3/Cargo.toml#L29-L38)
* a rust-toolchain that matches the rust-toolchain in your servo clone
