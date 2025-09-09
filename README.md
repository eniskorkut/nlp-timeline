## Sunum Kodu

Bu depo, sunumda kullanılan Jupyter Notebook'ları ve ilgili bağımlılıkları içerir.

### Sunum ve Kapsam
- Bu çalışmalar, Diyanet İşleri Başkanlığı Bilgi İşlem Kampı bünyesinde gerçekleştirilmiştir.
- Konular:
  - Tokenization (01_tokenization.ipynb)
  - Embedding (02_embedding.ipynb)
  - Attention (03_attention.ipynb)
  - RAG ve Fine-tuning (04_ragvsfinetuning.ipynb)

### Kurulum
1. Python ortamınızı oluşturun (öneri: venv veya conda).
2. Bağımlılıkları yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

### Kullanım
- Notebook'ları açmak için:
  ```bash
  jupyter lab
  # veya
  jupyter notebook
  ```
- Notebook içinde büyük modeller indirilebilir. İlk çalıştırmada internet bağlantısı gerektirebilir.

### Veri
- Örnek veri: `e-ticaret_urun_yorumlari.csv` (noktalı virgül `;` ayracı ile).

### Notlar
- `requirements.txt` dosyası, notebooklardan çıkarılan bağımlılıkları listeler.
- GPU mevcutsa PyTorch otomatik olarak GPU'yu kullanabilir; aksi halde CPU ile çalışır.


**Sunum Linki**: [NLP / Doğal Dil İşleme Sunumu](https://gamma.app/docs/NLP-natural-language-processing-Dogal-dil-isleme-2iegvr79bg6fuzh)