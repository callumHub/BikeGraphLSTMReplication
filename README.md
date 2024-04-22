## Working Version of Chai et al. Bike flow prediction with GNNs
https://github.com/Di-Chai/GraphCNN-Bike/ had missing data for many years. 
This project has recovered suitable data to replicate their experiment.
Recovery process documented at https://github.com/Di-Chai/GraphCNN-Bike/issues 

#### TO RUN
0. Download the recovered data from: 
1. To run, first must preprocess all of the data following directions in 
the PrepareData Directory. 
2. Next, change what model script you will run in Main.py 
3. After setting up a python venv. Set the number of jobs in Main.py to your CPU count. 
4. python Main.py 
(5.) You'll want to run this in the background: 
```
nohup python Main.py >> output_file.txt 2>&1 &

```
