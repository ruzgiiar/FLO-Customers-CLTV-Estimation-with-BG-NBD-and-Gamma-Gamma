# FLO Customers CLTV Estimation with BG-NBD and Gamma-Gamma
---

## Business Problem (İş Problemi)

- **FLO wants to determine a roadmap for sales and marketing activities. In order for the company to make medium-long term plans, it is necessary to estimate the potential value that existing customers will provide to the company in the future.**

    - *(FLO satış ve pazarlama faaliyetleri için roadmap belirlemek istemektedir. Şirketin orta uzun vadeli plan yapabilmesi için var olan müşterilerin gelecekte şirkete sağlayacakları potansiyel değerin tahmin edilmesi gerekmektedir.)*

 ---

 ## Data Set Story (Veri Seti Hikayesi)

 - **The data set shows the last purchases from Flo in 2020 - 2021 by OmniChannel (both online and offline shoppers). It consists of information obtained from the past shopping behavior of customers.**

    - *(Veri seti Flo’dan son alışverişlerini 2020 - 2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan) olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.)*
---

- **master_id:** *Unique customer number* (Eşsiz Müşteri Numarası)

- **order_channel:** *Which channel of the shopping platform is used (Android, iOS, Desktop, Mobile)* (Alışveriş yapılan platforma ait hangi kanalın kullanıldığı (Android, ios, Desktop, Mobile))

- **last_order_channel:** *Channel where last purchase was made* (En son alışverişin yapıldığı kanal)

- **first_order_date:** *Date of the customer's first purchase* (Müşterinin yaptığı ilk alışveriş tarihi)

- **last_order_date:** *Customer's last purchase date* (Müşterinin yaptığı son alışveriş tarihi)

- **last_order_date_online:** *The customer's last shopping date on the online platform* (Müşterinin online platformda yaptığı son alışveriş tarihi)

- **last_order_date_offline:** *The last shopping date of the customer on the offline platform* (Müşterinin offline platformda yaptığı son alışveriş tarihi)

- **order_num_total_ever_online:** *Total number of purchases made by the customer on the online platform* (Müşterinin online platformda yaptığı toplam alışveriş sayısı)

- **order_num_total_ever_offline:** *Total number of purchases made by the customer offline* (Müşterinin offline'da yaptığı toplam alışveriş sayısı)

- **customer_value_total_ever_offline:** *Total fee paid by the customer for offline purchases* (Müşterinin offline alışverişlerinde ödediği toplam ücret)

- **customer_value_total_ever_online:** *Total fee paid by the customer for online shopping* (Müşterinin online alışverişlerinde ödediği toplam ücret)

- **interested_in_categories_12:** *List of categories the customer has shopped in the last 12 months* (Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi)

---
