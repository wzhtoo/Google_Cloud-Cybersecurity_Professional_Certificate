# Aggregations and correlations

[Aggregations and correlations 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/JvIAu/aggregations-and-correlations)

# Aggregation and Correlation in Cybersecurity

## 1. Introduction

- To **stay ahead of threats**, organizations must **collect vast amounts of data** from their infrastructure.
- This video covers **aggregation** and **correlation**, two key concepts that help:
  - **Monitor activities**.
  - **Identify patterns**.
  - **Detect potential threats**.

## 2. What is Aggregation?

- **Aggregation** = The **collection and consolidation** of diverse data sources.
- **Example: Farming Vegetables**
  - Farmers **plant, water, and harvest** different types of crops.
  - Crops are **collected, processed, and distributed**.
  - **Damaged crops are removed**, and only **useful products are delivered**.
- **In cybersecurity**, organizations aggregate data from:
  - **User activities**.
  - **Authentication logs**.
  - **Firewalls and intrusion detection systems**.
- **Benefits of Aggregation**
  - **Provides a centralized view** of security data.
  - **Helps identify security patterns**.
  - **Supports incident detection and response**.

### **Example: Security Information and Event Management (SIEM)**

- **SIEM tools** collect and analyze log data to **monitor critical activities**.
- **Google Cloud’s Chronicle** is an example of a **SIEM tool** that aggregates logs from:
  - **Firewalls**.
  - **Data Loss Prevention (DLP) tools**.

## 3. What is Correlation?

- **Correlation** = Identifying relationships between **two or more security events**.
- **Involves**:
  - **Comparing events**.
  - **Adding context**.
  - **Making connections** between incidents.

### **Example: Drought and Farming**

- A **farmer notices fewer crops** in a harvest.
- The **cause** = **Extreme drought** affected crop production.
- **Lesson**: Just like farmers **correlate events in farming**, cybersecurity professionals correlate security events.

### **Correlation in Cybersecurity**

- Used to **connect different security alerts** and **determine real threats**.
- **Example: Suspicious Login Attempt**
  1. A **user logs in from a new device** → Security alert triggered.
  2. The system **compares data points**:
     - **IP address consistency**.
     - **Login time**.
     - **Previous login behavior**.
  3. If data **matches previous behavior**, the login is **legitimate**.
  4. If data **does not match**, the login may be a **potential breach**.

## 4. Conclusion

- **Aggregation and correlation** improve **threat detection and response**.
- **Aggregation** gathers and consolidates **large volumes of data**.
- **Correlation** identifies **patterns and connections** to detect **real security incidents**.
- These techniques help **organizations stay proactive** in **cybersecurity**.

---

# Cybersecurity တွင် Aggregation နှင့် Correlation ကို နားလည်ခြင်း

## ၁။ မိတ်ဆက်

- **ခြိမ်းခြောက်မှုများကို ကြိုတင်လေ့လာရန်**, **အဖွဲ့အစည်းများသည်** **အခြေဆောင်မှု အချက်အလက်များ** **စုစည်းရမည်**။
- ဤသင်ခန်းစာတွင် **Aggregation** နှင့် **Correlation** ကို မိတ်ဆက်မည်။
- **Aggregation** နှင့် **Correlation** သည်:
  - **လှုပ်ရှားမှုများကို ကြည့်ရှုရန်**။
  - **ပုံစံများကို တွက်ချက်ရန်**။
  - **ခြိမ်းခြောက်မှုများကို ရှာဖွေရန်** အသုံးဝင်သည်။

## ၂။ Aggregation ဆိုတာဘာလဲ?

- **Aggregation** = **အချက်အလက်များကို စုစည်းပြီး တစ်နေရာထဲတွင် သိမ်းဆည်းခြင်း**။
- **ဥပမာ: စိုက်ပျိုးရေး**
  - **တောင်သူများသည် အမျိုးမျိုးသောသီးနှံများကို စိုက်ပျိုး၊ ရေမြှုပ်၊ သီးပြည့်အောင်စောင့်ရှောက်သည်**။
  - **သီးနှံများကို စုစည်းပြီး သုံးစွဲနိုင်မည့်နေရာများသို့ ပေးပို့သည်**။
  - **ပျက်စီးသည့် သီးနှံများကို ဖယ်ရှားပြီး အသုံးဝင်သည့် သီးနှံများကိုသာ ထုတ်လုပ်သည်**။
- **Cybersecurity တွင် Aggregation သည်**:
  - **အသုံးပြုသူ လှုပ်ရှားမှုများ**။
  - **Authentication Logs**။
  - **Firewall နှင့် Intrusion Detection System (IDS) Logs** **ကိုစုစည်းခြင်း** ဖြစ်သည်။
- **Aggregation ၏ အကျိုးကျေးဇူးများ**
  - **လုံခြုံရေးအချက်အလက်များကို တစ်နေရာထဲတွင် စုစည်းနိုင်သည်**။
  - **လှုပ်ရှားမှုများအပေါ် ပုံစံများကို တွက်ချက်နိုင်သည်**။
  - **ခြိမ်းခြောက်မှုများကို မြန်မြန်ထောက်လှမ်းနိုင်သည်**။

### **ဥပမာ: Security Information and Event Management (SIEM)**

- **SIEM Tools** သည် **Log Data များကို စုစည်း၍ အရေးကြီးသော လှုပ်ရှားမှုများကို ထိန်းချုပ်ပေးနိုင်သည်**။
- **Google Cloud's Chronicle** သည် **SIEM Tool** တစ်ခုဖြစ်သည်။
  - **Firewall Logs**။
  - **Data Loss Prevention (DLP) Tools Logs** **ကို စုစည်း၍ ခြိမ်းခြောက်မှုများကို တုံ့ပြန်နိုင်သည်**။

## ၃။ Correlation ဆိုတာဘာလဲ?

- **Correlation** = **လုံခြုံရေးဖြစ်စဉ်များအကြား ဆက်စပ်မှုများကို တွက်ချက်ခြင်း**။
- **Correlation တွင် ပါဝင်သော အကြောင်းအရာများ**:
  - **ဖြစ်ရပ်များကို နှိုင်းယှဉ်ခြင်း**။
  - **Context (အကြောင်းအရာ) ထည့်သွင်းခြင်း**။
  - **အဖြစ်အပျက်များအကြား ဆက်နွယ်မှုများကို ချိတ်ဆက်ခြင်း**။

### **ဥပမာ: မိုးခေါင်ခြင်းနှင့် စိုက်ပျိုးရေး**

- **တောင်သူသည် သီးနှံများ မရနိုင်ခြင်း** ကို တွေ့ရသည်။
- **အကြောင်းရင်း** = **အလွန်ပြင်းထန်သော မိုးခေါင်မှု**။
- **သင်ခန်းစာ**: **စိုက်ပျိုးရေးတွင် ဖြစ်ရပ်များကို ဆက်စပ်ဆင်ခြင်နိုင်သလို**, **Cybersecurity တွင်လည်း Correlation ကိုအသုံးပြုနိုင်သည်**။

### **Cybersecurity တွင် Correlation**

- **Security Alerts များကို ချိတ်ဆက်ပြီး သောင့်စွဲရှာဖွေနိုင်သည်**။
- **ဥပမာ: သံသယဖြစ်စရာ Login Attempt**
  1. အသုံးပြုသူ **အသစ်သော Device** မှ login ပြုလုပ် → **Security Alert Trigger**။
  2. System သည် **Login Data များကို နှိုင်းယှဉ်**:
     - **IP Address ကို ကြည့်ခြင်း**။
     - **Login ၏ အချိန်**။
     - **ယခင် Login Pattern နှင့် ကိုက်ညီမှု**။
  3. **တူညီမှုရှိပါက**, **Login သည် မှန်ကန်သည်**။
  4. **မကိုက်ညီပါက**, **အနိုင်ကျင့်မှု ဖြစ်နိုင်သည်**။

## ၄။ သတ်မှတ်ချက်

- **Aggregation နှင့် Correlation သည် ခြိမ်းခြောက်မှုများကို စောစောမိရှာနိုင်စေသည်**။
- **Aggregation** သည် **အချက်အလက်များကို စုစည်းပေးသည်**။
- **Correlation** သည် **ဖြစ်ရပ်များအကြား ဆက်စပ်မှုများကို တွက်ချက်ပေးသည်**။
- **Cybersecurity တွင် ပိုမို လုံခြုံရေးရှိရန် Aggregation နှင့် Correlation ကို ပေါင်းစပ်အသုံးပြုသင့်သည်**။
