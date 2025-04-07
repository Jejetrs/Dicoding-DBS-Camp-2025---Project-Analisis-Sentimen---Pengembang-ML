# ⚙️ SETUP

🔁 1. Upgrade & Reinstall Dependencies
```
!pip install --upgrade --force-reinstall numpy pandas scikit-learn gensim

⚠️ Setelah instalasi, restart runtime/kernel:
<RESTART KERNEL / SESSION / RUNTIME>
```

📦 2. Install Library Tambahan
```
!pip install Sastrawi
!pip install emoji
!pip install gensim
```

🔤 3. Download NLTK Resources
```
import nltk
nltk.download('stopwords')
nltk.download('punkt')

from nltk.corpus import stopwords
stop_words = set(stopwords.words('indonesian'))
```
