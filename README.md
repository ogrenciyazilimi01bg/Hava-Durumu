# Hava-Durumu
## Genel Bakış
Bu projede, Hava Durumu  için geliştirilen kodların kaynağı yer almaktadır. Bu proje, C# dilinde yazılmış bir Hava durumu uygulamasını içermektedir. Proje, konsol uygulaması olarak tasarlanmıştır ve Türkiye'nin üç büyük şehri olan İstanbul, İzmir ve Ankara için güncel hava durumu bilgilerini ve 3 günlük bir tahmin sunmaktadır. Bu yönergeleri, projeyi kendi makinenizde çalıştırmak ve geliştirmek için kullanabilirsiniz. Hava verileri "goweather" API'sından alınmaktadır.
## Özellikler
- Her şehir için güncel sıcaklık, rüzgar hızı ve hava durumu açıklamasını gösterir.
- 3 günlük hava durumu tahmini sağlar, bu tahminde gün, sıcaklık, açıklama ve rüzgar hızı yer alır.
## Classlar
Bu proje Hava durumu  projesi.Burda ForecastData,WeatherData classlarından oluşmaktadır. Bu projede, 2 Class yer almaktadır. WeatherData Class’ı içerisinde: Temperature, Wind,  Description  özellikleri yer almaktadır ve ForecastData Class’ından Forecast dizisi özelliği türetilir . ForecastData Class’ı içerisinde: Day, Temperature,Description ve Wind özellikleri yer almaktadır.
## Consol uygulaması bu şekilde çalışır:
1. Programı çalıştırın.
2. Uygulama, "goweather" API'sından İstanbul, İzmir ve Ankara için en son hava verilerini çekecektir.
3. Konsol, her şehir için güncel hava durumu bilgilerini ve 3 günlük bir tahmini gösterecektir.
Not : Eğer API ulaşılamazsa, bir hata mesajı görüntülenir ve veriler gösterilemez.
