# SCT_PE_3
# Task 03 - Prompting for Task Automation

## Objective
Use prompting to semi-automate real-world tasks such as summarizing, extracting structured data, or transforming formats.

---

## Prompt
"Convert the following bullet points into JSON format with keys 'task' and 'priority'. Ensure the output is valid JSON."

---

## Input-Output Examples

### Example 1
**Input:**  
- Buy groceries (High)  
- Finish homework (Medium)  
- Call mom (High)  

**Output:**  
```json
[
  {"task": "Buy groceries", "priority": "High"},
  {"task": "Finish homework", "priority": "Medium"},
  {"task": "Call mom", "priority": "High"}
]
