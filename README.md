# Endogenized_Learning
The SEAMAPS model is a least-cost optimization model dedicated to anaylse future fuel mix, emissions and underlying cost of the maritime industry.
SEAMAPS runs in Julia. The Data-format is an excel document. The analysis of results works via an R-Markdown file.
This version of SEAMAPS is used to derive the impact of endogenous experience based learning

How to use it:
1. Install Julia and the following packages: JuMP, Gurobi, CSV, DataFrames, DelimitedFiles'
2. Install R & R-Studio
3. Download this repository to your local machine
4. Open the folder and go to /code - here open the file "SEAMAPS.jl"
5. Inside "SEAMAPS.jl" -Insert your local path to the SEAMAPS/data folder
6. Run SEAMAPS 
7. Analyse your results!

For further questions please contact semfr@dtu.dk
