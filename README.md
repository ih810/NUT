# Project Name  
Network Unit Transmitter (NUT)
![alt text](https://i.kym-cdn.com/entries/icons/facebook/000/020/383/nutbutton.jpg)  
## Description

NUT is a comprehensive network testing tool written in Python. It provides a variety of methods for testing network resilience and performance, including both Layer 4 and Layer 7 methods.  
  
## Usage  
```python3 start.py```  
## Features  
Proxy Management: The tool can handle a list of proxies, check their availability, and use them for network testing. It supports different types of proxies including SOCKS4, SOCKS5, and HTTP.  
User-Agent and Referer Management: The tool can read from a list of user-agents and referers, which can be used to simulate different types of web traffic.  
Layer 7 request sender: The tool supports various Layer 7 (Application Layer) methods. It can send HTTP flood request to a specified URL.  
Layer 4 request sender: The tool also supports various Layer 4 (Transport Layer) methods. It can send different types of packets to a specified host and port.  
Google Agents: The tool includes a list of Googlebot user-agents, which can be used to simulate traffic from Google's web crawler.  
Thread Management: The tool can run multiple threads concurrently for more effective network testing.  