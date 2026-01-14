<div align="center">

# Hi, I'm Dehao (sdh1014) 👋  
AI InferenceFramework • AI Compiler (MLIR/LLVM) • Embedded Development

</div>

## 📌 About Me
- I completed my **undergraduate studies** in Electronic Information Engineering at **CUG** and I’m currently pursuing a **master’s degree** in Electronic Information at **HUST**.
- My main technical interests and experience span **embedded development**, **AI compilers (MLIR)**, and **HPC**.
- Interested in **LLM inference systems** and **compute-graph compilation & optimization**.
- I’m currently diving deeper into **MLIR**, **LLM inference frameworks**, and **CUDA**.

---

## 📊 Stats

<div align="center">
  <img height="160" src="https://streak-stats.demolab.com?user=sdh1014&hide_border=true" />
  <img height="160" src="https://github-readme-stats-ten-rose.vercel.app/api?username=sdh1014&show_icons=true&hide_border=true&show=prs_merged,prs_merged_percentage,reviews&cache_seconds=86400" />
  <img height="160" src="https://github-readme-stats-ten-rose.vercel.app/api/top-langs/?username=sdh1014&layout=compact&hide_border=true&cache_seconds=86400" />
</div>

---

## 🧩 Work / Projects

### buddy-mlir
MLIR-based compiler framework bridging DSLs to DSAs.  
- Repo: https://github.com/sdh1014/buddy-mlir  
- **My work:**
  - Built a user-facing CLI tool on top of DeepSeek-R1-Distill-Qwen-1.5B inference (llama.cpp-style). Implemented context shift to prevent token overflow during the decode stage, and applied RoPE correction to recompute K vectors for the shifted segment.
  - Extended the Buddy-MLIR frontend to support 191 PyTorch Core ATen IR ops, and completed graph-level lowering from Core ATen ops to TOSA/Linalg-level IR. 

### OpenHarmony Device Code Generator (openRuyi)
Generates device source code from templates for faster OpenHarmony adaptation.  
- Repo: https://code.openruyi.cn/SongDehao/device_code_generator  
- **My work:**
  - Refactored the board/soc/vendor codebase by separating shared logic from customization layers, and introduced a processor mechanism to decouple components and handle variations in a modular way.
  - Implemented the generator’s orchestration logic in Python: used Jinja2 for rendering shared code from predefined common configuration items, and a patch-based workflow to apply device-specific customizations.
  - Adapted and validated the generator on dayu200 (RK3568) and OrangePi 5B (RK3588S), and delivered additional CLI tools for patch and defconfig management to streamline user development.

---

## 📫 Contact
- Email: songdehao1014@gmail.com
