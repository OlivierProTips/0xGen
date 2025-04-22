# 0xGen

0xGen is a simple web-based toolset designed for penetration testers and security enthusiasts.  
It features several command generators and hash utilities with a hacking-inspired interface.

## Features

- **Hydra Command Generator:**  
  Easily build complex `hydra` commands for HTTP POST brute-force attacks using a user-friendly form.
- **Hashcat Command Generator:**  
  Quickly generate `hashcat` commands for various attack modes and hash types.
- **Hash Identifier:**  
  Instantly identify the type of a hash (MD5, SHA1, SHA256, etc.) as you type.
- **Dynamic Forms:**  
  Choose between single values or file lists for usernames, passwords, wordlists, and masks.
- **Live Command Preview:**  
  The command updates automatically as you fill out the form.
- **Copy to Clipboard:**  
  Instantly copy the generated command with a single click.
- **Hacker Style UI:**  
  Dark theme, green monospace text, and terminal-inspired visuals.

## Usage

1. Open `index.html` in your browser.
2. Click on one of the tools to access:
    - **Hydra http-post-form**
    - **Hashcat**
    - **Hash Identifier**
3. Fill in the required fields for the selected tool.
4. The command or result is generated automatically.
5. Click **Copy** (where available) to copy the command to your clipboard.

## Requirements

- Modern web browser (no backend required)
- [Hydra](https://github.com/vanhauser-thc/thc-hydra) installed on your system to use the generated Hydra command
- [Hashcat](https://github.com/hashcat/hashcat) installed on your system to use the generated Hashcat command

## Preview

![hydra-screenshot](/images/hydra-screenshot.png)  
![hashcat-screenshot](/images/hashcat-screenshot.png)  
![hash-identifier-screenshot](/images/hash-identifier-screenshot.png)  

## License

MIT License
