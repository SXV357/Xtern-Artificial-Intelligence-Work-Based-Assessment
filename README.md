# Xtern-Artificial-Intelligence-Work-Based-Assessment

My submission for the Xtern 2024 AI work-based assessment. My work is in `FoodX.ipynb`, and the trained model is saved as `knn.pkl`. The original prompt is below.

## Situation

Given the launch of our food truck line, FoodX, we will be running an exciting and interactive promotion on college campuses to attract a massive initial student following.  When placing their order on our fancy new FoodX app they input basic information about their college experience and we predict what they are going to order.  If we don’t get it right they get a 10% discount.

While the promotion has done a great job of bringing in business our staff has not been great at guessing orders and are not happy with the combined workload of guessing and cooking.

Because of this you have been asked to consider implications, solutions and deployment of a mechanism to automatically guess orders, sounds like the perfect job for AI!

### Part 1(25%)  
Given the data set, do a quick exploratory data analysis to get a feel for the distributions and biases of the data.  Report any visualizations and findings used and suggest any other impactful business use cases for that data.

### Part 2(30%)
Consider implications of data collection, storage, and data biases you would consider relevant here considering Data Ethics, Business Outcomes, and Technical Implications
  1. Discuss Ethical implications of these factors
  2. Discuss Business outcome implications of these factors
  3. Discuss Technical implications of these factors

### Part 3(35%)
Build a model to predict a customers order from their available information.  You will be graded largely on your intent and process when designing the model, performance is secondary. It is strongly suggested that you use SKLearn for this model as to not take too much time.  You may use any kind implementation you would like though, but it must be pickelable and have a “.predict()” method similar to SKLearn
  1. Outline your process for model selection, training and testing. Including data preparation.
  2. Design a function that prepares your data by loading the provided dataset and processes it into an appropriate machine readable format if necessary.
  3. Design a function to train your model and pickle it.
  4. Train and test your model.  Submit any training, testing and model selection visuals or metrics.
  5. Upload your work to GitHub and link the repository, make sure it is public.

### Part 4(10%)
Given the work required to bring a solution like this to maturity and its performance, what considerations would you make to determine if this is a suitable course of action?
