# diabetes
Bu çalışmada, diyabet hastalığının öngörülmesi için çeşitli makine öğrenmesi algoritmaları uygulanmıştır. UCI Machine Learning Repository'den indirilen diyabet veri seti kullanılarak, Support Vector Machines (SVM), Decision Tree, Random Forest ve XGBoost gibi algoritmalar karşılaştırılmıştır. Veri seti, hamilelik durumu, glukoz seviyesi, kan basıncı, cilt kalınlığı, insülin seviyesi, vücut kitle indeksi, diyabet soy ağacı işlevi ve yaş gibi öznitelikleri içermektedir.

Veri setinde eksik değerlerin bulunduğu tespit edilmiş ve bu değerler medyan değeriyle doldurulmuştur. Veriler standardizasyon işleminden geçirilerek aynı ölçek üzerinde normalize edilmiştir. Ardından, veri seti eğitim ve test olarak ayrılmış ve modellerin performansı çeşitli metriklerle (accuracy, precision, recall, f1-score) değerlendirilmiştir.

Sonuçlar, Random Forest modelinin diğer yöntemlere göre daha yüksek doğruluk oranı ve daha iyi sınıflandırma performansı sunduğunu göstermiştir. XGBoost modeli ise güçlü öğrenme kapasitesiyle dikkat çekmiş ancak bazı teknik hatalar nedeniyle model tamamen değerlendirilememiştir. Bu çalışma, diyabet hastalığının erken teşhisinde makine öğrenmesi algoritmalarının etkinliğini ortaya koymaktadır.
