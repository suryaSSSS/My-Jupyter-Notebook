# My Jupyter Notebook on IBM Watson Studio
Name : SURYA RAJAN S

Desired Occupation: Data Scientist

It all started with when I was first introduced to BASIC code as a part of my matriculation studies. At first the black screen with white pixelated alphabets were quite suffocating, but it isn’t in my nature to fly away at the face of any challenge. I struggled in it, made blunders in my assignments, but when I got a hang of the keywords and constructed a mind-map of how the syntax is related, I could make the MACHINE do what “I” wanted. That was a really big deal and that’s how it all started. The thing I was struggling with, became my game.

Now that I had grasped the knowledge of how to solve basic problems I looked forward to other challenges. Having a profound interest and understanding in Mathematics and statistics, led me to develop code that would actually solve a problem rather than "print" my name on the screen.

After that I leared all kinds of things related to problem solving, algorithms, data structures etc. Before I knew it, I was already finishing my Masters Degree Program from University of Karachi in Computer Science. But I still have a lot to accomplish, and I will not stop looking forward.


The following code snippet performs basic Linear Regression on a sample dataset.



#Getting the sample dataset
Sample = pd.read_csv("http://bit.ly/w-data")

# Creating "x" and "y" variables
x = Sample[["Hours"]]
y = Sample[["Scores"]]

# Creating and fitting the Linear Regression model
model = lr()
model.fit(x , y)

# Plotting the regression line
line = model.coef_*x+model.intercept_

# Plotting the scatter plot for our original dataset
plt.scatter(x, y, marker='+', color='green')
plt.plot(x, line, color='red', linewidth='0.2');
plt.show()





![image](https://user-images.githubusercontent.com/86156702/144440864-b80f9ff0-9d3d-4bb4-a1f4-3f2a08237b3e.png)
