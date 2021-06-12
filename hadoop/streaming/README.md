With Hadoop 3.2.2 and python3, the following command works:

$ mapred streaming -input /shakespeare -output myMRoutput -file mapper.py -file reducer.py -mapper mapper.py -reducer reducer.py
