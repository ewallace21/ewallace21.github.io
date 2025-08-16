---
title: "Journey Into Vanem"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---
# *Journey Into Vanem* — A Co-op Platformer on FPGA

Over the course of four weeks, Aaron Kanefsky and I developed *Journey Into Vanem*, a 2D cooperative platformer built entirely on the **DE1-SoC FPGA development board**. Inspired by the classic *Fireboy and Watergirl*, the game features two unique characters, real-time animation, and a Dungeons & Dragons–themed world—all optimized to run within the space and speed constraints of FPGA hardware.

## Key Features

* Fully asynchronous two-player gameplay with independent controls  
* Real-time animations and responsive input handling  
* Custom graphics pipeline using MIF ROMs and 16-bit color optimization  
* Finite state machines (FSMs) for screen transitions and gameplay logic  
* Collision detection, sprite-based animation, and a complete gameplay loop  
* Custom hardware input via GPIO and on-board switches  
* VGA output with modular SystemVerilog architecture  

## Technical Implementation

We worked hands-on with low-level hardware design to build a complete game from the ground up, using:

* **M10K RAM blocks** for video and state data  
* **GPIO interfaces** for external controls  
* **Python and Pillow** for generating ROM-encoded sprite graphics  
* **Modular SystemVerilog** for FSMs, rendering logic, and hardware interfacing  

The design process involved developing a layered rendering system, sprite sheet management, and efficient state transitions, all under tight timing and memory constraints.

## Challenges and Outcomes

This project went beyond coding—it tested our ability to:

* Engineer a playable system within strict memory and performance limits  
* Design modular hardware logic for maintainability and scalability  
* Collaborate effectively in a fast-paced, high-pressure environment  

While we had to make trade-offs due to time and resource limitations, *Journey Into Vanem* gave us practical experience at the intersection of hardware design, embedded systems, and game development. With additional development time, future improvements could include smoother jump mechanics, animated enemies, and character selection functionality.

---

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen></iframe>

