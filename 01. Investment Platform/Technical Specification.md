# Investment Platform Technical Specification

This document provides a technical specification for an investment platform.

# Requirements

Design a investment platform that provides support for clients across multiple platforms.

The platform must be able to store user infomation about their investments and provide insights into users investment habits.

Purchase orders for stocks and funds occur through a 3rd party API, as well as recieving relevant news about the stock.

The platform must be able to handle multiple users making different transactions and queries at once. (10000+ users making 3 requests per second)

A separate application for internal employees to look and query user insights would also be ideal.

# System Diagram

![Investment Platform Architectural Diagram](Diagram.png)

You can find an editable version of the diagram on [Excalidraw](https://excalidraw.com/#json=bUXhkgxY_6AZYC_wCA6aO,yZxxG8Z92gR2SQVgeO0Ubw)
