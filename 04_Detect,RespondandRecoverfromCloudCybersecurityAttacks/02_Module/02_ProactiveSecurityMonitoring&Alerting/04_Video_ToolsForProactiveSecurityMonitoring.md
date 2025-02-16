# Tools for proactive security monitoring

[Tools for proactive security monitoring 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/fsiKb/tools-for-proactive-security-monitoring)

# **Cloud Security Monitoring with Google Cloud Tools**

## **English Version**

### **Introduction**

Cloud security tools help **identify and mitigate threats** by providing insights into potential security risks. This guide explores how to use **Google Cloud's monitoring tools** for proactive security management.

### **Cloud Logging: A Key Security Tool**

Cloud Logging is a powerful tool that enables Cloud security professionals to:

- **Store, search, analyze, and monitor log data**
- **Set up alerts for security events**
- **Investigate potential threats**

#### **Example Use Case: Investigating Unauthorized Access**

Imagine you suspect a **security breach** where an unauthorized person accessed a **Cloud application**. Your goal is to determine whether **sensitive data** was accessed.

Using **Cloud Logging**, you can:

1. **Query log entries** from the Cloud application.
2. **Filter results** to find unauthorized access attempts.
3. **Analyze timestamps and IP addresses** to track the source.
4. **Generate an alert** to notify the security team.

### **Security Command Center (SCC): Proactive Threat Monitoring**

**SCC** is a **security solution** that helps organizations **improve their security posture** by:

- **Detecting threats**
- **Managing risk**
- **Providing full visibility into Cloud assets**

#### **Why Asset Visibility is Critical**

Cloud environments are **highly scalable and dynamic**, making it difficult to track all assets. Without proper monitoring, organizations risk:

- **Data breaches** due to unknown assets.
- **Misconfigurations** that expose sensitive data.
- **Unauthorized access to critical systems.**

### **Common Cloud Security Issues: Misconfigurations**

One of the most common security risks in the Cloud is **misconfigurations**. SCC helps detect and fix these vulnerabilities.

#### **Example: Exposed Cloud Server**

A media company **accidentally adds a new critical server** to its Cloud environment, containing unreleased video content. However, the **server has an open firewall**, allowing **unrestricted internet traffic**.

1. **SCC immediately detects the misconfiguration.**
2. **An alert is sent to the security team.**
3. **The team applies firewall rules** to block unnecessary internet access.

### **Event Threat Detection: Continuous Monitoring**

**Event Threat Detection** is a **built-in service in SCC** that continuously monitors Cloud environments for security threats.

#### **How It Works:**

1. **Analyzes logs** from the Cloud Logging platform.
2. **Uses predefined detection rules** to identify malicious activities.
3. **Provides real-time alerts** to security teams.

#### **Example: Suspicious Account Login Detection**

A security detection rule can be set up to:

- **Identify unusual login attempts**
- **Block access if suspicious behavior is detected**
- **Alert security teams** for further investigation

### **Conclusion**

Monitoring tools like **Cloud Logging, SCC, and Event Threat Detection** provide **actionable security insights** for Cloud security professionals. By leveraging these tools, organizations can **proactively detect and mitigate threats** before they cause harm.

---

# **Burmese Version**

# **Google Cloud Tools များဖြင့် Cloud လုံခြုံရေး စောင့်ကြည့်ခြင်း**

## **မိတ်ဆက်**

Cloud လုံခြုံရေး tools များသည် **လုံခြုံရေးခြိမ်းခြောက်မှုများကို ဖော်ထုတ်ရန်နှင့် ဖြေရှင်းရန်** အထောက်အကူပြုပါသည်။ ဤလမ်းညွှန်သည် **Google Cloud ၏ Security Tools များကို အသုံးပြု၍** လုံခြုံရေးကို **proactive** အနေနဲ့ စောင့်ကြည့်နိုင်မှုကို ရှင်းလင်းပြသပါမည်။

---

## **Cloud Logging: Cloud Security ၏ အဓိက Tool**

Cloud Logging သည် Cloud security ပညာရှင်များကို **log data များကို သိမ်းဆည်းခြင်း, ရှာဖွေခြင်း, စီစစ်ခြင်း, နှင့် alert ပေးခြင်း** ကို ပြုလုပ်နိုင်စေသည်။

### **ဥပမာ: Unauthorized Access ကို စူးစမ်းဖော်ထုတ်ခြင်း**

ဥပမာအားဖြင့် **Cloud application တစ်ခုသို့ unauthorized user တစ်ဦး** ဝင်ရောက်ခဲ့သည်။

Cloud Logging ကိုအသုံးပြုပြီး –

1. **Application ၏ log entries များကို query လုပ်ပါ။**
2. **Unauthorized login attempt များကို filter လုပ်ပါ။**
3. **IP address နှင့် timestamp များကို စစ်ဆေးပါ။**
4. **Security team ထံသို့ alert ပေးပို့ပါ။**

---

## **Security Command Center (SCC): အန္တရာယ်များကို ကြိုတင်ကာကွယ်ခြင်း**

**SCC သည်** Cloud အတွင်း **လုံခြုံရေးကို တိုးတက်စေသော** security solution တစ်ခုဖြစ်သည်။

- **Security threats များကို စောင့်ကြည့်ခြင်း**
- **Risk များကို စီမံခန့်ခွဲခြင်း**
- **Cloud resources များကို အပြည့်အစုံ ရှာဖွေခြင်း**

### **Cloud Asset Visibility ၏ အရေးကြီးမှု**

Cloud သည် **စွမ်းဆောင်ရည်မြင့်ပြီး dynamic ဖြစ်သောကြောင့်**, **asset များကို ချက်ခြင်းမထိန်းနိုင်လျှင် ခြိမ်းခြောက်မှုများ ပိုမိုဖြစ်နိုင်**သည်။

---

## **Cloud Security ၏ Common Issue – Misconfigurations**

Cloud-based Security ပြဿနာများထဲတွင် အများဆုံးဖြစ်နိုင်သော ခြိမ်းခြောက်မှုမှာ **misconfigurations** ဖြစ်သည်။ SCC သည် **ဤအခက်အခဲကို သတိပေးပြီး ပြုပြင်ရန် ကူညီပေးသည်**။

### **ဥပမာ: Firewall များပွင့်လင်းနေသော Cloud Server**

Media company တစ်ခုသည် **Cloud server အသစ်တစ်ခု** ထည့်သွင်းသည့်အခါ –

- Server သည် **မသန့်ရှင်းသော firewall setting** ရှိသည်။
- Internet မှ **မလိုအပ်သည့် traffic များ လွယ်ကူစွာ ဝင်လာနိုင်သည်**။

SCC သည် **မိနစ်ပိုင်းအတွင်း သတိပေးပြီး, security team သည် ချက်ချင်း firewall rules ကို ပြုလုပ်နိုင်သည်**။

---

## **Event Threat Detection: အန္တရာယ်များကို အမြဲတမ်း စောင့်ကြည့်ခြင်း**

**Event Threat Detection** သည် SCC ထဲတွင် ပါဝင်သည့် **security monitoring tool** ဖြစ်သည်။

### **မည်သို့လုပ်ဆောင်သနည်း?**

1. **Cloud Logging မှ data များကို စီစစ်သုံးသပ်ခြင်း**
2. **သတ်မှတ်ထားသည့် security detection rules များကို အသုံးပြုခြင်း**
3. **Security team များသို့ alert ပေးခြင်း**

---

## **သတ်မှတ်ထားသည့် Security Detection Rule များ**

- **သံသယရှိသော login များကို ပိတ်ပင်ခြင်း**
- **Security team ကို real-time alert ပေးခြင်း**
- **Cloud environment ၏ လုံခြုံမှုကို မြှင့်တင်ခြင်း**

---

## **ချုပ်ဆိုချက်**

Google Cloud ၏ **Cloud Logging, SCC, နှင့် Event Threat Detection** tools များကို အသုံးပြုခြင်းဖြင့် –  
✅ **Cloud ထဲရှိ Security ခြိမ်းခြောက်မှုများကို ကြိုတင်ကာကွယ်နိုင်သည်**  
✅ **Log data များကို စုစည်းပြီး analysis ပြုလုပ်နိုင်သည်**  
✅ **Security team များကို အချက်အလက်ပေးပို့နိုင်သည်**

Cloud Security ကို **အစဉ်မပြတ် စောင့်ကြည့်ခြင်းသည်** ခြိမ်းခြောက်မှုများကို **လျှော့ချနိုင်သည့် အရေးကြီးသော နည်းလမ်းများထဲမှ တစ်ခုဖြစ်သည်**။
