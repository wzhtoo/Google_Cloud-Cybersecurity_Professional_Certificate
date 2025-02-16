# Recovery options and measures of success

[Recovery options and measures of success 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/krqLB/recovery-options-and-measures-of-success)

# Disaster Recovery in Cloud Security

## Introduction to Disaster Recovery

- **English**: Disaster recovery ensures business continuity when prevention fails. It requires teamwork, awareness of continuity standards, and efficient corrective measures to restore operations swiftly.
- **Burmese**: ကြိုတင်ကာကွယ်မှုမအောင်မြင်ပါက စီးပွားရေးလုပ်ငန်းများ မပြတ်တောက်စေရန် ဘေးအန္တရာယ်ပြန်လည်ထူထောင်ရေးသည် အရေးကြီးသည်။ ၎င်းတွင် အဖွဲ့လိုက်ပူးပေါင်းဆောင်ရွက်မှု၊ စဉ်ဆက်မပြတ်လည်ပတ်မှုစံနှုန်းများနှင့် လျင်မြန်ထိရောက်သော ပြုပြင်မှုများ ပါဝင်သည်။

---

## Key Recovery Options

### 1. Backup Restoration

- **English**:
  - Restore systems using the most recent stable backup.
  - Example: Google Cloud’s backup tools for rapid data recovery.
- **Burmese**:
  - နောက်ဆုံးတည်ငြိမ်သော backup မှ စနစ်များကို ပြန်လည်တည်ဆောက်ပါ။
  - ဥပမာ- Google Cloud ၏ backup ကိရိယာများဖြင့် ဒေတာမြန်မြန်ပြန်လည်ရယူခြင်း။

### 2. Redundancy

- **English**:
  - Store data copies across multiple zones to prevent single points of failure.
  - Example: Automatically switching to a backup system during failures.
- **Burmese**:
  - ဒေတာများကို zone အမျိုးမျိုးတွင် သိမ်းဆည်းကာ ချို့ယွင်းမှုတစ်ခုတည်းကို ရှောင်ရှားပါ။
  - ဥပမာ- စနစ်ချို့ယွင်းပါက အလိုအလျောက် backup စနစ်သို့ ပြောင်းလဲခြင်း။

### 3. Warm Standby

- **English**:
  - A scaled-down duplicate system runs in the cloud, ready to scale up during disasters.
- **Burmese**:
  - Cloud တွင် အသေးစားပုံစံဖြင့် စနစ်တူကူးယူထားပြီး ဘေးအန္တရာယ်ဖြစ်ပါက အမြန်ချဲ့ထွင်နိုင်သည်။

---

## Disaster Recovery Plan (DRP)

- **English**:
  - A step-by-step guide for responding to disasters, including RPO and RTO metrics.
- **Burmese**:
  - ဘေးအန္တရာယ်တုံ့ပြန်ရန် အဆင့်ဆင့်လမ်းညွှန်နှင့် RPO/RTO အညွှန်းကိန်းများ ပါဝင်သည်။

---

## Measures of Success: RPO & RTO

### 1. Recovery Point Objective (RPO)

- **English**:
  - **Definition**: Maximum acceptable data loss duration.
  - **Example**: A bank needs a low RPO (minutes) to minimize transaction loss.
- **Burmese**:
  - **အဓိပ္ပာယ်**: လက်ခံနိုင်သော ဒေတာဆုံးရှုံးမှုအများဆုံးအချိန်။
  - **ဥပမာ**: ဘဏ်တစ်ခုသည် ငွေလွှဲလုပ်ငန်းဆုံးရှုံးမှုကို လျှော့ချရန် RPO အနည်းဆုံး (မိနစ်ပိုင်း) လိုအပ်သည်။

### 2. Recovery Time Objective (RTO)

- **English**:
  - **Definition**: Target time to restore operations after a disaster.
  - **Example**: A local bookstore may tolerate an RTO of 1-2 days.
- **Burmese**:
  - **အဓိပ္ပာယ်**: ဘေးအန္တရာယ်ပြီးနောက် လုပ်ငန်းပြန်လည်စတင်ရန် လိုအပ်သောအချိန်။
  - **ဥပမာ**: စာအုပ်ဆိုင်တစ်ခုသည် RTO ၁-၂ ရက်ကို လက်ခံနိုင်သည်။

---

## Tools and Strategies

- **English**:
  - **Load Balancers**: Distribute traffic to maintain availability during failures.
  - **Failover Services**: Automatically switch to backup resources.
- **Burmese**:
  - **Load Balancers**: စနစ်ချို့ယွင်းစဉ် ဝန်ဆောင်မှုရရှိရန် လှိုင်းများကို ဖြန့်ဝေပေးသည်။
  - **Failover Services**: အရန်အရင်းအမြစ်များသို့ အလိုအလျောက်ပြောင်းလဲပေးသည်။

---

## Key Takeaways

- **English**:
  - Use RPO/RTO to guide backup frequency and recovery timelines.
  - Combine redundancy, backups, and warm standby for robust recovery.
- **Burmese**:
  - Backup အကြိမ်နှုန်းနှင့် ပြန်လည်ထူထောင်ချိန်ကို RPO/RTO ဖြင့် ညွှန်ကြားပါ။
  - ခိုင်မာသော ပြန်လည်ထူထောင်ရေးအတွက် redundancy၊ backup နှင့် warm standby တို့ကို ပေါင်းစပ်အသုံးပြုပါ။
