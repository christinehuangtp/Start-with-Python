# Start with Python
### Find interesting CSV datasets.

#### Here are some dataset source:

. Kaggle datasets: https://www.kaggle.com/datasets 

. UCI datasets: https://archive.ics.uci.edu/ml/datasets.php?format=&task=&att=&area=bus&numAtt=10to100&numIns=&type=&sort=dateUp&view=list 

. Legal datasets: https://lionbridge.ai/datasets/10-best-legal-datasets-for-machine-learning/ 


#### Load the dataset into a dataframe.
. Migration Animal Dataset
. Fatal Crime Dataset
. Online News Popularion Dataset

import pandas as pd
data = pd.read_csv("filename.csv", encoding = 'unicode_swcape")

#### Display the data.
####data.head(5)
####data.columns
####data.columns = ['AA','BB','CC'...] (rename)
####data.describe()
####data.AA.describe()

#### Display simple statistics of the data.

#### Display histograms graph. 
%matplotlib inline
histogram = airline.hist('AAincidents_85_99')
