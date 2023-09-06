# Movie-Review-Classification-Using-Zero-Shot-Learning

This repository contains an implentation of movie review classification using ZSL. Here, the rotten_tomatoes dataset is being used for testing purposes. Since ZSL is being implemented, the training set is being used for testing the algorithm. 

The facebook/bart-large-mnli pretrained model is used to implement ZSL. The 2 labels used to test the algorithm is 'Good' and 'Bad'. If there is a higher likelihood of the review being 'Good' then the prediction is 1.0, else it is 0.0.

The training input data was tested against the output and gave a % error. 

# Citations

Rotten_Tomatoes Dataset

@InProceedings{Pang+Lee:05a,
  author =       {Bo Pang and Lillian Lee},
  title =        {Seeing stars: Exploiting class relationships for sentiment
                  categorization with respect to rating scales},
  booktitle =    {Proceedings of the ACL},
  year =         2005
}
