# Global_AI_Hub_Akbank_Data_Analysis_Bootcamp


**------------English------------**

# Mercedes-Benz Stock Data Analysis

## Overview
This project involves the analysis and feature engineering of Mercedes-Benz stock data. The dataset includes 1105 records with the following columns: 'Date', 'Open', 'High', 'Low', 'Close', 'Adj Close', and 'Volume'. The objective is to preprocess the data, analyze the relationships between variables, handle outliers, and perform feature selection to prepare the data for further modeling.

## Steps and Techniques

### 1. Data Preprocessing and Exploratory Data Analysis (EDA)

#### Data Cleaning
- Converted the 'Date' column to datetime format.
- Checked for missing values and found no missing values in the dataset.

#### Descriptive Statistics
- Generated basic statistics such as mean, median, standard deviation, etc., for all numerical columns.

### 2. Data Visualization

#### Scatter Plot
- Visualized the 'Open' prices over time using a scatter plot.

#### Histogram
- Visualized the distribution of 'Volume' to understand its distribution and identify outliers.

#### Time Series Plot
- Plotted the 'Volume' over time to visualize trends and patterns.

### 3. Handling Outliers

#### Box Plot
- Used box plots to visualize the outliers in the 'Volume' data.

#### Winsorizing
- Applied Winsorizing to cap the extreme outliers based on the calculated lower and upper limits:
  - Lower limit: 4835280527572.5
  - Upper limit: 9761116761076.5

### 4. Correlation Analysis

#### Correlation Matrix
- Analyzed the relationships between numerical variables using a correlation matrix.

### 5. Feature Selection

#### Variance Threshold
- Removed features with low variance that might not be useful for modeling.

#### Backward Elimination
- Used backward elimination to remove features with high p-values.

#### Recursive Feature Elimination (RFE)
- Selected the most important features using Recursive Feature Elimination.

## Conclusion
In this project, we successfully preprocessed the data, visualized the relationships and distributions, handled outliers, and performed feature selection. These steps have prepared the data for further modeling and analysis. The techniques used ensure that the data is clean, relevant, and ready for predictive modeling.

---


**------------Turkish------------**

# Mercedes-Benz Stock Data Analysis

## Overview
Bu proje, Mercedes-Benz borsa hissesi verilerinin analizi ve özellik mühendisliğini içermektedir. Veri seti, 1105 kayıttan oluşmakta olup 'Date', 'Open', 'High', 'Low', 'Close', 'Adj Close' ve 'Volume' sütunlarını içermektedir. Projenin amacı, verileri ön işlemek, değişkenler arasındaki ilişkileri analiz etmek, aykırı değerleri ele almak ve özellik seçimi yaparak veriyi modellemeye hazırlamaktır.

## Steps and Techniques

### 1. Data Preprocessing and Exploratory Data Analysis (EDA)

#### Data Cleaning
- 'Date' sütunu tarih formatına dönüştürüldü.
- Eksik değerler kontrol edildi ve veri setinde eksik değer bulunmadı.

#### Descriptive Statistics
- Tüm sayısal sütunlar için ortalama, medyan, standart sapma gibi temel istatistiksel değerler hesaplandı.

### 2. Data Visualization

#### Scatter Plot
- 'Open' fiyatlarını zaman içinde görselleştirmek için scatter plot kullanıldı.

#### Histogram
- 'Volume' verisinin dağılımını görmek ve aykırı değerleri belirlemek için histogram oluşturuldu.

#### Time Series Plot
- 'Volume' verisi zaman içinde çizilerek trendler ve desenler görselleştirildi.

### 3. Handling Outliers

#### Box Plot
- 'Volume' verisindeki aykırı değerleri görselleştirmek için box plot kullanıldı.

#### Winsorizing
- Hesaplanan alt ve üst limitlere göre aşırı uç değerler Winsorizing yöntemi ile sınırlandırıldı:
  - Alt limit: 4835280527572.5
  - Üst limit: 9761116761076.5

### 4. Correlation Analysis

#### Correlation Matrix
- Sayısal değişkenler arasındaki ilişkileri analiz etmek için korelasyon matrisi kullanıldı.

### 5. Feature Selection

#### Variance Threshold
- Düşük varyansa sahip özellikler çıkarılarak modellemeye daha faydalı özellikler seçildi.

#### Backward Elimination
- Yüksek p-değerlerine sahip özellikler çıkarılarak önemli özellikler belirlendi.

#### Recursive Feature Elimination (RFE)
- Recursive Feature Elimination yöntemi ile en önemli özellikler seçildi.

## Conclusion
Bu projede, veriler başarıyla ön işlemden geçirilmiş, ilişkiler ve dağılımlar görselleştirilmiş, aykırı değerler ele alınmış ve özellik seçimi yapılmıştır. Bu adımlar, verilerin ileri modelleme ve analiz için hazır hale getirilmesini sağlamıştır. Kullanılan teknikler, verinin temiz, ilgili ve tahminsel modellemeye hazır olmasını garanti eder.

---
