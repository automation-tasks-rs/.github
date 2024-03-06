# automation_tasks_rs

Cargo is a great tool for building Rust projects. It has all the basics: `cargo build`, `cargo build --release`, `cargo fmt`, `cargo test`, `cargo doc`,...  
But sometimes we need to do more things like copying some files, publishing to FTP, or entering long commands. These repetitive tasks must be automated.  
Task automation makes work easier and faster, and simplifies the workflow while improving the consistency and accuracy of workflows.  
This is also sometimes referred to as "workflow automation."  
There are many different build systems and task runners there: `make`, `cmake`, `shell scripts`, `cargo-xtask`, `cargo-make`, `cargo-task`, `cargo-script`, `cargo-run-script`, `runner`, `python scripts`, `powershell scripts`, `cmd prompt scripts`, ...  
Sadly there is no standard in the Rust community for now.  
I want something similar to [build.rs](https://doc.rust-lang.org/cargo/reference/build-scripts.html), so I can write my "tasks" in pure Rust.  
I don't want to learn another meta language with weird syntax and difficulty to debug.   
