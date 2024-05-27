# Kurumsal Ağ Simülasyonu ve Yönetimi

## Proje Amacı
Bu proje, bir kurumsal ağın simülasyonunu yaparak farklı ağ topolojilerini ve senaryolarını test etmeyi amaçlar. Ayrıca, bu simülasyon üzerinden ağ yönetimi ve optimizasyonu için araçlar geliştirilir.

## Kullanılan Teknolojiler
- Cisco Packet Tracer / GNS3
- Python
- Netmiko, Nornir

## Adımlar
1. **Topoloji Tasarımı**
   - Ana ofis ve iki uzak ofis içeren bir ağ topolojisi oluşturuldu.
   - Kullanılan cihazlar: Routerlar, Switchler, Access Pointler, Sunucular, İstemci Bilgisayarlar.

2. **Ağ Simülasyonu**
   - Cisco Packet Tracer kullanılarak ağ topolojisi oluşturuldu.
   - Cihaz konfigürasyonları yapıldı: IP adresleri, VLAN'lar, routing protokolleri (OSPF, EIGRP).

3. **Ağ Yönetimi ve Optimizasyonu**
   - Python kullanılarak ağ yönetim aracı geliştirildi.
   - **Modüller**:
     - Konfigürasyon Yedekleme
     - Ağ Performans İzleme
     - Güvenlik Kontrolleri

## Kurulum ve Kullanım
- Projeyi klonlayın: `git clone https://github.com/atakandenzakdmr/ag-simulasyon-projesi.git`
- Gerekli Python kütüphanelerini yükleyin: `pip install -r requirements.txt`
- Simülasyon dosyasını Cisco Packet Tracer ile açın ve çalıştırın.
- Python betiklerini çalıştırarak ağ yönetim araçlarını kullanın.

## Katkıda Bulunma
Katkıda bulunmak için lütfen bir pull request oluşturun ve değişikliklerinizi açıklayın.
