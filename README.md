# tangrams

To make this work, use the following:
(base) km@MacBook-Pro-10.local:~/tangrams/experiments$ node app.js tangrams_sequential/
cannot find SSL certificates; falling back to http
info  - socket.io started
	 :: Express :: Listening on port 8888



http://IP:8888/tangrams_sequential/index.html?workerId=robbie



This repository contains the experiment, data, and analysis code for the paper "Characterizing the dynamics of learning in repeated reference games".

**Manuscript pre-print available on [ArXiv](https://arxiv.org/pdf/1912.07199)**

* *experiments* contains the code and materials for running repeated reference games as web experiments
* *data* contains the raw, anonymized data from the experiments as well as the pre-processed versions ([unconstrained](https://github.com/hawkrobe/tangrams/raw/master/data/tangramsUnconstrained.csv), [sequential](https://github.com/hawkrobe/tangrams/raw/master/data/tangramsSequential.csv))
* *analysis* contains the python and R code for producing all results and figures reported in the paper
* *writing* contains the TeX to generate the journal manuscript
