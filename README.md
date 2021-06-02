

# Visually grounded follow-up questions: a dataset of spatial questions which require dialogue history
This is the repository of the dataset VISPA, which is introduced in the [paper link]. The dataset is built upon the GuessWhat?! ([de Vries etal.2017](https://arxiv.org/abs/1611.08481)), with the goal of collecting history-dependent spatial questions. 

The dataset contains different trigger and zoomer question pairs based on the visual property that the questions rely on (e.g. color, number), which are automatically extracted from the GuessWhat?! games. It also contains manually filtered questions from the automatically extracted trigger and zoomer question pairs. Each example is verified by two annotators.

Here is one example taken from our manually filtered dataset: ![alt text](/example/plane_example.PNG)

0. Is it a plane? (Yes)

1. One of the 3 planes in front? (Yes)  'Trigger' Question

2. Is it the one in the middle? (Yes) 'Zoomer' Question

# Dataset 
The ids of zoomer question are provided in the format: Game_id _ Postion (eg. the above example is 85113_2). 
# Contact
For any comments or questions, please email [Dota](mailto:tianai.dong@studenti.unitn.it) :)
