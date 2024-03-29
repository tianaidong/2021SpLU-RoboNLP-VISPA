

# Visually grounded follow-up questions: a dataset of spatial questions which require dialogue history
This is the repository of the dataset VISPA, which is introduced in the [paper link]. The dataset is built upon the GuessWhat?! ([de Vries etal.2017](https://arxiv.org/abs/1611.08481)), with the goal of collecting history-dependent spatial questions. 

# Abstract 
In this paper, we define and evaluate a methodology for extracting history-dependent spatial questions from visual dialogues. We say that a question is history-dependent if it requires (parts of) their dialogue history to be interpreted. We argue that some kinds of visual questions define a context upon which a follow-up spatial question relies. We call the question that restricts the context: trigger, and we call the spatial question that requires the trigger question to be answered: zoomer. We automatically extract different trigger and zoomer pairs based on the visual property that the questions rely on (e.g. color, number). We manually annotate the automatically extracted trigger and zoomer pairs to verify which zoomers require their trigger. We implement a simple baseline architecture based on a SOTA multimodal encoder. It leaves much room for
improvement for answering history-dependent questions

# Dataset 
The dataset contains different trigger and zoomer question pairs based on the visual property that the questions rely on (e.g. color, number), which are automatically extracted from the GuessWhat?! games. It also contains manually filtered questions from the automatically extracted trigger and zoomer question pairs. Each example is verified by two annotators.

Here is one example taken from our manually filtered dataset: <img src="/example/plane_example.PNG" width="800" height="400">

0. Is it a plane? (Yes)

1. One of the 3 planes in front? (Yes)  'Trigger' Question

2. Is it the one in the middle? (Yes) 'Zoomer' Question

The ids of zoomer questions are provided in the format: Game_id _ Postion (eg. the above example is 85113_2). 
# Contact
For any comments or questions, please email [Dota](mailto:dongtianaimit@gmail.com) or [Raffaella](mailto:bernardi@disi.unitn.it) :)
