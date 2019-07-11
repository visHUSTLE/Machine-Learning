# Machine-Learning

# Linear Regression

Linear regression can be thought of as the "hello world" of machine learning. It's relatively straigthforward to implement once you understand it, yet (unlike a simple "hello world" app) is powerful enough to have signficant use in industry. Let's take a look at the linear regression problem.

We have some (input, output) pairs which we denote as $ (x_i, y_i) $ and we have $n$ of these, so $i \in [1...n]$. We want to learn a function $f: x \rightarrow{} y$ that maps inputs to outputs.

Crucially, we want to learn the function $ f $ such that $ f $ generalizes well to unseen data. We can easily create a function $ f $ that always returns the correct answer on data we've seen before (data in our training set) - can you guess what that function would look like, and why it would be essentially worthless for data we haven't seen before?


# Dataset

We'll be using the Boston house prices dataset. This dataset has 500 training examples, each with 13 features describing various attributes of the home, and a target associated with the example, giving the value of the home in thousands of dollars.

Each of the 13 features denotes some quality or quantity regarding the house or the surrounding area. A few examples of the different features included in the dataset include the area's crime rate, the number of rooms in the house, the distance from the house to popular Boston locations, and the average student to teacher ratio in nearby schools.
