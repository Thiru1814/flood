# Flash flood Prediction

# To do list
https://mlhub.earth/10.34911/rdnt.ebk43x

python code to fatch dataset
------

from radiant_mlhub import Dataset

ds = Dataset.fetch('nasa_floods_v1')
for c in ds.collections:
    print(c.id)
    
-----

for other datasets (https://mlhub.earth/datasets)
