# Logistic-Regression
In diesem Projekt werden wir mit Fake-Daten zu Werbung arbeiten, die aufzeigen, ob ein Nutzer auf eine Werbeanzeige auf einer Webseite einer Firma geklickt hat oder nicht. Wir werden versuchen ein Modell zu erstellen, das anhand von Nutzereigenschaften vorhersagt, ob dieser auf die Werbung klicken wird oder nicht.

Der Datensatz beinhaltet folgende Eigenschaften:

* 'Daily Time Spent on Site': Zeit auf der Webseite in Minuten
* 'Age': Alter in Jahren
* 'Area Income': Durchschnittliches Einkommen der Region des Nutzers
* 'Daily Internet Usage': Durchschnittliche Minutenzahl die der Nutzer täglich im Internet ist
* 'Ad Topic Line': Überschrift der Werbung
* 'City': Stadt des Nutzers
* 'Male': Ob der Nutzer männlich ist (1) oder nicht (0)
* 'Country': Land des Nutzers
* 'Timestamp': Zeit zu der der Nutzer auf die Werbung geklickt oder das Fenster geschlossen hat
* 'Clicked on Ad': Ob der Nutzer gelickt hat (1) oder nicht (0)

# Ausfürhung

Um dieses Jupyter Notebook auszuführen, müssen Sie dem Link des oben genannten Binder-Badges folgen. Öffnen Sie das Notebook „3-Logistische_Regression_Projekt-Loesung.ipynb“. Sobald das Notbook geöffnet wurden, gehen Sie bitte auf den Reiter "Edit" und drücken Sie "Clear Outputs of all Cells". Nachdem Sie das gemacht haben, können Sie auf "Run all Cells" klicken um den Code auszuführen.

### Schritte im jupyter Notebooks

Daten laden und vorbereiten: Lesen Sie die Daten aus der Datei advertising.csv in einen DataFrame ein und untersuchen Sie die Daten mit den Methoden info() und describe(). Dies gibt Ihnen einen Überblick über die Datenstruktur und die Verteilung der verschiedenen Merkmale.

Daten visualisieren: Verwenden Sie die Bibliothek Seaborn, um verschiedene Visualisierungen der Daten zu erstellen. 

Zum Beispiel:

Erstellen Sie ein Histogramm, um die Altersverteilung der Nutzer zu sehen.
Verwenden Sie Jointplots, um die Beziehung zwischen dem Einkommen der Region und dem Alter, sowie zwischen der täglichen Internetnutzung und der Zeit, die auf der Webseite verbracht wird, zu untersuchen.
Nutzen Sie ein Pairplot, um die Datenverteilung basierend darauf zu sehen, ob auf die Anzeige geklickt wurde oder nicht.
Daten aufteilen: Teilen Sie die Daten in ein Trainings- und ein Testset auf, um das Modell zu trainieren und später zu evaluieren. Dabei verwenden Sie die Merkmale "Daily Time Spent on Site", "Age", "Area Income", "Daily Internet Usage" und "Male" als unabhängige Variablen (X) und "Clicked on Ad" als Zielvariable (y).

Modell trainieren: Trainieren Sie ein logistisches Regressionsmodell mit dem Trainingsset. Dies lernt die Beziehung zwischen den Nutzermerkmalen und der Wahrscheinlichkeit, dass auf die Anzeige geklickt wird.

Vorhersagen und Evaluierung: Nutzen Sie das trainierte Modell, um Vorhersagen für das Testset zu machen. Bewerten Sie die Modellleistung anhand eines Klassifizierungsberichts, der Metriken wie Precision, Recall, und F1-Score enthält.

# Binder Badge
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FranjoHHZ/Logistic-Regression/HEAD)



# Aufürhung in Colabs

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FranjoHHZ/Logistic-Regression/blob/main/Logistic%20Regression/3-Logistische_Regression_Projekt-Loesung.ipynb)

# Erwartete Ergbnisse
Der Klassifizierungsreport zeigt diese Werte:

![image](https://github.com/user-attachments/assets/a1bb6f03-0388-4575-a2ec-543e1d48a6fa)


