# Self Assessment

My role on the final project was primarily related to the machine learning aspect of the project. As such, I, researched which machine learning techniques would effectively address the question that we wanted to answer with the dataset. I chose to use a deep neural network model to determine the likelihood, given a set of parameters, that an individual would be injured in an accident. Together we determined the data fields that would be important to include in the model, and then I processed the data for entry into the model. I drafted and fine-tuned the model, created output files to utilize the predictive model in the online app, and provided interpretation on how the model was working and how the results could be interpreted and used to answer our question of interest. I created a second machine learning model using a random forest classifier to benchmark the performance of the deep neural network model and to provide the feature importance, which was then used in the organization of the input fields within the injury prediction portion of the online application. 

In addition to the machine learning, I found dataset that we used for the project and proposed the question that we aimed to answer using the data. From the start of the project, I gave input on which type of dataset we should use, dataset organization, visualization, and dashboard design. I provided critical review of visualizations and summaries and was directly involved in the dashboard design, which involved creating the inputs for each of the features for the end user and representation of the predicted outcome.

Going into the project, I had doubts about my abilities to complete the tasks that I had been assigned. I was pleasantly surprised that I was able to complete the machine learning model and learn a few new skills along the way, particularly in regard to publishing the data in an application online. Through direct communication with team members, I was able to gain news skills and apply them as we developed the finished product.

# Team Assessment

I was fortunate to have the team members that I had. We each brought different strengths to the team and complemented each other well. We initially took the time to get to know each other as individuals when the group was formed, and I think this provided a good foundation of respect among members in the group. We learned of each other’s strengths and weaknesses and the made the group assignments based on that initial assessment. We relied primarily on the time that we had in class to assess what stage of the project we were at and to determine an action plan for the upcoming days. We agreed to stay in communication on Slack, which worked well for us. In the event of a difficulty in a task, we would post to the group Slack and provide feedback or assistance. The biggest challenge that we had was the connection of the machine learning model to the web application. Each of us researched the issue until a solution was found and then worked together to bring about a solution. A real strength of the team was the ability to take the time to teach each other when there was something new that we needed to apply in the project.

# Summary of Project

The project we produced involved sampled crash data from the National Highway Traffic Safety Administration (NHTSA) for the years 2019 and 2020 to answer the question whether an individual in a crash would be likely to suffer a minor, serious, or fatal injury.  The data was hosted on Amazon Web Services using a Postgres database and was processed in Python. A deep neural network machine leaning model was used to classify each level of potential injury.  The data was visualized in Tableau. A desktop web application was created using Node JS and hosted in Heroku. Tableau visualizations were connected to the online application through an interactive display. An injury predictor was created, allowing users to select characteristics of a crash and see the predicted injury outcome.  Accuracy of the model was 77% for any injury, 93% for serious injury, and 99% for fatal injury.
