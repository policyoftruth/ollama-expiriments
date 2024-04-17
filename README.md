# Ollama on WSL2/Win11

The intent of this repository is for expirimentation with the tool Ollama. 
The best description that I have heard is that it is equivalent to the Docker but for AI.

### **Notes**
* General instructions are located in the [INSTRUCTIONS.md](./INSTRUCTIONS.md) file which was pulled from the official repository for the tool.
* I installed using the provided tools script. Yes, I know it is a bit sketch security-wise but YMMV. Review [*the code*](https://ollama.com/install.sh) before your execute it.
    * `curl -fsSL https://ollama.com/install.sh | sh`
* AVX2 and GPU support [*works*](./images/ollama-screen-capability.png) in my WSL2/Ubuntu 20.04 install on Windows 11 as represented by the output on a `ollama serve` command.
