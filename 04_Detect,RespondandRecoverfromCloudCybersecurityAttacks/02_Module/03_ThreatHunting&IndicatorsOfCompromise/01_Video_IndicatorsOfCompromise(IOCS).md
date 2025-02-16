# Indicators of compromise (IOCS)

[Indicators of compromise (IOCS) 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/ABRcj/indicators-of-compromise-iocs)

# **Identifying and Managing Indicators of Compromise (IOCs)**

## **English Version**

### **Introduction**

How do you know if your system has been compromised? There are several methods to identify **potential security incidents**. One of the most fundamental components of security monitoring is **Indicators of Compromise (IOCs)**.

### **What Are Indicators of Compromise (IOCs)?**

IOCs are **observable pieces of evidence** that suggest a **potential security breach** has occurred in a system or network.

#### **Understanding IOCs: A Simple Analogy**

IOCs are similar to **smoke**—when you see smoke, it may indicate a fire. Likewise, IOCs act as **early warning signs** that a system might be compromised. Detecting IOCs early is crucial in **preventing threats** and securing Cloud environments.

### **How IOCs Work**

IOCs **link specific data** to **known malicious activities, processes, or tools**. These include:

- **Hash values** – Unique file signatures that can indicate malware.
- **IP addresses** – Identifying suspicious or blacklisted sources.
- **Domain names** – Recognizing malicious websites used in attacks.
- **Compromised tools** – Detecting unauthorized software or scripts.

### **Example of an IOC**

A security analyst receives an **alert** that a new file was created on a system. Upon investigation, the:

1. **File hash matches a known malware signature**
2. **Source IP address matches a known malicious entity**

Both the **file hash and IP address** are IOCs that signal a possible security threat.

#### **Important Note:**

Not all IOCs confirm an **actual attack**—some may be **false positives**. However, **monitoring IOCs is essential** for identifying real threats.

---

## **Best Practices for Managing IOCs**

As a Cloud security professional, it's important to know how to **effectively handle IOCs**. Here are five best practices:

### **1. Proactive Monitoring**

- **Continuously monitor systems and networks**
- **Fine-tune detection rules** to identify suspicious activities
- **Set up real-time alerts** for unusual behavior

### **2. Thorough Investigation**

- **Gather all relevant information** about an IOC
- **Analyze surrounding events** to determine if it’s a real threat
- **Be systematic and avoid jumping to conclusions**

### **3. Risk Assessment**

- **Identify affected systems and data**
- **Assess the potential impact** on your organization
- **Prioritize response efforts based on severity**

### **4. Timely Response**

- **Respond quickly to confirmed threats**
- **Implement patches, remove malware, or isolate compromised systems**
- **Activate the **incident response process** when necessary**

### **5. Documentation**

- **Record IOCs, their risks, and impacts**
- **Keep detailed notes to improve future investigations**
- **Share insights with security teams** to enhance threat intelligence\*\*

---

## **Tools for Managing IOCs**

Google Cloud offers multiple **security tools** to help detect and respond to IOCs:

### **Chronicle SIEM & VirusTotal**

- **Chronicle SIEM:** Collects and analyzes event data to identify IOCs.
- **VirusTotal:** Integrates with Chronicle SIEM to provide **threat context, reputation data, and attack relationships** between files, URLs, and domains.

### **Security Command Center (SCC)**

SCC provides:

- **Security services and partner integrations**
- **Threat detection and vulnerability management**
- **Visibility into potential attack vectors**

By using these tools, organizations can **enhance their ability to detect, investigate, and respond to threats**.

---

## **Conclusion**

Understanding **Indicators of Compromise (IOCs)** enables Cloud security professionals to:  
✅ **Detect potential security breaches early**  
✅ **Investigate and respond efficiently**  
✅ **Strengthen overall Cloud security**

By implementing **best practices** and using **advanced security tools**, you can proactively protect your **Cloud environment from cyber threats**.

---

# **Burmese Version**

# **Compromise ဖြစ်နိုင်မှုကို အစောပိုင်းက ခြွင်းချက်ဖော်ထုတ်ခြင်း (IOCs)**

## **မိတ်ဆက်**

သင့်စနစ်ထဲတွင် **လုံခြုံရေး ခြိမ်းခြောက်မှု** တစ်ခုဖြစ်ပေါ်ခဲ့ကြောင်း **မည်သို့ သိနိုင်မလဲ?** Security ခြိမ်းခြောက်မှုများကို **သိရှိရန် နည်းလမ်းများ** ရှိသည်။ ထိုနည်းလမ်းများထဲမှ အဓိက တစ်ခုမှာ **Indicators of Compromise (IOCs)** ဖြစ်သည်။

---

## **Indicators of Compromise (IOCs) ဆိုတာဘာလဲ?**

IOCs သည် **လုံခြုံရေး ခြိမ်းခြောက်မှု ဖြစ်နိုင်ကြောင်း ခြွင်းချက်ပြသသော အထောက်အထားများ** ဖြစ်သည်။

### **ဥပမာ - Smoke နှင့် IOC**

🔥 **IOCs သည် ချိုးဖောက်မှုများကို အစောပိုင်းက သတိပေးသည်။**  
🚨 **မီးခိုးတွေ့ရလျှင် မီးလောင်မှု ဖြစ်နိုင်သည့် အလားအလာရှိသည်။**  
💻 **IOCs တွေ့လျှင် system တစ်ခုကို hack ခံခဲ့နိုင်သည်။**

---

## **IOCs မည်သို့ လုပ်ဆောင်သနည်း?**

IOCs သည် **မကောင်းသည့် လုပ်ဆောင်မှုများနှင့် ပတ်သက်မှုရှိသော data များကို ချိတ်ဆက်ပေးသည်။**

🔍 **IOCs အမျိုးအစားများ**

- **Hash values** – Malware ကို ခြွင်းချက်ဖော်ထုတ်နိုင်သည်
- **IP addresses** – Suspicious IP များကို သိနိုင်သည်
- **Domain names** – Phishing websites များကို ခြွင်းချက်ဖော်ထုတ်နိုင်သည်
- **Compromised tools** – Unauthorized software များကို သိနိုင်သည်

---

## **ဥပမာ: IOC တစ်ခုကို မည်သို့ သတိပြုမလဲ?**

Security analyst **alert တစ်ခု ရရှိသည်။**

1. **File hash တစ်ခုသည် Malware တစ်ခုနှင့် ကိုက်ညီနေသည်။**
2. **IP address သည် အန္တရာယ်ရှိသော network မှ ဖြစ်သည်။**

📌 **File hash နှင့် IP address** နှစ်ခုစလုံးသည် IOCs ဖြစ်သည်။

---

## **IOCs ကို စီမံခန့်ခွဲရန် အကောင်းဆုံး လုပ်ဆောင်နည်း (Best Practices)**

### ✅ **1. Proactive Monitoring**

✔ **System နှင့် network များကို အမြဲတမ်း စောင့်ကြည့်ပါ။**  
✔ **Detection rules များကို ပြင်ဆင်ပြီး suspicious activities များကို ခြွင်းချက်ဖော်ထုတ်ပါ။**

### ✅ **2. Thorough Investigation**

✔ **IOCs နှင့် ပတ်သက်သော အချက်အလက်များကို စုစည်းပါ။**  
✔ **နောက်ခံအချက်အလက်များကို စစ်ဆေးပြီး တကယ် hack ဖြစ်သည် မဖြစ်သည် သေချာစေရန် စူးစမ်းပါ။**

### ✅ **3. Risk Assessment**

✔ **အန္တရာယ်ရှိသော system နှင့် data များကို ခြွင်းချက်ဖော်ထုတ်ပါ။**  
✔ **သက်သာသော ခြိမ်းခြောက်မှု vs အထိခိုက်မှု အဆင့်များကို စိစစ်ပါ။**

### ✅ **4. Timely Response**

✔ **ခြိမ်းခြောက်မှုကို သတ်မှတ်ပြီး ချက်ချင်း ပြုပြင်ပါ။**  
✔ **Security patch များထည့်သွင်းခြင်း၊ system quarantine ပြုလုပ်ခြင်းစသည်ဖြင့် တုန့်ပြန်ပါ။**

### ✅ **5. Documentation**

✔ **IOCs, သူတို့၏ risk, impact များကို မှတ်တမ်းတင်ပါ။**  
✔ **Security team နှင့် မျှဝေပြီး အနာဂတ် စောင့်ကြည့်မှုများ ပိုမိုကောင်းမွန်စေရန် ပြင်ဆင်ပါ။**

---

## **Google Cloud Tools များ**

🔹 **Chronicle SIEM & VirusTotal**  
🔹 **Security Command Center (SCC)**

💡 **Cloud Security ကို အစောပိုင်းက ခြွင်းချက်ဖော်ထုတ်နိုင်ရန် Google Cloud Security Tools များကို အသုံးပြုပါ။**
