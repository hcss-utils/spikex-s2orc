# spikex-s2orc 

First clone the repository (by running the following command in terminal):
```bash
$ git clone https://github.com/hcss-utils/spikex-s2orc.git
```

then run:

```bash
$ cd spikex-s2orc
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ python -m spacy download en_core_web_sm
```

Once you have your enviroment ready, put the source file into `data/raw` folder 
(we're not sharing the dataset publically). 

to start the notebook, run:

```bash
$ jupyter lab
```

and head over to `notebooks/` folder.