# FlutterEffect: Kullanıcı Akışı (User Flow) 🦋

Bu doküman, bir kullanıcının FlutterEffect platformuna girdiği andan itibaren yaşadığı deneyimi ve sistemin arka planda nasıl tepki verdiğini adım adım açıklamaktadır.

## 🌊 1. Karşılama ve Giriş (Landing Page)
* **Kullanıcı Eylemi:** Siteye giriş yapar. Minimalist, okyanus temalı arayüz ve "Small wings, big oceans" vizyonu ile karşılaşır.
* **Sistem Yanıtı:** Kullanıcıyı yormayan, amacını hemen belli eden temiz bir arama/girdi kutusu (input alanı) sunar.

## ⌨️ 2. Veri Girişi (Input Phase)
* **Kullanıcı Eylemi:** Günlük hayatta tükettiği bir ürünü veya alışkanlığını (örneğin: "1 fincan kahve", "1 adet pamuklu tişört") ilgili alana yazar ve "Hesapla" butonuna tıklar.
* **Sistem Yanıtı:** Girdiyi alır, arayüzde bir yükleme (loading) animasyonu göstererek arka planda Gemini API'ye asenkron bir istek (request) gönderir.

## 🧠 3. AI İşleme ve Kelebek Etkisi (Processing)
* **Arka Plan İşlemi:** Gemini AI, girilen veriyi standart bir veri tabanından çekmek yerine bağlamsal olarak analiz eder.
* **Kullanıcı Eylemi:** Kullanıcı herhangi bir karmaşık form doldurmadan, saniyeler içinde analiz sonucunun gelmesini bekler.

## 📊 4. Sonuçların Gösterimi (Results & Impact)
* **Kullanıcı E750 Litre su geri kazandırdın!" şeklinde bir tebrik mesajı ve bu başarıyı sosyal medyada (veya arkadaşlarıyla) paylaşabileceği bir "Paylaş" butonu çıkar.
