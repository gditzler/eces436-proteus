# About 

This repo presents some of the basic functionality for using `Proteus` on [Drexel University's Research Computing Facility (UCRF)](http://www.drexel.edu/research/urcf/). Proteus uses the [Univa Grid Engine](http://www.univa.com/products/grid-engine) as the batch queuing system to submit and handle jobs. Before getting started, read through the [Proteus wiki](https://proteusmaster.urcf.drexel.edu/urcfwiki) for more information on using the batch queuing system. 

# SSHing into Proteus

Proteus has two head nodes that you can use for compting. Think of the nodes as being a computer or server. The two head nodes either use: (a) AMD, or (b) Intel processors. To connect to one of the head nodes, run the follwing commands in the shell. 

```bash
  # sshing into AMD servers 
  ssh $USERNAME@proteusa01.urcf.drexel.edu
  # sshing into Intel servers 
  ssh $USERNAME@proteusi01.urcf.drexel.edu
```
where `$USERNAME` is your username for proteus. Note that in the shell, the `$` is used to denote a variable. For example, if my username was `greg`, I could use something like: 

```bash 
  USERNAME=greg
  echo "My user name is $USERNAME" 
  ssh $USERNAME@proteusi01.urcf.drexel.edu
```


