# Elan Yerləşdirmə – Test Ssenariləri

## Pozitiv yoxlamalar

### 1. Elanın uğurla yaradılması
**Addımlar:**
- İstifadəçi hesabına daxil olur
- Elan yerləşdir bölməsinə daxil olur
- Bütün məcburi sahələri doldurur
- "Yerləşdir" düyməsinə klik edir

**Nəticə:**
- Elan uğurla yaradılır və istifadəçinin elanlar siyahısında görünür

---

### 2. Şəkil yükləmə funksiyasının düzgün işləməsi
**Addımlar:**
- İstifadəçi elan yerləşdirmə səhifəsinə daxil olur
- Bir neçə şəkil seçərək yükləyir
- Digər sahələri doldurur və elanı yerləşdirir

**Nəticə:**
- Şəkillər elanda düzgün əks olunur

---

### 3. Müxtəlif şəkil formatlarının qəbul edilməsi
**Addımlar:**
- İstifadəçi JPG, PNG formatlarında şəkillər yükləyir
- Elanı yerləşdirir

**Nəticə:**
- Bütün formatlar düzgün qəbul olunur və görüntülənir

---

### 4. Kateqoriya seçib düzgün sahələrin açılması
**Addımlar:**
- Müəyyən kateqoriya (məs: avtomobillər) seçilir
- Sistem əlavə sahələri (marka, model və s.) göstərir
- Sahələr doldurulur və elan yerləşdirilir

**Nəticə:**
- Kateqoriyaya uyğun sahələr düzgün göstərilir və elan düzgün yerləşdirilir

---

### 5. Elanın redaktə edilərək yenidən yerləşdirilməsi
**Addımlar:**
- İstifadəçinin mövcud elanı açılır
- Məlumatlar dəyişdirilir
- Yenidən yadda saxlanılır

**Nəticə:**
- Dəyişikliklər düzgün tətbiq olunur və elan yenilənmiş formada görünür

---

## Neqativ yoxlamalar

### 1. Məcburi sahələrin boş buraxılması
**Addımlar:**
- İstifadəçi başlıq və ya qiymət kimi sahələri boş saxlayır
- "Yerləşdir" düyməsinə klik edir

**Nəticə:**
- Sistem xəta mesajı göstərir və yerləşdirməyə icazə vermir

---

### 2. Yanlış formatda qiymət daxil edilməsi
**Addımlar:**
- Qiymət sahəsinə hərflər və ya xüsusi simvollar daxil edilir (məs: abc123)
- Elan yerləşdirilməyə çalışılır

**Nəticə:**
- Sistem düzgün format tələb edir və xəta mesajı göstərir

---

### 3. Şəkil limitinin aşılması
**Addımlar:**
- İcazə veriləndən çox şəkil yüklənməyə çalışılır

**Nəticə:**
- Əlavə şəkillər qəbul edilmir və istifadəçiyə limit barədə mesaj göstərilir

---

### 4. Login olmadan elan yerləşdirmə
**Addımlar:**
- İstifadəçi login olmadan formu doldurur
- Elanı yerləşdirməyə çalışır

**Nəticə:**
- Sistem istifadəçini login səhifəsinə yönləndirir
