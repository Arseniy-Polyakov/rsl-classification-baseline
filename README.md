# russian-sign-language-classification

  # kfolds = KFold(n_splits=5, random_state=42, shuffle=True)
  # accuracy_metric, f1_metric, classification_report_metric = [], [], []
  # for i, (train_index, test_index) in enumerate(kfolds.split(X, y)):
  #   X_train, X_test = X[train_index], X[test_index]
  #   y_train, y_test = y[train_index], y[test_index]

  #   model = models[model_name]
  #   model.fit(X_train, y_train)
  #   y_pred = model.predict(X_test)
  #   accuracy_metric.append(accuracy_score(y_pred, y_test))
  #   f1_metric.append(f1_score(y_pred, y_test, average="macro"))
  #   classification_report_metric.append(classification_report(y_pred, y_test))