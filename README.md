# NeuralNetworkChain.sol
Neural Network Chain solidity contract
# NeuralNetworkChain.sol 🧠⚡

**NeuralNetworkChain** is a Solidity-based smart contract designed to simulate **neural connections** for AI-driven **neuroplasticity research**. This contract is a key component of **Eternum**, the Biological Blockchain.

## **📌 Project Overview**
- **Name:** NeuralNetworkChain
- **Language:** Solidity (`^0.8.19`)
- **Purpose:** Simulates decentralized neural network activity for **AI learning** and **neuroplasticity research**.
- **License:** Creative Commons BY-ND 4.0 *(Minimal Open Source - No Derivatives Allowed)*

---

## **🚀 Features**
✅ **Decentralized Neural Network Simulation**  
✅ **Neuron Creation & Synaptic Connection Mapping**  
✅ **AI-Driven Activation Events**  

---

## **📂 Smart Contract Structure**
The contract is structured as follows:

### **🧬 Neuron Struct**
Each neuron consists of:
- **`id`** – Unique identifier  
- **`owner`** – Creator of the neuron  
- **`activationThreshold`** – Minimum activation requirement  
- **`connectionCount`** – Number of connected neurons  
- **`synapticWeights`** – Mapped connections with weighted values  

### **🔗 Core Functions**
- `createNeuron(uint256 _activationThreshold)` → Creates a new neuron.  
- `connectNeurons(uint256 fromNeuron, uint256 toNeuron, uint256 weight)` → Establishes a synaptic connection.  
- `activateNeuron(uint256 neuronId, uint256 intensity)` → Simulates neuron firing.  

---

## **🛠 Compilation & Deployment**
### **1️⃣ Install Dependencies**
```sh
npm install
