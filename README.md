# PWJS_PROJECT


Spektrogram to wykres widma amplitudowego sygnału dla każdej chwili t, dla której sygnał jest określony.
Konstruuje się go dzieląc cały sygnał na części, dla których obliczone amplitudy składowych harmonicznych są wartościami spektrogramu.
Argumentami są więc częstotliwość i czas.
Najczęściej pozioma oś reprezentuje czas, pionowa częstotliwość, a intensywność każdego punktu odzwierciedla amplitudę określonej częstotliwości
w danym punkcie czasu. Projekt wykorzystuje GUI bibliotek PyQt4 do reprezentacji efektów działania programu. Spektogram wykorzystuje analizę FFT do wyznaczania częstotliwości.
Użytkownik ma możliwość nagrania dźwięku lub załadowania go w pliku wav. Na wykresie częstotliwościowym pojawia się zakres próbek. Suwaki służą do wybrania zakresu
próbek do wygenerowania spektrogramu. Wygenerowane dane wejściowe pozwalają na narysowanie wykresu spektrogramu. Format danych wyjściowych jest też rozpoznawalny
dla wielu algorytmów uczenia maszynowego spejalizujących się w analizie i przetwarzaniu dźwięków (N-gram, algorytm Viterbiego, sieć neuronowa).
