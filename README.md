### Learning a Mathematical Function through Reinforcement Learning


Agent learns the function target = sin(x − 3) cos(y) + N(0, 0.1), where N is randomly destributed with mean = 0 and standard dev = 0.1

<img width="885" alt="screen shot 2018-05-13 at 8 09 20 pm" src="https://user-images.githubusercontent.com/6922982/39976621-9e4598a4-56e9-11e8-9360-cfba7a5a5a96.png">


<img width="640" alt="screen shot 2018-05-13 at 8 11 03 pm" src="https://user-images.githubusercontent.com/6922982/39976667-ceb378da-56e9-11e8-8521-e040edb6ec5d.png">

### Requirements:
```
python 2.7
conda install matplotlib
```

### Installing Requirements:
```
conda create --name python27 python=2.7
source activate python27
conda install matplotlib
```

### Usage:
```
python SuperLearn.py
```
should output f10000

### Plotting:
```
python2 plot.py f10000
```


This is an assignment from a class on Reinforcement Learning, taught by Richard Sutton, the father of Reinforcement Learning
