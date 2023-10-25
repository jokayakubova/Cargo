rkspace = true
edition.workspace = true
homepage.workspace = true
license.workspace = true
repository.workspace = true

[dependencies]
anyhow = "1"
clap = { version = "3", features = ["derive"] }
forc-pkg = { version = "0.46.1", path = "../../forc-pkg" }
forc-tracing = { version = "0.46.1", path = "../../forc-tracing" }
forc-util = { version = "0.46.1", path = "../../forc-util" }
prettydiff = "0.5"
sway-core = { version = "0.46.1
