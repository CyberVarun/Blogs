+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true

tags = [
"linux", "ubuntu", "cybersecurity","github", "IoT",
"git", "nvim", "vim", "neovim", "python", "python3", 
"IoT hacking", "MQTT", "CoAP", "IDA", "Ghidra",
"Binary Analysis", "Binary Reverse Engineering",
"Reverse Engineering", "Tool", "config", "JTAG",
"UART", "SPI", "I2C", "Firmware", "Firmware Analysis",
"Hardware", "Hardware hacking", "Hardware Analysis",
"Hardware Hacking", "Hardware Hacking Tool"] 

summary = "summary"
description = "desc (150-160 char)"
canonicalURL = "https://cybervarun.pages.dev/{{ .Dir }}" 

[cover] 
image = "img" 
alt = "text"
caption = "cap" 
relative = false

[editPost]
URL = "https://github.com/CyberVarun/Blogs"
Text = "Suggest Changes"
appendFilePath = true
+++
