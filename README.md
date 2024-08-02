# Portföy Yönetimi Uygulaması

Bu Python uygulaması, hisse senedi portföyünüzü yönetmenizi sağlar. Uygulama, kullanıcıların hisse senedi kodları ve miktarlarını eklemelerine, düzenlemelerine ve portföylerinin genel değerini görselleştirmelerine olanak tanır. Ayrıca, portföyünüzün dağılımını pasta grafiği ile görselleştirebilir.

## Özellikler

- **Hisse Senedi Ekleme**: Kullanıcılar hisse senedi kodu ve miktarını girerek portföylerine hisse senedi ekleyebilirler.
- **Hisse Senedi Düzenleme**: Var olan hisse senetlerini düzenleyebilirsiniz.
- **Portföy Listesi**: Eklenen hisse senetlerini ve her birinin değerini listeleyebilirsiniz.
- **Toplam Değer**: Portföyünüzün toplam değerini hesaplar ve görüntüler.
- **Pasta Grafiği**: Portföyünüzün dağılımını görselleştiren bir pasta grafiği sunar.
- **Veri Saklama**: Portföy verileri JSON formatında saklanır ve uygulama kapatılıp açıldığında korunur.

## Gereksinimler

- Python 3.x
- `tkinter` (Python ile birlikte gelir)
- `yfinance` (Yüklemek için `pip install yfinance`)
- `matplotlib` (Yüklemek için `pip install matplotlib`)

## Kurulum ve Kullanım

1. **Gereksinimleri Yükleyin**:
    ```bash
    pip install yfinance matplotlib
    ```

2. **Kullanım**:
    - **Hisse Senedi Kodu** ve **Miktar** girin.
    - **Ekle** butonuna tıklayarak hisse senedini portföyünüze ekleyin.
    - Portföydeki bir hisse senedini seçerek **Düzenle** butonuna tıklayarak düzenleyebilirsiniz.
    - Portföyünüzdeki toplam değeri ve dağılımını görüntüleyebilirsiniz.

## Katkıda Bulunanlar

- İbrahim Püsküllü

## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.
