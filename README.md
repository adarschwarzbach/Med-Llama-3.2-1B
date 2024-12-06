# Medical Llama Fine-Tuning on Google Colab Pro+

Jupyter Notebook for fine-tuning and benchmarking the Llama model with medical datasets, leveraging several fine tuning technique (LoRA, BOFT, etc.)  Google Colab Pro+ and GPU acceleration.

---

## **Model Performance on Test Data**

| **Configuration**        | **Perplexity** | **Next-token Accuracy** |
|---------------------------|----------------|--------------------------|
| **Base Model**            | 6.110          | 0.591                   |
| **Re-training Final Layer** | **2.960**      | **0.733** (Best Model)  |
| **LoRA (PEFT)**           | 3.252          | 0.715                   |
| **BOFT (PEFT)**           | 4.623          | 0.643                   |

### **🏆 Best Model: Re-training Final Layer**  
- **Perplexity**: 2.960  
- **Next-token Accuracy**: 0.733  

---

## **Features**
- Fine-tune Llama specifically for **medical datasets**.
- Full GPU support for fast and efficient training.
- Real-time performance monitoring and visualizations of metrics like perplexity and accuracy.

---

## **Setup Instructions**

1. **Open the Notebook**  
   - Upload the `.ipynb` file to your Google Drive.  
   - Open it in Google Colab by selecting "Open With > Google Colab."

2. **Set Runtime**  
   - Go to `Runtime > Change runtime type`.  
   - Select **GPU** (recommended: **A100**, as of Dec. 2024).  

3. **Install Dependencies**  
   - Follow the setup cells in the notebook to install required libraries.  

4. **Upload Dataset**  
   - Mount your Google Drive or upload datasets directly to Colab.  

---

## **Resources**
- [Meta Llama](https://www.llama.com/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Google Colab](https://colab.research.google.com)
