+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true

tags = [
"Linux", "Ubuntu", "Cybersecurity","Github", "IoT",
"Git", "Nvim", "Vim", "Neovim", "Python", "Python3", 
"IoT hacking", "MQTT", "CoAP", "IDA", "Ghidra",
"Binary Analysis", "Binary Reverse Engineering",
"Reverse Engineering", "Tool", "Config", "JTAG",
"UART", "SPI", "I2C", "Firmware", "Firmware Analysis",
"Hardware", "Hardware hacking", "Hardware Analysis",
"Hardware Hacking Tool"] 

summary = "summary"
description = "desc (150-160 char)"
canonicalURL = "https://cybervarun.pages.dev/{{ .Dir }}" 

[cover] 
image = "img" 
alt = "text"
caption = "cap" 
relative = false

[editPost]
URL = "https://github.com/CyberVarun/Blogs/content"
Text = "Suggest Changes"
appendFilePath = true
+++
