
[dependencies]
photon_lib = { path = "../photon_lib" }
anyhow = "1"
bytes = "1"
futures = "0.3"
futures-util = "0.3"
hyper = { version = "~0.14.20", features = ["http1", "http2", "client", "server"] }
hyper-tls = "0.5"
hyper-tungstenite = "0.10"
photon_lib = { path = "../photon_lib" }
regex = "1.6"
serde_json = "1"
shared = { path = "../bulletforcehax2_shared" }
tokio = "1.26"
tokio-tungstenite = { version = "0.18", features = ["native-tls"] }
hyper-tungstenite = "0.9"
tokio-tungstenite = { version = "0.19", features = ["native-tls"] }
tower = { version = "0.4", features = ["util"] }
tower-http = { version = "0.4", features = ["cors", "decompression-br"] } # NOTE: CrazyGames downloader requires decompression-br feature
tracing = "0.1"
futures = "0.3"
