# 14o-ml-meetup-poa

Repository containing presentation + code for my talk in the [14º Machine Learning Meetup](https://github.com/jayme-anchante/14o-ml-meetup-poa)

## abstract

 - Jayme Anchante

Title: Artificial intelligence and data science in the JavaScript ecosystem  
By: Jayme Anchante  
Description: Have you ever participed in a project involving machine learning and are you curious about the behind the scenes? You have already participated in a few, but you have interest about discussing the theme? I will cover some learnings about the machine learning projects I was involved and share some details about a real case or show some livecoding about a case that could be real

## resumo

Título: Learnings and insights from 10 Machine Learning projetct  
Por: Jayme Anchante  
Descrição: Nunca participou de um projeto envolvendo machine learning e tem curiosidade em saber os bastidores? Já participou de alguns, mas tem interesse em discutir o tema? Vou abordar alguns aprendizados que tive em projetos de Machine Learning e compartilhar mais detalhes de um case real ou mostrar um livecoding de um caso que poderia ser real

# presentation

In order to compile the presentation you need [sent](https://tools.suckless.org/sent/). Please make sure you have all dependencies installed in your system, then:

```
mkdir -p sent &&
cd sent &&
wget https://dl.suckless.org/tools/sent-1.tar.gz &&
tar -xvzf sent-1.tar.gz &&
make &&
sudo make install &&
cd .. &&
rm -r sent &&
sent presentation
```

# case

The [Restaurant & consumer data Data Set](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data) is a dataset which comprises of 138 instances and 47 attributes across 9 files. The original task is to generate a top-n list of restaurants according to the consumer preferences. We are going to explore it a bit and make a recommendation based on an open business question. The code is hosted [here](https://github.com/jayme-anchante/restaurant-consumer-dataset-project)
