# Introduction to query tools

[Introduction to query tools 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/mklje/introduction-to-query-tools)

# Querying and Searching Log Data in Cybersecurity

## 1. Introduction

- Sorting through **large amounts of log data** is a critical skill in cybersecurity.
- This video covers:
  - **How to query effectively**.
  - **How to use Regular Expressions (RegEx)**.
  - **How Unified Data Model (UDM) enhances log searching**.

## 2. Querying Log Data in Cloud Environments

- **Cloud logging systems** generate vast amounts of log data from:
  - **User activities**.
  - **Authentication attempts**.
  - **Firewall logs**.
  - **Intrusion detection and prevention systems (IDPS)**.
- **Effective querying** helps filter, sort, and extract **relevant data**.

## 3. Introduction to Regular Expressions (RegEx)

- **RegEx** is a pattern-matching technique used to **search for specific text patterns**.
- **Example: SSH Login Attempts**
  - Imagine an **authentication log** with thousands of entries.
  - **RegEx can search for failed SSH login attempts** based on:
    - **SSH protocol**.
    - **Port number**.
    - **Failed login status**.

### **How RegEx Works**

- **Pattern Matching** – Defines the search criteria.
- **If text matches the pattern**, RegEx extracts the data.

### **Example: Google Cloud Logs Explorer**

- **Google Cloud's Logs Explorer** allows **querying logs using RegEx**.
- **Example Query Breakdown**:
  - **logName="logs/ssh"** → Identifies the log file.
  - **=~ "SSH"** → Uses RegEx to search for logs containing "SSH".
  - **^SSH** → Matches only entries that **start with SSH**.

### **Advantages of RegEx**

- **Faster and more efficient searches**.
- **Works across different tools and programming languages**.
- **Flexible pattern matching**.

## 4. RegEx Fundamentals

- **Square Brackets [abc]** → Matches **any one of the characters** inside the brackets.
- **Period (.)** → Wildcard that **matches any single character**.
- **Backslash \s** → Matches **whitespace characters** (space, tab).
- **Backslash \d** → Matches **digits (0-9)**.
- **Curly Brackets {5}** → Defines **the number of characters to match**.

## 5. Understanding UDM (Unified Data Model)

- **Chronicle uses UDM** to process and store aggregated log data.
- **UDM = A filing cabinet** for organizing log data.
- **Benefits of UDM**:
  - **Attaches labels to data for easier searches**.
  - **Helps identify security threats more efficiently**.

### **Example: UDM Rule for Suspicious Logins**

- **Rule Name:** `differentCityLogin`
- **Meta Section:** Contains **additional rule information**.
- **Events Section:** Specifies **what data to match** (e.g., **user logins**).
- **Match Section:** Defines **time-based conditions**:
  - **Example: User logs in from multiple cities within 5 minutes**.
- **Condition Section:** Defines **when an alert is triggered**.
  - If all conditions are met, **an alert is generated**.

### **Performing UDM Searches in Chronicle**

- **Chronicle's UDM Search** processes ingested security data.
- **Allows for advanced filtering and correlation**.
- **Enhances threat detection** by structuring data.

## 6. Conclusion

- **Mastering querying techniques saves time in log analysis**.
- **RegEx improves search performance** by efficiently filtering logs.
- **UDM simplifies data organization** for better threat detection.
- **With practice, cybersecurity professionals can refine these skills** for better investigations.

---

# Cybersecurity တွင် Log Data Querying နှင့် Searching

## ၁။ မိတ်ဆက်

- **Log Data တွင် သံသယဖြစ်စရာ အချက်အလက်များကို စိစစ်ရန်** **querying** နှင့် **searching** လုပ်နိုင်ဖို့ လိုအပ်သည်။
- ဤသင်ခန်းစာတွင်:
  - **Query တစ်ခုကို ထိရောက်စွာ ဖန်တီးနည်း**။
  - **Regular Expressions (RegEx) ကိုအသုံးပြုနည်း**။
  - **Unified Data Model (UDM) ဖြင့် Log Data ကို အစီအစဉ်ပြုလုပ်နည်း** **ကို လေ့လာမည်**။

## ၂။ Cloud Environment များတွင် Log Data Querying

- **Cloud Logging Systems** တွင် အောက်ပါ source များမှ **log data များ** ပါဝင်နိုင်သည်။
  - **အသုံးပြုသူ လှုပ်ရှားမှုများ**။
  - **Authentication Attempts** (Login, Logout)။
  - **Firewall Logs**။
  - **Intrusion Detection & Prevention System (IDPS) Logs**။
- **ထိရောက်သော Querying** ဖြင့် အရေးကြီးသော အချက်အလက်များကို **Filter, Sort, Extract** ပြုလုပ်နိုင်သည်။

## ၃။ Regular Expressions (RegEx) ကို နားလည်ခြင်း

- **RegEx** သည် **လက်ခံထားသော pattern များအတိုင်း log data များကို ရှာဖွေနိုင်သော နည်းလမ်း** ဖြစ်သည်။
- **ဥပမာ: SSH Login Attempts ကို ရှာဖွေရန်**
  - Authentication Log များထဲတွင် **SSH Login** **ဆိုင်ရာ သောင်းနှင့်ချီသော entry များ** ရှိနိုင်သည်။
  - **RegEx** ကို အသုံးပြု၍ **SSH protocol**, **port number**, **failed login attempts** များကို **ထုတ်ယူနိုင်သည်**။

### **RegEx ၏ အလုပ်လုပ်ပုံ**

- **Pattern ကို သတ်မှတ်ခြင်း** – ရှာလိုသော အကြောင်းအရာကို သတ်မှတ်ရန်။
- **မည်သည့် text မဆို pattern နှင့် ကိုက်ညီပါက**, **RegEx သည် အချက်အလက်များကို ထုတ်ပေးနိုင်သည်**။

### **Google Cloud Logs Explorer မှ RegEx Example**

- **Google Cloud Logs Explorer** တွင် **RegEx** ကို အသုံးပြု၍ **log searching** ပြုလုပ်နိုင်သည်။
- **Query Breakdown**
  - **logName="logs/ssh"** → **Log File ကို သတ်မှတ်ခြင်း**။
  - **=~ "SSH"** → **RegEx ကို အသုံးပြု၍ SSH ဖြင့် စတင်သော Log များကို ရှာဖွေနိုင်သည်**။
  - **^SSH** → **SSH ဖြင့် စတင်သော log entry များသာ ရှာဖွေနိုင်သည်**။

### **RegEx ၏ အားသာချက်များ**

- **Search Performance ပိုမိုမြန်ဆန်ခြင်း**။
- **ပုံမှန် text searching ထက် ပိုမိုပြည့်စုံခြင်း**။
- **Programming Language အမျိုးမျိုးတွင် အသုံးပြုနိုင်ခြင်း**။

## ၄။ RegEx ၏ မူလအခြေခံများ

- **[abc]** → **a, b, c အနက်မှ တစ်ခုခု ကိုက်ညီသော စာလုံးများကို ရှာဖွေနိုင်သည်**။
- **. (Period)** → **တစ်ခုခု character ကို ကိုက်ညီစေသည်**။
- **\s** → **Whitespace (space, tab) ကို ကိုက်ညီစေသည်**။
- **\d** → **Digit (0-9) ကို ကိုက်ညီစေသည်**။
- **{5}** → **၅ လုံးပါဝင်သော number/string ကို ရှာဖွေနိုင်သည်**။

## ၅။ Unified Data Model (UDM) ကို နားလည်ခြင်း

- **Google Chronicle** သည် **UDM** ကို အသုံးပြု၍ **log data များကို စနစ်တကျ စုစည်းသည်**။
- **UDM = Log Data ကို ဖိုင်အမျိုးအစားအလိုက် ခွဲခြားသိမ်းဆည်းနိုင်သော စနစ်**။
- **UDM ၏ အကျိုးကျေးဇူးများ**:
  - **Log Data များကို Label (Tag) များဖြင့် စနစ်တကျ ပြုလုပ်နိုင်သည်**။
  - **Security Threat များကို ပိုမိုမြန်မြန် ရှာဖွေနိုင်သည်**။

## ၆။ သတ်မှတ်ချက်

- **Querying နည်းလမ်းများကို သိရှိခြင်းသည် Log Analysis ကို မြန်မြန်ပြုလုပ်နိုင်စေသည်**။
- **RegEx သည် log searching အတွက် ထိရောက်သော နည်းလမ်းဖြစ်သည်**။
- **UDM သည် data များကို စနစ်တကျ စုစည်းခြင်းဖြင့် Log Analysis ကို ပိုမို အလွယ်တကူ ပြုလုပ်နိုင်စေသည်**။
