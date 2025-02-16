# Lockheed Martin’s Cyber Kill Chain® in practice

[Lockheed Martin’s Cyber Kill Chain® in practice 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/supplement/5j2ir/lockheed-martins-cyber-kill-chain-r-in-practice)

## PDF file

[Lockheed Martin’s Cyber Kill Chain® in practice.pdf 🔗](https://1drv.ms/b/c/526c45566c8c239a/ETgglYe0hWBIu15xhjF5TmkBT-RTsibu9cwN3yU3DC5Aiw?e=7nvGbs)

# Lockheed Martin's Cyber Kill Chain® in

practice
So far, you've learned that the Lockheed Martin Cyber Kill Chain® is a framework used to help
analyze security attacks. The goal of using the Cyber Kill Chain® is to create actionable threat
intelligence that can be used to improve security defenses, measure defensive performance,
and plan for future prevention. These goals can be achieved by mapping attacks to each step
of the Cyber Kill Chain®, and analyzing them to identify patterns. The steps of the Cyber Kill
Chain® include:

1. Reconnaissance
2. Weaponization
3. Delivery
4. Exploitation
5. Installation
6. Command and control
7. Actions on objective
   In this reading, you'll explore the Lockheed Martin Cyber Kill Chain® in more detail through a
   scenario involving compromised cloud IAM credentials.

# Applying the Lockheed Martin Cyber Kill Chain® to a Cloud Threat Scenario

## Overview

- **English**: Malicious actors often target cloud environments using compromised credentials. This walkthrough applies the Cyber Kill Chain® framework to a cloud intrusion scenario.
- **Burmese**: အန္တရာယ်ရှိသူများသည် cloud environment များကို ခိုးယူထားသော အထောက်အထားများ (ဥပမာ- စကားဝှက်များ၊ cloud access keys) ဖြင့် မကြာခဏ ပစ်မှတ်ထားလေ့ရှိသည်။ ဤဥပမာတွင် Cyber Kill Chain® ကို cloud ချိုးဖောက်မှုဖြစ်စဉ်တစ်ခုနှင့် နှိုင်းယှဉ်ရှင်းပြထားသည်။

---

## 1. Reconnaissance (စူးစမ်းရှာဖွေခြင်း)

### Scenario

- **English**:  
  The attacker researches the target organization’s website, social media, and employee code repositories to identify vulnerabilities.
- **Burmese**:  
  အန္တရာယ်ရှိသူသည် ပစ်မှတ်အဖွဲ့အစည်း၏ ဝက်ဘ်ဆိုက်၊ လူမှုမီဒီယာ၊ နှင့် ဝန်ထမ်း code repositories များကို စူးစမ်းကာ အားနည်းချက်များရှာဖွေသည်။

### Defense Strategies

- **English**:
  - Limit public information exposure.
  - Train employees on data-sharing risks.
  - Monitor for suspicious scanning activity.
- **Burmese**:
  - အများသိသော အချက်အလက်များကို ကန့်သတ်ပါ။
  - ဝန်ထမ်းများကိ် အွန်လိုင်းတွင် အချက်အလက်မျှဝေခြင်း၏ အန္တရာယ်များအကြောင်း သင်ကြားပေးပါ။
  - သံသယဖြစ်ဖွယ် စူးစမ်းမှုများကို စောင့်ကြည့်ပါ။

---

## 2. Weaponization (လက်နိုင်ငယ်ပြင်ဆင်ခြင်း)

### Scenario

- **English**:  
  The attacker crafts a phishing email with malicious links to compromise the employee’s account.
- **Burmese**:  
  အန္တရာယ်ရှိသူသည် ဝန်ထမ်း၏အကောင့်ကို ချိုးဖောက်ရန် phishing email တစ်စောင်ကို ဖန်တီးသည်။

### Defense Strategies

- **English**:
  - Use threat intelligence to track evolving threats.
  - Block malicious payloads via email/web filtering.
- **Burmese**:
  - အန္တရာယ်များကို လိုက်လံစောင့်ကြည့်ရန် threat intelligence ကို အသုံးပြုပါ။
  - မကောင်းသော payload များကို email/web filtering ဖြင့် ပိတ်ပင်ပါ။

---

## 3. Delivery (တိုက်ခိုက်မှုစတင်ခြင်း)

### Scenario

- **English**:  
  The attacker sends a phishing email with a fake login page to steal credentials.
- **Burmese**:  
  အန္တရာယ်ရှိသူသည် စကားဝှက်များခိုးယူရန် အတုအယောင် login page ပါသော phishing email ကို ပို့သည်။

### Defense Strategies

- **English**:
  - Train users to recognize phishing attempts.
  - Deploy email/web filtering tools.
- **Burmese**:
  - phishing ကြိုးစားမှုများကို သိရှိစေရန် သင်တန်းပေးပါ။
  - email/web filtering ကိရိယာများ တပ်ဆင်ပါ။

---

## 4. Exploitation (ချိုးဖောက်အသုံးချခြင်း)

### Scenario

- **English**:  
  The attacker uses stolen credentials to log into the cloud environment and access critical assets.
- **Burmese**:  
  အန္တရာယ်ရှိသူသည် ခိုးယူထားသော အထောက်အထားများဖြင့် cloud environment သို့ ဝင်ရောက်ကာ အရေးပါသော ဒေတာများကို ရယူသည်။

### Defense Strategies

- **English**:
  - Enforce multi-factor authentication (MFA).
  - Apply least-privilege access controls.
  - Use vulnerability management tools.
- **Burmese**:
  - Multi-factor authentication (MFA) ကို အတင်းအကျပ်အသုံးပြုပါ။
  - အခွင့်အာဏာအနည်းဆုံး ဝင်ရောက်မှုကို သတ်မှတ်ပါ။
  - အားနည်းချက်စီမံခန့်ခွဲမှု ကိရိယာများကို အသုံးပြုပါ။

---

## 5. Installation (ဝင်ရောက်နေရာယူခြင်း)

### Scenario

- **English**:  
  The attacker creates new user accounts in the cloud to maintain persistent access.
- **Burmese**:  
  အန္တရာယ်ရှိသူသည် cloud တွင် အကောင့်အသစ်များဖန်တီးကာ အဆက်မပြတ်ဝင်ရောက်နိုင်ရန် ပြင်ဆင်သည်။

### Defense Strategies

- **English**:
  - Patch systems regularly.
  - Deploy intrusion detection systems (IDS).
- **Burmese**:
  - စနစ်များကို ပုံမှန်အပ်ဒိတ်လုပ်ပါ။
  - Intrusion detection systems (IDS) များ တပ်ဆင်ပါ။

---

## 6. Command and Control (ထိန်းချုပ်မှုအဆင့်)

### Scenario

- **English**:  
  The attacker sets up network policies to communicate with a C2 server for further attacks.
- **Burmese**:  
  အန္တရာယ်ရှိသူသည် နောက်ထပ်တိုက်ခိုက်မှုများအတွက် C2 server နှင့် ဆက်သွယ်ရန် နက်ဝပ်မူဝါဒများ သတ်မှတ်သည်။

### Defense Strategies

- **English**:
  - Monitor network traffic for anomalies.
  - Block suspicious outbound traffic.
- **Burmese**:
  - မူမှန်မဟုတ်သော နက်ဝပ်လှိုင်းများကို စောင့်ကြည့်ပါ။
  - သံသယဖြစ်ဖွယ် အပြင်ဘက်သို့ လှိုင်းများကို ပိတ်ပင်ပါ။

---

## 7. Actions on Objective (ရည်မှန်းချက်အောင်မြင်ခြင်း)

### Scenario

- **English**:  
  The attacker copies and exfiltrates sensitive data (e.g., PII) to a C2 server.
- **Burmese**:  
  အန္တရာယ်ရှိသူသည် အရေးကြီးဒေတာများ (ဥပမာ- PII) ကို ကူးယူပြီး C2 server သို့ သယ်ဆောင်သွားသည်။

### Defense Strategies

- **English**:
  - Encrypt data at rest.
  - Restrict access to sensitive storage.
- **Burmese**:
  - သိမ်းဆည်းထားသော ဒေတာများကို စကားဝှက်ဖြင့် ကာကွယ်ပါ။
  - အရေးကြီးသော ဒေတာသို့ ဝင်ရောက်မှုကို ကန့်သတ်ပါ။

---

## Key Takeaways

- **English**:
  - Map threats to the Cyber Kill Chain® to identify defense opportunities.
  - Proactive monitoring and user training are critical.
- **Burmese**:
  - အန္တရာယ်များကို Cyber Kill Chain® နှင့် နှိုင်းယှဉ်ကာ ကာကွယ်ရန် အခွင့်အလမ်းများရှာပါ။
  - ကြိုတင်စောင့်ကြည့်ခြင်းနှင့် ဝန်ထမ်းသင်တန်းများသည် အရေးကြီးသည်။
