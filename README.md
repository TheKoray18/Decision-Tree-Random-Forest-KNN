# Decision-Tree-Random-Forest-KNN
Decision Tree ve Random Forest algoritmalarını kullanarak prediction modeli geliştirdim.K-Nearest Neighbors algoritmasını kullanarak da diagnosis sınıflandırması yapan model geliştirdim

Decision Tree Reression ve Random Forest Regression modeli ile veri setimiz de bulunan radius_mean sütununda ki değerleri tahmin eden bir model geliştirdim.
Bu iki modelin başarısına baktığımızda Random Forest modelimiz daha iyi tahminlerde bulunmuştur.
İki modeli karşılaştırırken de Mean Squared Error ve Root Mean Squared Error değerlerine baktım.Random Forest modelimizin Mean Squared Error değeri daha düşüktür.
Mean Squared Error değerinin düşük olması modelimizin hatasının minimum olduğunu bize verir.Root Mean Squared Error değerinin az veya çok olduğunu ölçmek için de bağımlı değişkenin standart sapmasını alırız.Eğer Root Mean Squared Error değerimiz, Bağımlı değişkenimizin stndart sapmasından küçük ise modelimiz iyi yolda ilerlediğini söyleyebiliriz.
Veri setimizde bulunan Diagnosis (kanser hücresinin kötü huylu ya da iyi huylu olduğu) kategorik veri sütunu ile de classification model geliştirdim.
Bu modeli geliştirirken K-Nearest Neighbors Classification algoritmasını kullandım.
Modelin değerlendirme metriklerinden accuracy_score ve f1_score kullanarak modelin başarısını ölçtüm. Accuracy Score değerimiz %90'dır.
Bu iki başarı değerlendirme metriğini ve f1_score hesaplarken kullanılan precision ve recall değerlerinin hepsini bir arada görüntelemek için de classification_report kullandım.
%90 accuracy değeri elde ettim.

