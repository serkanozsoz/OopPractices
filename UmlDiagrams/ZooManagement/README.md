# ZooManagement(UML Diagram)

## Ödev - Hayvanat Bahçesi Yönetimi

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

```
Hayvanlar:
-Atlar (atlar, zebralar, eşekler vb.),
-Kedigiller (kaplanlar, aslanlar vb.),
-Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
-Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır(tür adı, ağırlığı, yaşı vb.)
-Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
-Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()
-Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.
```

## Diagram

![ZooManagement](https://user-images.githubusercontent.com/100076932/166239936-a40a67e8-3e7e-4e77-aa76-248148f4637a.png)
