## lesson1
~~~python

import torch
torch.cuda.is_available() #True
torch.backends.cudnn.enabled #True
import os
PATH=" "#your image root file path
os.listdir(PATH)
os.listdir(f'{PATH}valid'}
files=os.listdir(f'{PATH}valid/cats')[:5]
img=plt.imread(f'{PATH}valid/cats/{files[0]}')




~~~
