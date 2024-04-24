#Creating devcontainer and running Deep Learning on the CPU

IF you can avoid using the CPU, do so at all costs. I attempted running the given Jupyter Notebook 
on my personal laptop which dosent have a discrete GPU unit. I was in the middle of the library and 
it roared like an airplane engine because the whole system was overheating. 

Due to the multiple simultaneous calculations that are required for the deep learning algorithim in the 
"00-is-it-a-bird-creating-a-model-from-your-own-data" Jupyter Noteboook, a discrete GPU with multiple cores
capable of handling the multitude of calculations would be significantly better.

As of writing this blog post, I have not tested Q3 and Q4 with a GPU, but stay tuned for a future post to see 
what happens.
