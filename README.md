# 2019版的cs224n比2017版的多了哪些内容？
---
**What is this course about?**

Natural language processing (NLP) is one of the most important technologies of the information age, and a crucial part of artificial intelligence. Applications of NLP are everywhere because people communicate almost everything in language: web search, advertising, emails, customer service, language translation, medical reports, etc. In recent years, Deep Learning approaches have obtained very high performance across many different NLP tasks, using single end-to-end neural models that do not require traditional, task-specific feature engineering. In this course, students will gain a thorough introduction to cutting-edge research in Deep Learning for NLP. Through lectures, assignments and a final project, students will learn the necessary skills to design, implement, and understand their own neural network models. This year, CS224n will be taught for the first time using PyTorch rather than TensorFlow (as in previous years).

17年课程安排：https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1174/syllabus.html

17课程视频：https://www.bilibili.com/video/av28030942?from=search&seid=1487880710084069013

19年课程安排：http://web.stanford.edu/class/cs224n/

19年课程视频：[bilibili](https://www.bilibili.com/video/av47113620?from=search&seid=12367917153248364874) | [youtube](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=2&t=0s)


19版cs224n新增的内容包括：
character models, transformers, safety/fairness, multitask learn

---


| 19 课程安排 | 19 Description                                               | 17 Description                                            | 17 课程安排 |
| ----------- | ------------------------------------------------------------ | --------------------------------------------------------- | ----------- |
| 1           | Introduction and Word Vectors <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture01-wordvecs1.pdf)] [[notes](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes01-wordvecs1.pdf)] <br/>Gensim word vectors example: <br/>[[zip](http://web.stanford.edu/class/cs224n/materials/Gensim.zip)] [[preview](http://web.stanford.edu/class/cs224n/materials/Gensim word vector visualization.html)] | Introduction to NLP and Deep Learning                     | 1           |
| 1           | Word Vectors 2 and Word Senses <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture02-wordvecs2.pdf)] [[notes](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes02-wordvecs2.pdf)] | Word Vector Representations: word2vec                     | 1           |
| 2           | Word Window Classification, Neural Networks, and Matrix Calculus <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture03-neuralnets.pdf)] [[matrix calculus notes](http://web.stanford.edu/class/cs224n/readings/gradient-notes.pdf)] <br/>[[notes (lectures 3 and 4)](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes03-neuralnets.pdf)] | Advanced Word Vector Representations                      | 2           |
| 2           | Backpropagation and Computation Graphs <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture04-backprop.pdf)] <br/>[[notes (lectures 3 and 4)](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes03-neuralnets.pdf)] | Word Window Classification and Neural Networks            | 2           |
| 3           | Linguistic Structure: Dependency Parsing <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture05-dep-parsing.pdf)] <br/>[[scrawled-on slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture05-dep-parsing-scrawls.pdf)] <br/>[[notes](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes04-dependencyparsing.pdf)] | Backpropagation and Project Advice                        | 3           |
| 3           | The probability of a sentence? Recurrent Neural Networks and Language Models <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture06-rnnlm.pdf)] <br/>[[notes (lectures 6 and 7)](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes05-LM_RNN.pdf)] | Dependency Parsing                                        | 3           |
| 4           | Vanishing Gradients and Fancy RNNs <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture07-fancy-rnn.pdf)] [[notes (lectures 6 and 7)](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes05-LM_RNN.pdf)] | Introduction to TensorFlow                                | 4           |
| 4           | Machine Translation, Seq2Seq and Attention <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture08-nmt.pdf)] [[notes](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes06-NMT_seq2seq_attention.pdf)] | Recurrent Neural Networks and Language Models             | 4           |
| 5           | Practical Tips for Final Projects <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture09-final-projects.pdf)][[notes](http://web.stanford.edu/class/cs224n/readings/final-project-practical-tips.pdf)] | Machine translation and advanced recurrent LSTMs and GRUs | 5           |
| 5           | Question Answering and the Default Final Project<br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture10-QA.pdf)][[notes](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes07-QA.pdf)] | Midterm Review                                            | 5           |
| 6           | **ConvNets for NLP** <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture11-convnets.pdf)][[notes](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes08-CNN.pdf)] | Neural Machine Translation and Models with Attention      | 6           |
| 6           | **Information from parts of words: Subword Models** <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture12-subwords.pdf)] | Gated recurrent units and further topics in NMT           | 6           |
| 7           | **Modeling contexts of use: Contextual Representations and Pretraining** <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture13-contextual-representations.pdf)] | End-to-end models for Speech Processing                   | 7           |
| 7           | **Transformers and Self-Attention For Generative Models** <br/>*(guest lecture by Ashish Vaswani and Anna Huang)* <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture14-transformers.pdf)] | Convolutional Neural Networks                             | 7           |
| 8           | **Natural Language Generation** <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture15-nlg.pdf)] | Tree Recursive Neural Networks and Constituency Parsing   | 8           |
| 8           | Reference in Language and Coreference Resolution <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture16-coref.pdf)] | Coreference Resolution                                    | 8           |
| 9           | **Multitask Learning: A general model for NLP?** *(guest lecture by Richard Socher)* <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture17-multitask.pdf)] | Dynamic Neural Networks for Question Answering            | 9           |
| 9           | Constituency Parsing and Tree Recursive Neural Networks <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture18-TreeRNNs.pdf)][[notes](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes09-RecursiveNN_constituencyparsing.pdf)] | Issues in NLP and Possible Architectures for NLP          | 9           |
| 10          | Safety, Bias, and Fairness *(guest lecture by Margaret Mitchell)* <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture19-bias.pdf)] | Tackling the Limits of Deep Learning for NLP              | 10          |
| 10          | Future of NLP + Deep Learning <br/>[[slides](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture20-future.pdf)] |                                                           |             |

