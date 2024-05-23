# Introduction
Template for Rust "Hello World!" project.

# Get started
- Click the **Run** button to run the program.
  ![Run](https://lf-cdn.marscode.com/obj/eden-sg/ljhwz_lkpkbvsj/ljhwZthlaukjlkulzlp/project_template/images/native_rust/run.jpeg)
- Go to the Terminal panel to view the output.
  ![Run](https://lf-cdn.marscode.com/obj/eden-sg/ljhwz_lkpkbvsj/ljhwZthlaukjlkulzlp/project_template/images/native_rust/terminal.jpeg)

By default, MarsCode provide you with a default running configuration, running main.rs. You can modify it in the **.vscode/launch.json**. Refer to [Visual Studio Code's doc](https://code.visualstudio.com/docs/editor/debugging) for how to configure launch.json.

# Learn more
[rust](https://www.rust-lang.org/learn) - learn about Rust Programming.

# Help
If you need help, you might be able to find an answer in our [docs](https://docs.marscode.com/). Feel free to report bugs and give us feedback [here](https://discord.gg/qtVMXEDbRw).

# Command
```shell
cargo add crossterm
cargo clippy
cargo clippy -- -W clippy::all  -W clippy::pedantic
cargo clippy --allow-no-vcs --fix -- -W clippy::all  -W clippy::pedantic
# open all function
cargo clippy -- -W clippy::all -W clippy::pedantic  -W clippy::nursery -W clippy::cargo -W clippy::restriction
```

# doc
```text
https://vt100.net/docs/vt100-ug/chapter3.html
```