# 🌌 Nebula

**Nebula** is an ambitious project aiming to build a global decentralized platform.  
This repository acts as the central hub for the entire Nebula ecosystem, which will be composed of several independent modules working together to form an open, resilient, and user-owned network.  
The project is still in its early stages, and each component will be developed progressively.

---

## 🧩 Core Components

### **Kadnet — Decentralized networking layer**  
👉 https://github.com/enzoblain/Kadnet

Kadnet will serve as the networking foundation of Nebula.  
It is planned to become a peer-to-peer communication system based on the Kademlia protocol, enabling decentralized routing, peer discovery, and secure data exchange without relying on any central server.  
This module is currently in active development.

---

### **CosmaDB — Distributed storage engine**  
👉 https://github.com/enzoblain/CosmaDB

CosmaDB is intended to be Nebula’s decentralized database system.  
It will eventually provide a distributed storage architecture where data remains under user control, with a design based on B-Trees and other scalable indexing structures.  
Work on this component has not yet started.

---

### **NebulisChain — Economic & governance layer**  
👉 https://github.com/enzoblain/NebulisChain

NebulisChain will define Nebula’s blockchain layer, introducing the network’s economic model, governance rules, and token incentives.  
The long-term goal is to support a hybrid consensus mechanism and a decentralized governance model that rewards contributors and secures the ecosystem.  
This module is planned but not yet implemented.

---

### **App store — Decentralized application platform**  
👉 https://github.com/enzoblain/AppStore

The Playstore will act as Nebula’s decentralized application distribution system.
It will host only applications built specifically for the Nebula ecosystem, ensuring full compatibility with its decentralized networking, storage, and blockchain layers.
All apps published in the Playstore will be open-source, privacy-respecting, and verified to meet Nebula’s transparency and security standards.
The goal is to create a trustworthy environment where users can discover and install applications without intermediaries, relying entirely on Nebula’s decentralized infrastructure.
This component is still conceptual and will be developed once the core modules are in place.

### **Starship — Decentralized web browser**  
👉 https://github.com/enzoblain/Starship

Starship is planned to become Nebula’s dedicated web browser — similar to a traditional browser like Chrome, but fully adapted to the Nebula ecosystem.
It will allow users to access decentralized applications and services natively, without depending on any centralized backend.
The browser will integrate directly with Kadnet, CosmaDB, and NebulisChain so that identity, storage, and transactions work seamlessly inside the browsing experience.
Starship is still in the conceptual stage and will grow alongside the rest of the Nebula ecosystem.

---

## 🔧 Utility Crates & Supporting Libraries

### **Cryptography**  
👉 https://github.com/enzoblain/cryptography

The `cryptography` crate provides essential low-level utilities that will be reused across different Nebula modules.  
It currently offers implementations such as SHA-256 and U256, and will expand over time as more cryptographic primitives become necessary.  
Although useful across the ecosystem, it is not considered a core component of Nebula.

---

### **Reactor**  
👉 https://github.com/enzoblain/Reactor

The `Reactor` crate is a lightweight, predictable task runner designed for Nebula's asynchronous and multi-threaded operations.  
It provides fundamental building blocks to schedule, drive, and monitor units of work with flexible support for both synchronous and asynchronous primitives, as well as concurrent multi-threaded execution.  
This library enables efficient task management and execution across Nebula's distributed components.

---

## 🚀 Vision

Nebula aims to evolve into a modular, open, and decentralized ecosystem where each part remains independent yet interoperable.  
The project is still at the foundational stage, and the components listed here represent long-term goals rather than finished systems.  
As development progresses, Nebula will move toward becoming a fully decentralized alternative to traditional digital platforms.