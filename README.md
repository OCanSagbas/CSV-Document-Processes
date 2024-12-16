# 📄 CSV Document Processes
Bu repository, CSV dosyalarını okuma, düzenleme ve kaydetme işlemlerini gerçekleştiren bir Python projesini içermektedir.

# 🚀 Proje Açıklaması
Bu projede, CSV (Comma-Separated Values) formatındaki dosyalar üzerinde çeşitli veri işleme işlemleri gerçekleştirilmiştir. Özellikle:

Satır ve sütun ekleme/silme
Veri filtreleme ve düzenleme
Yeni CSV dosyası oluşturma
Jupyter Notebook ortamında detaylı olarak kodlanmıştır.

# 📂 Dosya Yapısı
bash
Kodu kopyala
CSV-Document-Processes/  
│  
├── CSV_File_Modifying.ipynb   # CSV dosyalarını düzenleyen Jupyter Notebook  
└── README.md                  # Proje açıklaması  
🛠️ Gereksinimler
# Bu projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

pandas
numpy
Kurulum için:

bash
Kodu kopyala
pip install pandas numpy  
# 💻 Kullanım
Repository'yi klonlayın:

bash
Kodu kopyala
git clone https://github.com/OCanSagbas/CSV-Document-Processes.git  
cd CSV-Document-Processes  
Jupyter Notebook'u çalıştırın:

bash
Kodu kopyala
jupyter notebook  
CSV_File_Modifying.ipynb dosyasını açarak adım adım çalıştırabilirsiniz.

# 📊 Örnek Kullanım
CSV Okuma

python
Kodu kopyala
import pandas as pd  
df = pd.read_csv("example.csv")  
print(df.head())  
CSV Düzenleme

python
Kodu kopyala
df['NewColumn'] = df['OldColumn'] * 2  
df.to_csv("modified_file.csv", index=False)  
# 🔧 Amaç
Bu proje, CSV dosyaları üzerinde veri düzenleme işlemlerini öğrenmek isteyen kullanıcılar için hazırlanmıştır. Veri manipülasyonu, veri analizi öncesi temel adımlardan biridir.

## 📜 Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.

