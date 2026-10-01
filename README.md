# Filo Yönetimi Ve Takip Sistemi

Bu projede, araç filosu bulunan bir firmanın depo, araç, sürücü ve servis verilerini ilişkisel bir veri tabanında tutan, araçlara takılan takip cihazlarından gelen verileri kaydeden ve bu verilerle araca özel rota planları oluşturan bir projedir.

Projenin hedefleri:

- Filo verilerini tutarlı ve ilişkisel bir yapıda saklamak
- Araçlardan gelen  verileri (yakıt, hız, kilometre, konum) kaydetmek
- Bu verilerle genel bir rota planı oluşturmak
- Planı araç bazında göstermek ve kaydetmek
- Kaydedilen verilerle geçmiş rotaları  göstermek

## Sistemin Çalışma Akışı

Sistemi kullanacak firmadan şu veriler istenir:
- Depo bilgileri
- Araç bilgileri
- Sürücü bilgileri
- Araç–sürücü ilişkileri
- Araç servis kayıtları

Araçlara takılan takip cihazı ile şu veriler alınır:
- Yakıt durumu
- Hız
- Kilometre
- Anlık konum

Toplanan veriler rota oluşturma algoritmasına girdi olarak verilir ve filo için genel bir plan hazırlanır.

Hazırlanan genel plan, her araca özel olacak şekilde veri tabanına kaydedilir.
