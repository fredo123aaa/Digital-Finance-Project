# **Digital Finance Project**

## **Authors**
- **Fredo Alejos Arrieta**  
- **Hachem Legha**

---

## **1. Project Overview**

This project, titled **"Digital Finance Project"**, explores the intersection of modern financial technologies and quantitative analysis of stock market data. It combines conceptual insights from emerging digital finance paradigms—such as **Blockchain**, **RegTech**, and **Algorithmic Trading**—with empirical analyses of French financial market data, specifically the **CAC 40 index** and selected constituent stocks.

The work aims to understand both **technological innovations in finance** and **data-driven insights into market behavior**, thus bridging qualitative and quantitative perspectives in financial research.

---

## **2. Objectives**

1. To identify and analyze key innovations shaping the digital finance landscape.  
2. To perform statistical and visual analysis of selected financial assets (e.g., CAP, BNPA, CAC 40).  
3. To evaluate return dynamics, volatility patterns, and potential signs of heteroskedasticity in financial time series.  
4. To link conceptual fintech trends with their potential applications in real-world financial data contexts.

---

## **3. Methodology**

### **3.1 Conceptual Analysis**
Three major digital finance innovations were reviewed:

- **Blockchain & Smart Contracts:**  
  Studied for their role in decentralizing financial services, enhancing transparency, and enabling digital identity management.

- **Regulatory Technology (RegTech):**  
  Investigated for its use of artificial intelligence and automation to improve compliance, risk management, and fraud detection.

- **Algorithmic Trading:**  
  Explored as a key trend in high-frequency and data-driven investment strategies, enhancing market efficiency and liquidity.

### **3.2 Quantitative Analysis**
Using financial data from the **CAC 40 Index** and selected French listed companies (e.g., CAP, BNPA), the study performs:

- **Data preprocessing and cleaning** of time series data  
- **Computation of returns and volatility**  
- **Exploratory visualization** (price evolution, volatility clustering)  
- **Assessment of statistical properties** such as homoskedasticity  

This analysis aims to detect general patterns in volatility and performance across sectors.

---

## **4. Data Description**

The data includes:

- Historical price series for **CAC 40 index**  
- Stock price data for individual firms (e.g., **CAP**, **BNPA**)  
- Time series spanning multiple years  

Data was sourced from publicly available databases or APIs (e.g., Yahoo Finance or Euronext).

---

## **5. Tools and Libraries**

The analysis was conducted in **Python**, using Jupyter Notebook.  
Main libraries:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- statsmodels  
- scipy  
- yfinance  

---

## **6. Results Summary**

- **Stock performance:**  
  Both CAP and BNPA showed a general decline over the observed period.

- **Volatility behavior:**  
  Returns appear largely **homoskedastic**, with minor variance peaks.  
  Volatility across the sample remains below approximately **2.1%**.

- **Comparative insights:**  
  Similar volatility patterns were observed between stocks and the CAC 40 index, suggesting broad market consistency.

---

## **7. Reproducibility**

To reproduce the results:

```bash
# Clone the repository
git clone https://github.com/fredo123aaa/Digital-Finance-Project.git

# Navigate to the project folder
cd Digital-Finance-Project

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook Digital_Finance_Project.ipynb
```

---

## **8. Discussion and Conclusion**

This project highlights the dual role of technological innovation and data analytics in shaping the future of finance.

While blockchain and RegTech redefine institutional processes, algorithmic trading underscores the growing importance of quantitative modeling in capital markets.

The results indicate that even traditional markets exhibit stable volatility structures that can be extended through advanced econometric modeling (e.g., GARCH).

---

## **9. References**

- Arner, D. W., Barberis, J., & Buckley, R. P. (2016). *The Evolution of Fintech: A New Post-Crisis Paradigm?*  
- Narayanan, A. et al. (2016). *Bitcoin and Cryptocurrency Technologies.* Princeton University Press.  
- Basel Committee on Banking Supervision. (2021). *Sound Practices: Implications of Fintech Developments for Banks and Bank Supervisors.*  
- Additional online and academic resources cited in the notebook.

---

## **10. Acknowledgements**

We acknowledge the guidance of our instructors and peers for their feedback and support throughout this academic project.
