# IOCs for threat detection

[IOCs for threat detection 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/supplement/aCSBE/iocs-for-threat-detection)

## PDF File

[IOCs for threat detection.pdf 🔗](https://1drv.ms/b/c/526c45566c8c239a/ET_FISS_CjtPnhZb5BzZg_0Beq9U5LtPPhLghyUbvNkp9g?e=nG0n2S)

# IoCs for threat detection

So far, you’ve learned that threat hunting is an approach security operations teams can use to
protect organizations against threats. As a reminder, threat hunting is the proactive method
of identifying previously unknown threats within a network. In this reading, you'll compare the
differences between reactive and proactive strategies for incident detection. You'll also
explore indicators of compromise, and their importance in detecting threats.

# Reactive and Proactive Strategies

## 1. Introduction

- The **proliferation of cloud deployment** introduces **new attack vectors**.
- **Malicious actors** continuously **improve their tactics** to:
  - **Gain access** to systems.
  - **Maintain access** and **evade detection**.
- **Security tools alone** are **not enough** to prevent threats.

## 2. Reactive Security Strategies

- **Traditional security solutions** like **SIEM** and **IDS** use a **reactive approach**.
- These tools detect **known threats** using:
  - **Signatures**.
  - **Patterns**.
- **How reactive security works:**
  - An alert is **generated** **while the attack is in progress**.
  - Security teams respond **after** the attack is detected.

### **Limitations of Reactive Security**

- **Effective for low-severity threats**.
- **Not sufficient for serious threats** like:
  - **Advanced Persistent Threats (APTs)**.
- **APTs** use **sophisticated tactics** to:
  - **Compromise systems**.
  - **Bypass detection**.
  - **Maintain persistence**.

### **Understanding Dwell Time**

- **Dwell time** = Number of days an attacker remains **undetected** in a system.
- **Longer dwell time** = **Greater damage** to an organization.

## 3. Proactive Security Strategies (Threat Hunting)

- **Threat hunting** is a **proactive approach** to detect and prevent attacks.
- It **searches for unknown threats** using **human judgment**.
- Helps security teams **understand attackers' motivations**.

### **Benefits of a Proactive Approach**

1. **Detects sophisticated threats** before they cause harm.
2. **Reduces dwell time** by identifying hidden attackers.
3. **Enhances security strategies** by closing security gaps.

## 4. Conclusion

- **Reactive security alone is not enough** for **modern threats**.
- **Threat hunting** provides a **proactive** defense against **APTs**.
- **Organizations should integrate proactive strategies** into their security operations.

---

# Threat Hunting Best Practices

## 1. Introduction

- **Threat hunting** is similar to **incident response**, but its main focus is to **identify previously undetected threats**.
- It requires **methodologies**, **plans**, and **processes**.
- **Best practices** can help organizations **create an effective threat hunting program**.

## 2. Best Practices for Threat Hunting

### **1. Define the Scope**

- Focus resources on **critical areas** of your environment.
- Use **threat modeling** to:
  - Identify **assets**.
  - Assess **vulnerabilities**.
  - Determine **criticality** of threats.

### **2. Know Your Threat Landscape**

- Understand **which threats** your organization is most likely to face.
- **Threat hunters** use:
  - **Threat intelligence data**.
  - **Research on observed TTPs (Tactics, Techniques, and Procedures)**.
- **Hypothesis-driven approach**:
  - Form a **testable statement** about potential threats.
  - Compare against **normal activity** (e.g., authorized applications, usual login patterns, network usage).

### **3. Use a Variety of Tools and Techniques**

- Combine multiple approaches:
  - **Threat intelligence**.
  - **Analytics**.
  - **Manual analysis**.
  - **Threat hunting frameworks**.

### **4. Collaborate with Others**

- **Cloud environments** are **complex** and **dynamic**.
- Cross-team **communication** helps build a **complete threat landscape**.

## 3. Indicators of Compromise (IoC)

- **IoC** refers to **observable evidence** of a potential security incident.
- **Malicious artifacts** include:
  - **Malware**.
  - **Hashes**.
  - **Domains**.
  - **Filenames**.
  - **IP addresses**.

### **Examples of IoC**

- **Unusual network traffic** (inbound or outbound).
- **Geographic irregularities** in network access.
- **Unknown applications** on a system.
- **Unusual privileged account activity**.
- **Increased access requests or failed logins**.
- **Unusually high database read volume**.
- **Repeated file access requests**.
- **Suspicious registry or system file changes**.
- **Unusual DNS activity**.
- **Inconsistent file hashes for known system files**.

## 4. Key Takeaways

- **No system can detect all threats**.
- **Multiple defensive approaches** help **early threat detection**.
- **Threat hunting** enables organizations to **discover threats early**.
- **Understanding threat hunting processes** helps **counter attacks** and **protect assets**.

---

# ပြန်တုံ့ပြန်မှုနှင့် ကြိုတင်ကာကွယ်မှု များ

## ၁။ မိတ်ဆက်

- **Cloud Deployment** များ **တိုးပွားလာမှု** ကြောင့် **အသစ်သော တိုက်ခိုက်မှု နည်းလမ်းများ** ပေါ်ပေါက်လာသည်။
- **မကောင်းမှုလုပ်သူများ**သည် **နည်းလမ်းများကို အဆင့်မြှင့်တင်ပြီး**:
  - **စနစ်များကို ဝင်ရောက်**နိုင်ရန်။
  - **ဝင်ရောက်မှုကို ထိန်းသိမ်းရန်** နှင့် **ရှောင်ကြဉ်ရန်**။

## ၂။ ပြန်တုံ့ပြန်မှု လုံခြုံရေး မဟာဗျူဟာများ

- **SIEM နှင့် IDS** ကဲ့သို့သော **ရိုးရာလုံခြုံရေး ဖြေရှင်းနည်းများ**သည် **ပြန်တုံ့ပြန်မှု (Reactive Approach)** ကို အသုံးပြုသည်။
- **အဓိကအားဖြင့်**:
  - **သံသယရှိသော လှုပ်ရှားမှုများကို မတိုင်မီ မတွေ့နိုင်**။
  - **တိုက်ခိုက်မှုဖြစ်နေစဉ်မှသာ သတိပေးချက်များ ထွက်ပေါ်လာသည်**။

### **ပြန်တုံ့ပြန်မှု လုံခြုံရေး၏ ချို့ယွင်းချက်များ**

- **အနည်းငယ်သော ခြိမ်းခြောက်မှုများအတွက်သာ ထိရောက်သည်**။
- **အဆင့်မြင့် တည်တံ့ခိုင်မြဲသော တိုက်ခိုက်မှုများ (APTs) ကို မထိရောက်နိုင်**။
  - **APTs (Advanced Persistent Threats or Auditable Pharmaceutical Transactions and Services)** များသည် ခက်ခဲသည့်နည်းလမ်းများနှင့် အဆင့်မြင့် လုပ်ထုံးလုပ်နည်းများကို အသုံးပြု၍ စနစ်များကို ချိုးဖောက်ခြင်း၊ စောင့်ကြည့်မှုမှ ရှောင်ရှားခြင်း၊ နှင့် ဝင်ရောက်မှုကို ရှည်ကြာစွာ ထိန်းသိမ်းခြင်းကို ပြုလုပ်နိုင်သည်။

### **Dwell Time ဆိုတာဘာလဲ?**

- **Dwell time** = **မိခင်စနစ်ထဲတွင် မတွေ့ရှိမိသေးသော ရက်ပေါင်း**။
- **Dwell time ကြာမြင့်လျှင်** = **အဖျက်အစီး ပိုမိုကြီးမားလာနိုင်သည်**။

## ၃။ ကြိုတင်ကာကွယ်မှု လုံခြုံရေး မဟာဗျူဟာ (Threat Hunting)

- **Threat Hunting** သည် **ကြိုတင်ကာကွယ်မှု နည်းလမ်း (Proactive Approach)** တစ်ခုဖြစ်သည်။
- **မသိရှိသေးသော ခြိမ်းခြောက်မှုများကို ရှာဖွေသည်**။
- **လူ့အမြင်နှင့် ဆင်ခြင်မှုများကို အသုံးပြုသည်**။

### **ကြိုတင်ကာကွယ်မှု သုံးစွဲမှု၏ အားသာချက်များ**

1. **Threat Hunting** သည် **APTs (Advanced Persistent Threats or Auditable Pharmaceutical Transactions and Services)** ကဲ့သို့သော အဆင့်မြင့် ခြိမ်းခြောက်မှုများကို ကြိုတင်ရှာဖွေနိုင်ရန် ကူညီပေးသည်။
2. **Dwell Time ကို လျှော့ချနိုင်သည်**။
3. **လုံခြုံရေး မဟာဗျူဟာများကို ပိုမိုကောင်းမွန်စေသည်**။

## ၄။ သတ်မှတ်ချက်

- **ပြန်တုံ့ပြန်မှုသာမက ကြိုတင်ကာကွယ်မှုလည်း အရေးကြီးသည်**။
- **Threat Hunting** သည် **ခေတ္တခေတ်အတွက် မဖြစ်မနေ လိုအပ်သော လုံခြုံရေး နည်းလမ်းတစ်ခုဖြစ်သည်**။
- **လုံခြုံရေး အသင်းများသည် ကြိုတင်ကာကွယ်မှု မဟာဗျူဟာများကို ထည့်သွင်းသင့်သည်**။

# Threat Hunting ဆိုင်ရာ လုပ်ထုံးလုပ်နည်းများ

## ၁။ မိတ်ဆက်

- **Threat hunting** သည် **Incident Response** နှင့် **ဆင်တူသည်**၊ သို့သော် **မသိရှိသေးသော ခြိမ်းခြောက်မှုများကို ရှာဖွေခြင်း** ဖြစ်သည်။
- **အစီအစဉ်များ၊ လုပ်ငန်းစဉ်များနှင့် နည်းလမ်းများ** လိုအပ်သည်။
- **လုပ်ထုံးလုပ်နည်းများ** မှန်ကန်ပါက **အကျိုးရှိသော Threat Hunting စနစ်** တည်ဆောက်နိုင်သည်။

## ၂။ Threat Hunting အတွက် အကောင်းဆုံး လုပ်ထုံးလုပ်နည်းများ

### **၁။ ချင့်ချိသတ်မှတ်မှု (Define the Scope)**

- **အရေးကြီးသော နယ်မြေများ** ကို **အလေးထားရန်**။
- **Threat Modeling** ဖြင့်:
  - **Asset များ** ကို ဖော်ထုတ်ရန်။
  - **အားနည်းချက်များ** ကို သုံးသပ်ရန်။
  - **ဘေးဥပဒ်များ၏ အလေးပေးမှု** ကို တိုင်းတာရန်။

### **၂။ ခြိမ်းခြောက်မှု ပတ်ဝန်းကျင်ကို နားလည်ရန် (Know Your Threat Landscape)**

- **မိမိအဖွဲ့အစည်း** ကြုံရနိုင်သည့် **ခြိမ်းခြောက်မှုအမျိုးအစားများ** ကို သိရှိရန်။
- **Threat Hunters** သည်:
  - **Threat Intelligence Data** ကို အသုံးပြုသည်။
  - **TTPs (Tactics, Techniques, and Procedures) ကို သုတေသနပြုသည်**။
- **Hypothesis-Driven Approach**:
  - **စမ်းသပ်နိုင်သော ခြိမ်းခြောက်မှု အချက်အလက်** တစ်ခုကို သတ်မှတ်ရန်။
  - **ပုံမှန်လုပ်ဆောင်မှုများနှင့် နှိုင်းယှဉ်ရန်** (ဥပမာ - အသုံးပြုခွင့်ပြုထားသော Application များ၊ ပုံမှန် Login နေရာများ)။

### **၃။ တိုင်းတာနည်းများနှင့် ကိရိယာများကို ပေါင်းစပ်အသုံးပြုရန်**

- အောက်ပါ နည်းလမ်းများကို ပေါင်းစပ်အသုံးပြုပါ:
  - **Threat Intelligence**။
  - **Data Analytics**။
  - **Manual Analysis**။
  - **Threat Hunting Frameworks**။

### **၄။ အခြားအသင်းများနှင့် ပူးပေါင်းဆောင်ရွက်ရန်**

- **Cloud ပတ်ဝန်းကျင်များ**သည် **ရှုပ်ထွေးပြီး အပြောင်းအလဲများစွာ ဖြစ်နိုင်သော နယ်မြေများဖြစ်သည်**။
- **အသင်းများနှင့် ဆက်သွယ်ခြင်း** ဖြင့် **ပိုမို ပြည့်စုံသော ခြိမ်းခြောက်မှုအမြင်** ရရှိနိုင်သည်။

## ၃။ ခြိမ်းခြောက်မှု ပြသမှု အညွှန်းများ (Indicators of Compromise - IoC)

- **IoC** သည် **လုံခြုံရေးဖြစ်စဉ် တစ်ခုဖြစ်နိုင်သည့် အထောက်အထားများ** ဖြစ်သည်။
- **မကောင်းသော အရာများ**:
  - **Malware**။
  - **Hash Values**။
  - **Domain Names**။
  - **File Names**။
  - **IP Addresses**။

### **IoC ဥပမာများ**

- **မထင်မှတ်သော နယ်မြေများမှ ဝင် / ထွက်နေသော Network Traffic**။
- **မထင်မှတ်သော Login များနှင့် ထူးခြားသော ခွင့်ပြုချက်များ**။
- **စနစ်ထဲတွင် မသိရသေးသော Application အသစ်များ**။
- **Administrator Account များတွင် ထူးခြားသော လှုပ်ရှားမှုများ**။
- **File Hash များနှင့် System File များတွင် ထူးခြားမှုများ**။

## ၄။ အဓိက အချက်များ

- **မည်သည့် စနစ်မှ ၁၀၀% ခြိမ်းခြောက်မှု မတားဆီးနိုင်ပါ**။
- **ကာကွယ်မှု အမျိုးမျိုး သုံးစွဲခြင်းဖြင့် ခြိမ်းခြောက်မှုများကို မဖြစ်မနေလျှော့ချနိုင်သည်**။
- **Threat Hunting သည် ခြိမ်းခြောက်မှုများကို စောစောရှာနိုင်သည့် အကျိုးရှိသော နည်းလမ်းဖြစ်လာသည်**။
- **Threat Hunting လုပ်ငန်းစဉ်များကို နားလည်ခြင်းဖြင့် မကောင်းမှုလုပ်သူများကို တိုက်ခိုက်နိုင်မည်**။
