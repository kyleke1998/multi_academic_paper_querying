# multi_academic_paper_querying
Python CLI that takes in PDF inputs of academic papers and either:
1. Returns generic summarization
2. Custmoized query results



## To run the python cli
1. `git clone repo url`
2. `pip install pipenv`
3. `pipenv sync`
4. `python3 summarize_multiple_pdf.py -f -d -p` where
   
-f specifies the string: "custom_summary" or "flexible_querying"

-d specifies the directory with all the PDFs of interest

-p filepath to the input prompt .txt file
