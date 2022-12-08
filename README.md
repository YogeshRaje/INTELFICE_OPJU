# INTELFICE_OPJU
Day4 Prgram and Dataset link
https://drive.google.com/drive/folders/16gtUKlWCjhwON6fM1rKU0XSxyGbQGph4?usp=sharing



from sklearn import svm
modelsvm = svm.SVC(kernel='rbf',gamma='auto')
modelsvm.fit(X_train,y_train)
pred = modelsvm.predict(X_test)
#checking the validation score or test score 
print('Validation accuaracy score with svc ',accuracy_score(y_test,pred))

+++++++++++++++++++++++++++++++++++++++++++

ANN using Sklearn

https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html


https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html

