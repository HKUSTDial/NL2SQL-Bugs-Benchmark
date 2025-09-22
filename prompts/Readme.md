This folder contains the **prompts** and **schema organization format** used in the paper:  

> *NL2SQL-BUGs: A Benchmark for Detecting Semantic Errors in NL2SQL Translation*  

---

## 📂 Files

- **`prompt.txt`**  
  Contains the evaluation prompts we used in our experiments.  
  These prompts are fed into large language models (LLMs) to generate SQL queries for benchmark evaluation.  

- **`schema_dev.json`**  
  Contains the **database schemas** with additional annotations.  
  Each table includes an `enhanced_ddl` field that provides a **human-readable explanation** of table/column semantics.    
---

## ⚙️ Usage

1. **Prepare your environment**  
   - Any LLM API (e.g., GPT, Qwen, DeepSeek, etc.) can be used.   

2. **Feeding prompts**  
   - Load the content of `prompt.txt` as your query template.  
   - Replace placeholders with the actual NL query and schema etc.  

3. **Schema organization**  
   - Use `schema_dev.json` to provide schema context.  
   - Each database entry contains extended `enhanced_ddl`.  
   - Note: **enhanced_ddl** 

---

## 📬 Contact

If you have any questions or need further support, please feel free to reach out: xliu371[at]connect.hkust-gz.edu.cn.  
