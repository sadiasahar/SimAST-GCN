# SimAST-GCN

![image](https://user-images.githubusercontent.com/93702668/147535219-77a55fc0-bb50-4466-9a9d-41c26fcb2ae6.png)


Attention! We modified the pipline.py, it didn't need large disk file. The graph generation is moved to the data_iter.py.

for the gensim module, please make sure that the version is < 4.00.

#### I noticed that the data had some problem. So I offer another link.
https://drive.google.com/file/d/1GFHZJQVztnk4XYkan7llEZDa-t_N2sQb/view?usp=sharing

I offer another dataset with text information, which is larger and less mistake, in another link.

https://github.com/SimAST-GCN/CLMN

---

### for SimAST-GCN, you can run the following commond.
1. python pipline.py
2. python SimAST-GCN.py

### for astnn, we recommend you to remove the files generated by the pipline.py. Then, do the following operation.
1. python ast_pipline.py
2. python astnn.py


### for dace, we all recommend you to remove the files generated by other files. Then, do the following operation.
1. python token_pre.py
2. python dace.py

### for tbrnn, we all recommend you to remove the files generated by other files. Then, do the following operation.
1. python tbrnn_pipeline.py
2. python tbrnn.py
