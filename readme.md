

dotnet new console

dotnet add package LLamaSharp   
dotnet add package LLamaSharp.Backend.Cpu

dotnet add package Microsoft.KernelMemory.Core
dotnet add package LLamaSharp.kernel-memory

curl -L -O "https://huggingface.co/lmstudio-community/Meta-Llama-3-8B-Instruct-GGUF/resolve/main/Meta-Llama-3-8B-Instruct-Q8_0.gguf?download=true"

curl -L -O "https://huggingface.co/lmstudio-community/Meta-Llama-3-8B-Instruct-GGUF/resolve/main/Meta-Llama-3-8B-Instruct-Q4_K_M.gguf?download=true"