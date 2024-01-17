# learning-rust-lang

## Create a new project 
```
  cargo new hello-world

  ├── README.md
  └── hello-world
      ├── Cargo.toml
      └── src
          └── main.rs

  2 directories, 3 files

  fn main() {
    println!("Hello World")
  }
```

## Rust Desktop App
```
sudo apt-get update 
sudo apt-get install -y musl-tools openssl-dev musl-dev libssl-dev
cargo install cargo-generate
cargo generate --git https://github.com/slint-ui/slint-rust-template --name desktop-app
cd desktop-app/
```

## Reference Links
- https://github.com/cargo-generate/cargo-generate
- https://doc.rust-lang.org/cargo/getting-started/first-steps.html
- https://doc.rust-lang.org/cargo/guide/creating-a-new-project.html
- https://github.com/slint-ui/slint/tree/master/examples
- https://github.com/slint-ui/slint/tree/master/examples
- https://www.youtube.com/watch?v=7aFgeUG9TK4