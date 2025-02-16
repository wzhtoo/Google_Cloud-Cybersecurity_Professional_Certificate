# How security teams preserve evidence

[How security teams preserve evidence 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/9IfYN/how-security-teams-preserve-evidence)

# **Cybersecurity Evidence Preservation: Process & Best Practices**

## **1. Introduction**

- **IP addresses, authentication attempts, network packets** – all are key **pieces of evidence** in an incident investigation.
- **Preserving evidence** ensures accurate investigations and **legal compliance**.
- **Key requirements for evidence preservation**:
  - **Undamaged & unaltered evidence**.
  - **Proper documentation**.
  - **Following the chain of custody**.

## **2. Chain of Custody: Ensuring Evidence Integrity**

- **Chain of custody** = The process of tracking evidence throughout an investigation.
- **Rules and processes** ensure:
  - **Prevention of unauthorized access**.
  - **No evidence tampering**.
- **Why proper documentation is critical?**
  - **Ensures evidence remains reliable & admissible** in investigations.
  - **Supports legal, insurance, and regulatory requirements**.
  - **Helps organizations prevent further damage or loss**.

## **3. Legal & Ethical Considerations in Evidence Handling**

### **Four Key Legal & Ethical Best Practices**

1. **Understand legal & ethical requirements**.
2. **Balance evidence collection with privacy rights**.
3. **Only collect necessary data**.
4. **Destroy evidence when no longer needed**.

## **4. Incident Investigation Life Cycle & Evidence Preservation**

### **Three Phases of an Investigation**

1. **Identification** – The foundation of evidence collection.
   - **Questions to ask during this phase**:
     - What logs, alerts, or events define this incident?
     - What detection rules were triggered?
     - Is this a **true incident** or a **false positive**?
2. **Incident Control** – Managing and mitigating the attack.
3. **Iterate & Improve** – Learning from the incident and refining security measures.

## **5. Challenges of Preserving Evidence in the Cloud**

- **Cloud environments (VMs, containers) are dynamic** – short-lived resources can disappear quickly.
- **Best practices for Cloud evidence preservation**:
  - **Prompt evidence collection** (e.g., capturing logs before system changes).
  - **Creating snapshots** of virtual machines & containers.
  - **Strict access controls** and **encryption policies**.
  - **Secure logging & restricted access to collected evidence**.

## **6. Google Cloud Tools for Evidence Preservation**

- **Cloud Logging & Cloud Monitoring**
  - **Collect, store, and analyze log data** from multiple sources.
  - **Identify & investigate security incidents** efficiently.
- **Cloud Storage**
  - **IAM (Identity & Access Management) controls for secure evidence storage**.
  - **Object versioning & storage policies to protect data integrity**.
- **Google Backup & Disaster Recovery**
  - **Automatically creates incremental, secure backups**.
  - **Ensures forensic evidence is always available**.

## **7. Conclusion**

- **Proper evidence preservation & documentation** ensures reliable cybersecurity investigations.
- **Legal & ethical guidelines** must be followed to protect data integrity.
- **Cloud security tools help collect, secure, and manage evidence effectively**.
- **With these best practices, you can handle digital evidence like a pro!** 🚀

# **Cybersecurity တွင် သက်သေထောက်ခံမှု ထိန်းသိမ်းခြင်း: လုပ်ငန်းစဉ်နှင့် အကောင်းဆုံး နည်းလမ်းများ**

## **၁။ မိတ်ဆက်**

- **IP Addresses, Authentication Attempts, Network Packets** – စုံစမ်းမှုများတွင် **အရေးကြီးသော သက်သေများ** ဖြစ်သည်။
- **သက်သေထောက်ခံမှု ထိန်းသိမ်းခြင်း** သည် **စုံစမ်းမှုတိကျမှုနှင့် ဥပဒေလိုက်နာမှု** အတွက် မဖြစ်မနေလိုအပ်သည်။
- **သက်သေထောက်ခံမှုအတွက် အဓိကလိုအပ်ချက်များ** –
  - **ပျက်စီးမှုမရှိခြင်း၊ ပြောင်းလဲမှုမရှိခြင်း**။
  - **မှန်ကန်သော မှတ်တမ်းများ ရှိခြင်း**။
  - **Chain of Custody ကို လိုက်နာခြင်း**။

## **၂။ Chain of Custody – သက်သေတည်မြဲမှုကို သေချာစေရန်**

- **Chain of Custody ဆိုသည်မှာ** **စုံစမ်းမှု တစ်ခုလုံးတွင် သက်သေကို မှန်ကန်စွာ ထိန်းသိမ်းခြင်း** ဖြစ်သည်။
- **ထိန်းချုပ်မှု နည်းလမ်းများ** –
  - **မသင့်တင့်သူများ ဝင်ရောက်မှုကို ကာကွယ်ခြင်း**။
  - **သက်သေများ ပြုပြင်ပြောင်းလဲခြင်း မဖြစ်နိုင်အောင် ကာကွယ်ခြင်း**။
- **မှန်ကန်သော မှတ်တမ်းတင်မှု အရေးကြီးမှု** –
  - **သက်သေများကို တရားဝင် အသုံးပြုနိုင်ရန်**।
  - **ဥပဒေရေးရာ၊ အာမခံနှင့် စည်းမျဉ်းများကို ဖြည့်ဆည်းရန်**။
  - **အဖွဲ့အစည်းများအတွက် ထိခိုက်မှုကို လျှော့ချရန်**။

## **၃။ ဥပဒေနှင့် ယုတ္တိမြန်မာစံနှုန်းများ**

### **သက်သေကို ကိုင်တွယ်ရာတွင် လိုက်နာရမည့် အဓိက လုပ်ထုံးလုပ်နည်း ၄ ချက်**

1. **ဥပဒေနှင့် ယုတ္တိမြန်မာလိုက်နာမှုများကို နားလည်ရန်**။
2. **သက်သေစုဆောင်းမှုနှင့် Privacy အခွင့်အရေးများကို ချိန်ညှိရန်**။
3. **လိုအပ်သည့်အချက်များသာ စုဆောင်းရန်**။
4. **အသုံးမလိုတော့သည့် သက်သေများကို ဖျက်ပစ်ရန်**။

## **၄။ Incident Investigation Life Cycle & သက်သေထောက်ခံမှု**

### **စုံစမ်းမှု လုပ်ငန်းစဉ် အဆင့် ၃ ခု**

1. **Identification (ဖော်ထုတ်ခြင်း)** –
   - **ဤအဆင့်တွင် မေးသင့်သော မေးခွန်းများ** –
     - **မည်သည့် Logs, Alerts, Events များဖြင့် တိုက်ခိုက်မှုကို အတည်ပြုနိုင်သည်?**
     - **Detection Rules မည်သို့ ပြုလုပ်ထားသလဲ?**
     - **False Positive ဖြစ်နိုင်ခြင်း ရှိသလား?**
2. **Incident Control (ထိန်းချုပ်မှု)** –
   - **တိုက်ခိုက်မှုကို ထိန်းချုပ်ပြီး ဖြေရှင်းရန်**။
3. **Iterate & Improve (တိုးတက်မှုများ ပြုလုပ်ခြင်း)** –
   - **တိုက်ခိုက်မှုမှ သင်ခန်းစာရယူပြီး လုံခြုံရေးကို မြှင့်တင်ရန်**။

## **၅။ Cloud-Based သက်သေထောက်ခံမှု၏ အထူးပြု ပြဿနာများ**

- **Cloud Environment (VMs, Containers) များသည် ယာယီဖြစ်ပြီး အလိုအလျှောက် ပြောင်းလဲနိုင်သည်**။
- **သက်သေထောက်ခံမှု အကောင်းဆုံး ထိန်းသိမ်းနည်းများ** –
  - **သက်သေများကို ချက်ချင်းစုဆောင်းရန်** (Logs မပြောင်းလဲမီ Snapshots ဖန်တီးခြင်း)။
  - **Virtual Machines & Containers များ၏ Logs များကို သိမ်းဆည်းရန်**။
  - **သက်သေထောက်ခံမှုများကို Encrypt ပြုလုပ်ပြီး ဝင်ရောက်ခွင့်ကို ထိန်းချုပ်ရန်**။

## **၆။ Google Cloud Tools များနှင့် သက်သေထောက်ခံမှု**

- **Cloud Logging & Monitoring** – Logs များကို စုဆောင်း၊ သိမ်းဆည်း၊ စီစစ်နိုင်သည်။
- **Cloud Storage** – IAM Access Control နှင့် Data Integrity ကိုထိန်းသိမ်းနိုင်သည်။
- **Google Backup & Disaster Recovery** – သက်သေများကို Backup ပြုလုပ်ရန် အသုံးပြုနိုင်သည်။

## **၇။ သတ်မှတ်ချက်**

- **သက်သေထောက်ခံမှုကို မှန်ကန်စွာ သိမ်းဆည်းခြင်းသည် လုံခြုံရေး စုံစမ်းမှုအတွက် မဖြစ်မနေလိုအပ်သည်**။
- **Cloud Tools များသည် သက်သေများကို ထိရောက်စွာ သိမ်းဆည်းနိုင်ရန် အထောက်အကူပြုသည်**။
- **ဤနည်းလမ်းများဖြင့် သင်သည် Digital Evidence ကို အကြမ်းမဖျက်ဘဲ ကိုင်တွယ်နိုင်မည်!** 🚀
