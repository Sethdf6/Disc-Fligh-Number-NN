# Disc Flight Number Neural Network
## Description 
A Neural Network designed to determine optimal flight numbers to be assigned to disc based on dimensions and characteristics of the mold. In disc golf discs are assigned numbers corresponding to their speed, glide, turn, and fade helping players predict how they will fly before they are thrown. This project aims to take the 1000+ discs on the market and develop a model that can classify new discs based on their predicted flight numbers.

### Process
The discs were inputed into a database and missing values were filtered out, strings were converted to numerical values, and column headers were renamed. Next the database was split into training and test datasets (80,20 split) and values were normalized. Finally using Tensorflow the 3 layer model was constructed using a ReLu activation function and 200 epochs. The alpha value was adjusted and the calculations were run several times with the same seed until the accuracy was improved over 85%. 

#### Results
The constructed model ended up having an accuracy of roughly 88% which considering the inconsitencies in flight ratings between disc golf brands is not too bad. I can say with some certainty that as new discs are released my model will be able to predict how they will fly based on their physical dimensions alone. Going forward I'd like to expand a little more into the sport of disc golf and maybe investigate the correlation between disc brands and the successes of players.
