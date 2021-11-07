# Dart_score_APP_v2
Dart scoring system base on IOS


For code related details, please see https://github.com/lucien404/Dart_score_APP_v2/tree/master
1. If you just want to view work related to CV. The calculation of the related dart score calculation in the vision is in back_end, and it can be run by running scoring.py.
2. The server-related interface can be obtained in scoring.py in back_end, and the linux system is required
3. The IOS front end is built in front_end, and MAC needs to be used for related editing work.
4. Model training uses Mask RCNN ResNet-50 FPN, The learning rate is set to 0.005, and the SGD optimizer is used for optimization. Among them, the parameters used by SGD are momentum=0.9 and learning rate drop=0.0001. 
