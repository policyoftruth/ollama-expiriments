# Ollama on WSL2/Win11

The intent of this repository is for expirimentation with the tool Ollama. 
The best description that I have heard is that it is equivalent to the Docker but for AI.

### **Notes**
* General instructions are located in the project's official [README.md](https://github.com/ollama/ollama/blob/main/README.md).
* I installed using the provided tools script. Yes, I know it is a bit sketch security-wise but YMMV. Review [*the code*](https://ollama.com/install.sh) before you execute it.
    * `curl -fsSL https://ollama.com/install.sh | sh`
* AVX2 and GPU support [*works*](./images/ollama-screen-capability.png) in my WSL2/Ubuntu 20.04 install on Windows 11 as represented by the output on an `ollama serve` command.
* I am running an older Nvidia 2080 Super w/8GB and a AMD Ryzen 5600X
* I use VScode with the SSH extension to connect to my WSL2 instance of Ubuntu
* My basic op is to run `ollama serve` in one terminal and the functional `ollama` commands in another. 
* Easy to use model lists for ollama are [here](https://ollama.com/library). Make sure to click on each one to check out the variants or you may pull a default you don't want

### **Resources**
* <https://huggingface.co/spaces/mike-ravkine/can-ai-code-results>

### **Examples**
* codellama:13b - "You are an expert programmer that writes simple, concise code and explanations. Write a bash script to generate the nth fibonacci number"