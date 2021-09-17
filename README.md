<img align="right" width="350px" src="https://media2.giphy.com/media/7c8QeB0VMddFOuu4iR/giphy.gif?cid=ecf05e47moacnihxnkdk6n5c4u4c5re9p5gehrjne0e6kvsn&rid=giphy.gif&ct=g">
<!-- ![](https://media2.giphy.com/media/7c8QeB0VMddFOuu4iR/giphy.gif?cid=ecf05e47moacnihxnkdk6n5c4u4c5re9p5gehrjne0e6kvsn&rid=giphy.gif&ct=g) -->

### Hi there 👋

- 🔭 I’m currently working on API Economy, Blockchain, Quantum technologies and more..
- 🌱 Currently working for home + Freelancing in Data Science, Data Analytics, Python, Web development etc.
- 🤔 Also developing "UEF Aerial Plantation detector" for my Final Year Project
- 💬 Ask me about Artificial Intelligence, API Economy, Web development
- 📫 How to reach me: wajid.linux99@gmail.com || [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/ssr-1998)  [<img src='https://image.flaticon.com/icons/png/512/174/174857.png' alt='linkedin' height='40'>](https://www.linkedin.com/in/linkedin.com/in/shubham-singh-rana-225744138/)  [<img src='https://image.flaticon.com/icons/png/512/187/187190.png' alt='skype' height='40'>](https://join.skype.com/invite/xlFLd4fGjK2l)  

- 😄 Pronouns: He/His
- ⚡ Fun fact: Size matters, but bigger isn't always better!(Talking about Neural Networks)

<img src="https://github-readme-stats.vercel.app/api?username=AbdulWajid99&&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=191919">


<!--Having selected an architecture one must then decide how large or small the neural network should be. How many inputs are there? How many hidden neurons should be used? How many hidden layers should be used (if we are using a deep neural network)? And how many outputs neurons are required? The reasons why these questions are important is because if the neural network is too large (too small) the neural network could potentially overfit (underfit) the data meaning that the network would not generalize well out of sample.

<!--HOW MANY AND WHICH INPUTS SHOULD BE USED?
The number of inputs depends on the problem being solved, the quantity and quality of available data, and perhaps some creativity. Inputs are simply variables which we believe have some predictive power over the dependent variable being predicted. If the inputs to a problem are unclear, you can systematically determine which variables should be included by looking at the correlations and cross-correlation between potential independent variables and the dependent variables. This approach is detailed in the article, What Drives Real GDP Growth?

<!--There are two problems with using correlations to select input variables. Firstly, if you are using a linear correlation metric you may inadvertently exclude useful variables. Secondly, two relatively uncorrelated variables could potentially be combined to produce a strongly correlated variable. If you look at the variables in isolation you may miss this opportunity. To overcome the second problem you could use principal component analysis to extract useful eigenvectors (linear combinations of the variables) as inputs. That said a problem with this is that the eigenvectors may not generalize well and they also assume the distributions of input patterns is stationary.

<!--Another problem when selecting variables is multicollinearity. Multicollinearity is when two or more of the independent variables being fed into the model are highly correlated. In the context of regression models this may cause regression co-efficients to change erratically in response to small changes in the model or the data. Given that neural networks and regression models are similar I suspect this is also a problem for neural networks.

<!--Last, but not least, one statistical bias which may be introduced when selecting variables is omitted-variable bias. Omitted variable bias occurs when a model is created which leaves out one or more important causal variables. The bias is created when the model incorrectly compensates for the missing variable by over or underestimating the effect of one of the other variables i.e. the weights may become too large on these variables or SSE will be large. 

<!--HOW MANY HIDDEN NEURONS SHOULD I USE?
The optimal number of hidden units is problem specific. That said, as a general rule of thumb the more hidden units used the more probable the risk of overfitting becomes. Overfitting is when the neural network does not learn the underlying statistical properties of the data, but rather 'memorizes' the patterns and any noise they may contain. This results in neural networks which perform well in sample but poorly out of sample. So how can we avoid overfitting? There are two popular approaches used in industry namely early stopping and regularization and then there is my personal favourite approach, global search,

<!--Early stopping involves splitting your training set into the main training set and a validation set. Then instead of training a neural network for a fixed number of iterations, you train then until the performance of the neural network on the validation set begins to deteriorate. Essentially this prevents the neural network from using all of the available parameters and limits it's ability to simply memorize every pattern it sees. The image on the right shows two potential stopping points for the neural network (a and b).

<!--Early Stopping

<!--The image below shows the performance and over-fitting of the neural network when stopped at a or b,
Early Stopping II

<!--Regularization penalizes the neural network for using complex architectures. Complexity in this approach is measured by the size of the neural network weights. Regularization is done by adding a term to sum squared error objective function which depends on the size of the weights. This is the equivalent of adding a prior which essentially makes the neural network believe that the function it is approximating is smooth,


<!--where  is the number of weights in the neural network. The parameters  and  control the degree to which the neural network over or underfits the data. Good values for  and  can be derived using Bayesian analysis and optimization. This, and the above, are explained in considerably more detail in this brilliant chapter.

<!--Neural Network Regularization

<!--My favourite technique, which is also by far the most computationally expensive, is global search. In this approach a search algorithm is used to try different neural network architectures and arrive at a near optimal choice. This is most often done using genetic algorithms which are discussed further on in this article.


<!--WHAT ARE THE OUTPUTS?
Neural networks can be used for either regression or classification. Under regression model a single value is outputted which may be mapped to a set of real numbers meaning that only one output neuron is required. Under classification model an output neuron is required for each potentially class to which the pattern may belong. If the classes are unknown unsupervised neural network techniques such as self organizing maps should be used.

<!--In conclusion, the best approach is to follow Ockhams Razor. Ockham's razor argues that for two models of equivalent performance, the model with fewer free parameters will generalize better. On the other hand, one should never opt for an overly simplistic model at the cost of performance. Similarly, one should not assume that just because a neural network has more hidden neurons and maybe more hidden layers it will outperform a much simpler network. Unfortunately it seems to me that too much emphasis is placed on large networks and too little emphasis is placed on making good design decisions. In the case of neural networks, bigger isn't always better. 

