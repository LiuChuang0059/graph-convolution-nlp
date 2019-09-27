# Graph Convolution for NLP

Research project to apply Graph Convolution to NLP.

## Research

1. [Why & What is Graph Convolution](https://medium.com/programming-soda/graph-convolution%E3%82%92%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%81%AB%E5%BF%9C%E7%94%A8%E3%81%99%E3%82%8B-part1-b792d53c4c18)
2. [Implementation of Graph Convolution: Graph Attention Network](https://medium.com/programming-soda/graph-convolution%E3%82%92%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%81%AB%E5%BF%9C%E7%94%A8%E3%81%99%E3%82%8B-part2-dd0f9bc25dd3)
3. [Kinds of task in Graph](https://medium.com/programming-soda/graph-convolution%E3%82%92%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%81%AB%E5%BF%9C%E7%94%A8%E3%81%99%E3%82%8B-part3-12e7458f31fb)
4. [Case study to use Graph Convolution in NLP](https://medium.com/programming-soda/graph-convolution%E3%82%92%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%81%AB%E5%BF%9C%E7%94%A8%E3%81%99%E3%82%8B-part4-4b0082ce26da)
5. [Design of Experiment to verify effectiveness of Graph Convolution](https://medium.com/programming-soda/graph-convolution%E3%82%92%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%81%AB%E5%BF%9C%E7%94%A8%E3%81%99%E3%82%8B-part5-c833f01fde58)
6. [Rethink the property of Graph Convolution and find appropriate task in NLP](https://medium.com/programming-soda/graph-convolution%E3%82%92%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%81%AB%E5%BF%9C%E7%94%A8%E3%81%99%E3%82%8B-part6-f4596b2bcc93)
7. [Research summary of Graph Convolution in NLP](https://medium.com/programming-soda/graph-convolution%E3%82%92%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%81%AB%E5%BF%9C%E7%94%A8%E3%81%99%E3%82%8B-part7-end-3f6812ca08cf)

## Implementation

* [Language Modeling](https://medium.com/programming-soda/%E8%A8%80%E8%AA%9E%E3%83%A2%E3%83%87%E3%83%AB%E3%81%AE%E6%80%A7%E8%83%BD%E3%81%8C-%E5%AE%9F%E8%A3%85%E3%81%AB%E3%82%88%E3%82%8A%E7%95%B0%E3%81%AA%E3%82%8B%E4%BB%B6%E3%82%92%E8%A7%A3%E6%B1%BA%E3%81%99%E3%82%8B-5d36c841fcac)
* Graph Attention Network Layer
  * [Fix to support batch data](https://medium.com/programming-soda/graph-attention-network-layer%E3%82%92%E5%AE%9F%E8%A3%85%E3%81%99%E3%82%8B-part1-4a199372b3de)
  * [Experiment by existing dataset](https://medium.com/programming-soda/graph-attention-network-layer%E3%82%92%E5%AE%9F%E8%A3%85%E3%81%99%E3%82%8B-part1-4a199372b3de)
  * [What is really effective attention method on Graph?](https://medium.com/programming-soda/graph-attention-network-layer%E3%82%92%E5%AE%9F%E8%A3%85%E3%81%99%E3%82%8B-part3-ce3548c3aa5c)
* Graph Convolution for Text Classification
  * [Prepare the Dataset](https://medium.com/programming-soda/graph-convolution%E3%81%A7%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%82%92%E8%A1%8C%E3%81%86-%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E5%88%86%E9%A1%9E%E7%B7%A8-part1-3eacc11eb622)
  * [Make baseline model and analysis](https://medium.com/programming-soda/graph-convolution%E3%81%A7%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%82%92%E8%A1%8C%E3%81%86-%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E5%88%86%E9%A1%9E%E7%B7%A8-part2-b0f1f0a67b17)
  * [Make graph convolution model](https://medium.com/programming-soda/graph-convolution%E3%81%A7%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%82%92%E8%A1%8C%E3%81%86-%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E5%88%86%E9%A1%9E%E7%B7%A8-part3-b85acee1a3e8)
  * [Analyze graph convolution model](https://medium.com/programming-soda/graph-convolution%E3%81%A7%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%82%92%E8%A1%8C%E3%81%86-%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E5%88%86%E9%A1%9E%E7%B7%A8-part4-caee203b86af)
  * [Enhance graph convolution model](https://medium.com/programming-soda/graph-convolution%E3%81%A7%E8%87%AA%E7%84%B6%E8%A8%80%E8%AA%9E%E5%87%A6%E7%90%86%E3%82%92%E8%A1%8C%E3%81%86-%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E5%88%86%E9%A1%9E%E7%B7%A8-part5-end-cc9b0b4aac06)

## Paper Reading

* [How Powerful are Graph Neural Networks?](https://medium.com/programming-soda/graph-neural-network%E3%81%AE%E5%87%A6%E7%90%86%E3%81%A8%E5%8A%B9%E6%9E%9C%E3%82%92%E7%90%86%E8%A7%A3%E3%81%99%E3%82%8B-how-powerful-are-graph-neural-networks-a26ee9245cce)
