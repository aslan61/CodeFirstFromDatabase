# CodeFirstFromDatabase

Bu proje, Entity Framework'ün "Code First from Database" yaklaşımını kullanarak bir veritabanı modelini oluşturmayı ve yönetmeyi amaçlamaktadır. Proje, bir ürün ve kategori ilişkisini temsil eden bir veritabanı yapısını içerir.

## Özellikler
- **Entity Framework Code First**: Veritabanı modelleri C# sınıfları üzerinden tanımlanmıştır.
- **Kategori ve Ürün İlişkisi**: 
  - `Kategori` sınıfı, birden fazla `Urunler` nesnesi ile ilişkilidir.
  - `Urunler` sınıfı, isteğe bağlı olarak bir `Kategori` ile ilişkilendirilebilir.
- **.NET Framework 4.7.2**: Proje, .NET Framework 4.7.2 üzerinde çalışmaktadır.
- **C# 7.3**: Kod, C# 7.3 dil özelliklerini kullanmaktadır.

## Kullanılan Teknolojiler
- **C#**
- **Entity Framework**
- **Windows Forms**

## Proje Yapısı
- **Model1.cs**: Veritabanı bağlamı ve ilişkilerin tanımlandığı sınıf.
- **Kategori.cs**: Kategori modelini temsil eden sınıf.
- **Urunler.cs**: Ürün modelini temsil eden sınıf.
- **Form1.cs**: Windows Forms arayüzü.

Bu proje, Entity Framework ile veritabanı yönetimi ve ilişkisel modelleme konularında öğrenim ve geliştirme yapmak isteyenler için uygundur.
