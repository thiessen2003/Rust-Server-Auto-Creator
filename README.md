# Rust Server Auto Creator

**Rust Server Auto Creator** is a Rust-based program that integrates with the OpenAI API to automate the creation of web servers. This project aims to simplify and expedite the setup process for Rust web servers by leveraging AI-driven templates and automated code generation.

## Features
- **Automated Server Creation**: Generates Rust web server code using predefined templates and integrates new features via OpenAI API.
- **Customizable Templates**: Modify or extend the web server template according to your needs.
- **AI-Powered Enhancements**: Uses OpenAI API to generate code based on prompts and integrate it into Rust projects.
  
## Prerequisites

- Rust installed on your machine.
- OpenAI API credentials.

### Create .env

```shell
touch .env
```

Within the .env file created, paste the following:

```plaintext
OPEN_AI_ORG=YOUR_OPEN_AI_ORG_ID
OPEN_AI_KEY=YOUR_OPEN_AI_KEY
```

### Update Paths

Update constants in the src/helpers/general path.

These should match where you have your web_template project saved. Recommend to save your web_template in the same
folder as this project.

Web template project: https://github.com/coderaidershaun/rust-web-server-template.git

These should link to a code template which you want your web server to use and the main.rs file where it will attempt to execute new code it writes.

### Build Project

```shell
cargo build
```

### Run Project

```shell
cargo run
```
