# RustExample

This repo is mainly a test on using Rust and QEMU.
Following the steps in docs.rust-embedded.org I was able to produce this result.

First download and install Rust, qemu (ARM install), Open OCD, and gcc compiler for arm. 
Make sure all of the paths after the installs are added to the environment variables so you will be able 
to call it in a Windows command prompt.

After downloading and installing everything you will be able to run this project by
1. Opening up Windows Command Prompt 
2. Changing your direcory to the root folder of this project
3. run command "cargo build" which will build the rust project
  - this can be edited by changing the code in main.rs
4. run command "cargo run" which will run the .elf file on the target specified in the .config file

Future Improvments:
I would love to convert a previous project written in C to Rust.
I would also love to emulate an stm32 board and run that project on it.
