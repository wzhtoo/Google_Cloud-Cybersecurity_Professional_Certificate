# Guide to backups and VM recovery

[Guide to backups and VM recovery 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/supplement/l3pLD/guide-to-backups-and-vm-recovery)

## PDF File

[Guide to backups and VM recovery.pdf 🔗](https://1drv.ms/b/c/526c45566c8c239a/EfnnkzsqFURBtMoxAEct7YIBD6wqMRE49IxMJu0gU0bycg?e=khPBkW)

# The role of BCDR tools

## Introduction

- **English**: So far, you’ve learned that business continuity and disaster recovery (BCDR) tools can range from BCDR plan builders and backup and restore utilities, to sophisticated software that handles data center failovers.
- **Burmese**: ယခုအချိန်အထိ၊ လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှုနှင့် ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး (BCDR) ကိရိယာများသည် BCDR အစီအစဉ်ရေးဆွဲသူများနှင့် အရန်ကူးခြင်းနှင့် ပြန်လည်ရယူခြင်း အသုံးအဆောင်များမှသည် ဒေတာစင်တာ failover များကို ကိုင်တွယ်သည့် ခေတ်မီဆော့ဖ်ဝဲလ်အထိ ရှိနိုင်ကြောင်း သင်လေ့လာခဲ့ပြီးဖြစ်သည်။

- **English**: BCDR tools aren’t just pieces of software, they're what you, as a cloud security professional, can use to ensure your business continues to run smoothly and efficiently during disaster recovery.
- **Burmese**: BCDR ကိရိယာများသည် ဆော့ဖ်ဝဲလ် အပိုင်းအစများသာ မဟုတ်ပါ၊ ၎င်းတို့သည် သင်၊ cloud လုံခြုံရေး ကျွမ်းကျင်သူတစ်ဦးအနေဖြင့်၊ ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေးအတွင်း သင်၏ လုပ်ငန်းကို ချောမွေ့စွာနှင့် ထိရောက်စွာ ဆက်လက်လည်ပတ်နိုင်ကြောင်း သေချာစေရန် အသုံးပြုနိုင်သည့်အရာများဖြစ်သည်။

---

## BCDR Categories and Tools

- **English**: In this reading, you’ll learn about BCDR categories and some common BCDR tools and their key features.
- **Burmese**: ဤစာဖတ်ခြင်းတွင်၊ သင်သည် BCDR အမျိုးအစားများနှင့် ဘုံ BCDR ကိရိယာအချို့နှင့် ၎င်းတို့၏ အဓိကအင်္ဂါရပ်များအကြောင်း လေ့လာရပါမည်။

- **English**: Then, you’ll learn the general steps to using the all-important BCDR recovery toolset for any cloud-based operation.
- **Burmese**: ထို့နောက်၊ မည်သည့် cloud အခြေခံ လည်ပတ်မှုအတွက်မဆို အလွန်အရေးကြီးသော BCDR ပြန်လည်ထူထောင်ရေး ကိရိယာအစုံကို အသုံးပြုရန် အထွေထွေအဆင့်များကို သင်လေ့လာရပါမည်။

- **English**: Next, you’ll inspect Google Cloud services that aid in disaster recovery.
- **Burmese**: နောက်တွင်၊ ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေးတွင် အထောက်အကူဖြစ်စေသော Google Cloud ဝန်ဆောင်မှုများကို သင်စစ်ဆေးပါမည်။

---

## Automation and Google Cloud

- **English**: You’ll also explore some of the many ways you can automate the tasks involved in recovery, including a scenario using Google Cloud Backup and Disaster Recovery (DR) to help a business minimize downtime and get back to business as quickly as possible.
- **Burmese**: လုပ်ငန်းတစ်ခုအား ရပ်တန့်ချိန်ကို အနည်းဆုံးဖြစ်စေပြီး အမြန်ဆုံး လုပ်ငန်းသို့ ပြန်လည်ရောက်ရှိစေရန် ကူညီရန်အတွက် Google Cloud Backup and Disaster Recovery (DR) ကို အသုံးပြုသည့် အခြေအနေတစ်ခုအပါအဝင်၊ ပြန်လည်ထူထောင်ရေးတွင် ပါဝင်သည့် အလုပ်များကို အလိုအလျောက်လုပ်ဆောင်နိုင်သည့် နည်းလမ်းများစွာကိုလည်း သင်လေ့လာပါမည်။

# BCDR categories

## BCDR categories

- **English**: BCDR tools can be categorized into two main types:
  - On-premises BCDR tools: These tools are installed and run on the organization's own hardware and software.
  - Cloud-based BCDR tools: These tools are hosted and managed by a cloud services provider.
- **Burmese**: BCDR ကိရိယာများကို အဓိက အမျိုးအစား နှစ်မျိုး ခွဲခြားနိုင်သည်-
  - On-premises BCDR ကိရိယာများ- ဤကိရိယာများကို အဖွဲ့အစည်း၏ ကိုယ်ပိုင် ဟာ့ဒ်ဝဲလ်နှင့် ဆော့ဖ်ဝဲလ်တွင် တပ်ဆင်ပြီး လုပ်ဆောင်သည်။
  - Cloud-based BCDR ကိရိယာများ- ဤကိရိယာများကို cloud ဝန်ဆောင်မှုပေးသူမှ ဟိုတ်နှင့် စီမံခန့်ခွဲသည်။

---

# BCDR common tools and key features

## BCDR common tools and key features

- **English**: BCDR tools can help you and your cloud security team make and execute a plan to restore your systems and get data back online. The tools ensure you can continue normal operations and continue serving your users without any interruption. There are a variety of different BCDR tools available, each with its own specific purpose.
- **Burmese**: BCDR ကိရိယာများသည် သင့်နှင့် သင့် cloud လုံခြုံရေးအဖွဲ့အား သင့်စနစ်များကို ပြန်လည်ရယူရန်နှင့် ဒေတာကို အွန်လိုင်းသို့ ပြန်လည်ရယူရန် အစီအစဉ်တစ်ခုပြုလုပ်ရန်နှင့် အကောင်အထည်ဖော်ရန် ကူညီပေးနိုင်သည်။ ကိရိယာများသည် သင့်အား ပုံမှန်လုပ်ငန်းဆောင်တာများကို ဆက်လက်လုပ်ဆောင်နိုင်ပြီး မည်သည့် အနှောင့်အယှက်မှမရှိဘဲ သုံးစွဲသူများကို ဆက်လက်ဝန်ဆောင်မှုပေးနိုင်ကြောင်း သေချာစေသည်။ ရရှိနိုင်သော မတူညီသော BCDR ကိရိယာများစွာရှိပြီး တစ်ခုစီတွင် ၎င်း၏ သီးခြားရည်ရွယ်ချက်ရှိသည်။

- **English**: Some common BCDR tools and their key features include:
- **Burmese**: ဘုံ BCDR ကိရိယာအချို့နှင့် ၎င်းတို့၏ အဓိကအင်္ဂါရပ်များ ပါဝင်သည်-

  - **English**: Backup and recovery tools: Use these tools in the event of a data loss to back up and restore data on a variety of different storage media, including on-premises storage, cloud storage, and tape.
  - **Burmese**: အရန်ကူးခြင်းနှင့် ပြန်လည်ရယူခြင်း ကိရိယာများ- ဤကိရိယာများကို ဒေတာဆုံးရှုံးမှုဖြစ်ပွားပါက on-premises သိုလှောင်မှု၊ cloud သိုလှောင်မှုနှင့် တိပ်အပါအဝင် မတူညီသော သိုလှောင်မှု မီဒီယာအမျိုးမျိုးတွင် ဒေတာကို အရန်ကူးရန်နှင့် ပြန်လည်ရယူရန် အသုံးပြုပါ။

  - **English**: Disaster recovery automation tools: Use these tools to automate the process to restore systems and data to a working state after a disaster, or other disruptive event. You can also use these tools to support a variety of different disaster recovery strategies, including:
    - Failover: Helps protect systems from failure
    - Failback: Restores the latest data from the backup image to the production application, restores the application from the latest data, and then performs a clean up
    - Replication: The process of continuously creating copies of data to multiple locations to support availability
  - **Burmese**: ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး အလိုအလျောက် ကိရိယာများ- ဤကိရိယာများကို ဘေးအန္တရာယ် သို့မဟုတ် အခြား အနှောင့်အယှက်ဖြစ်စေသော အဖြစ်အပျက်တစ်ခုပြီးနောက် စနစ်များနှင့် ဒေတာကို အလုပ်လုပ်နိုင်သော အခြေအနေသို့ ပြန်လည်ရယူရန် လုပ်ငန်းစဉ်ကို အလိုအလျောက်လုပ်ဆောင်ရန် အသုံးပြုပါ။ ဤကိရိယာများကို မတူညီသော ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး နည်းဗျူဟာအမျိုးမျိုးကို ပံ့ပိုးရန်အတွက်လည်း အသုံးပြုနိုင်သည်၊ ဥပမာ-

    - Failover: စနစ်များကို ပျက်ကွက်မှုမှ ကာကွယ်ရန် ကူညီပေးသည်။
    - Failback: အရန်ကူးပုံရိပ်မှ နောက်ဆုံးဒေတာကို ထုတ်လုပ်မှု application သို့ ပြန်လည်ရယူခြင်း၊ application ကို နောက်ဆုံးဒေတာမှ ပြန်လည်ရယူခြင်းနှင့် ထို့နောက် သန့်ရှင်းရေးလုပ်ဆောင်ခြင်း။
    - Replication: ရရှိနိုင်မှုကို ပံ့ပိုးရန်အတွက် ဒေတာ၏ မိတ္တူများကို တည်နေရာများစွာသို့ စဉ်ဆက်မပြတ် ဖန်တီးခြင်း လုပ်ငန်းစဉ်။

  - **English**: Business continuity (BC) tools: Use these tools to develop BC management plans to help maintain your business operations during and after a disaster. You can also use these tools to generate BCDR reports on activities and track performance in order to identify BCDR plan progress and areas for improvement.
  - **Burmese**: လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှု (BC) ကိရိယာများ- ဤကိရိယာများကို ဘေးအန္တရာယ်အတွင်းနှင့် အပြီးတွင် သင်၏ လုပ်ငန်းလည်ပတ်မှုများကို ထိန်းသိမ်းရန် ကူညီရန် BC စီမံခန့်ခွဲမှု အစီအစဉ်များကို ဖန်တီးရန် အသုံးပြုပါ။ BCDR အစီအစဉ် တိုးတက်မှုနှင့် တိုးတက်မှု ဧရိယာများကို ခွဲခြားသတ်မှတ်ရန်အတွက် လှုပ်ရှားမှုများအပေါ် BCDR အစီရင်ခံစာများကို ထုတ်လုပ်ရန်နှင့် စွမ်းဆောင်ရည်ကို ခြေရာခံရန်အတွက်လည်း ဤကိရိယာများကို အသုံးပြုနိုင်သည်။

# How to run a BCDR recovery tool

## How to run a BCDR recovery tool

- **English**: To run a BCDR recovery tool, you’ll typically need to:
- **Burmese**: BCDR ပြန်လည်ထူထောင်ရေး ကိရိယာကို အသုံးပြုရန်၊ သင်သည် အများအားဖြင့် လိုအပ်သည်-

  1. **English**: Identify the affected systems and data: The first step is to identify the systems and data that have been affected by the disruptive event. This may involve running reports or manually checking systems.

  - **Burmese**: ထိခိုက်ခံရသော စနစ်များနှင့် ဒေတာကို ခွဲခြားသတ်မှတ်ပါ- ပထမအဆင့်မှာ အနှောင့်အယှက်ဖြစ်စေသော အဖြစ်အပျက်ကြောင့် ထိခိုက်ခံရသော စနစ်များနှင့် ဒေတာကို ခွဲခြားသတ်မှတ်ရန်ဖြစ်သည်။ ၎င်းတွင် အစီရင်ခံစာများ ပြုလုပ်ခြင်း သို့မဟုတ် စနစ်များကို ကိုယ်တိုင်စစ်ဆေးခြင်းတို့ ပါဝင်နိုင်သည်။

  2. **English**: Select the appropriate recovery option: Once you’ve identified the affected systems and data, you need to select the appropriate recovery option. This will depend on the type of disruptive event and the severity of the damage.

  - **Burmese**: သင့်လျော်သော ပြန်လည်ထူထောင်ရေး ရွေးချယ်မှုကို ရွေးချယ်ပါ- ထိခိုက်ခံရသော စနစ်များနှင့် ဒေတာကို သင်ခွဲခြားသတ်မှတ်ပြီးသည်နှင့် သင့်လျော်သော ပြန်လည်ထူထောင်ရေး ရွေးချယ်မှုကို ရွေးချယ်ရန် လိုအပ်ပါသည်။ ၎င်းသည် အနှောင့်အယှက်ဖြစ်စေသော အဖြစ်အပျက် အမျိုးအစားနှင့် ပျက်စီးမှု၏ ပြင်းထန်မှုအပေါ် မူတည်ပါသည်။

  3. **English**: Run the recovery tool: Once you’ve selected the appropriate recovery option, you can run the BCDR recovery tool. The tool will automate the recovery process, restoring the affected systems and data to their previous state.

  - **Burmese**: ပြန်လည်ထူထောင်ရေး ကိရိယာကို အသုံးပြုပါ- သင့်လျော်သော ပြန်လည်ထူထောင်ရေး ရွေးချယ်မှုကို သင်ရွေးချယ်ပြီးသည်နှင့် BCDR ပြန်လည်ထူထောင်ရေး ကိရိယာကို အသုံးပြုနိုင်သည်။ ကိရိယာသည် ပြန်လည်ထူထောင်ရေး လုပ်ငန်းစဉ်ကို အလိုအလျောက်လုပ်ဆောင်ပြီး ထိခိုက်ခံရသော စနစ်များနှင့် ဒေတာကို ၎င်းတို့၏ ယခင်အခြေအနေသို့ ပြန်လည်ရယူပေးမည်ဖြစ်သည်။

  4. **English**: Test the recovered systems and data: Once the recovery process is complete, you need to test the recovered systems and data to ensure that they’re functioning properly.

  - **Burmese**: ပြန်လည်ရယူထားသော စနစ်များနှင့် ဒေတာကို စမ်းသပ်ပါ- ပြန်လည်ထူထောင်ရေး လုပ်ငန်းစဉ် ပြီးဆုံးသည်နှင့် ၎င်းတို့ ကောင်းမွန်စွာ အလုပ်လုပ်ကြောင်း သေချာစေရန်အတွက် ပြန်လည်ရယူထားသော စနစ်များနှင့် ဒေတာကို စမ်းသပ်ရန် လိုအပ်ပါသည်။

- **English**: Pro tip: It’s important to test your BCDR recovery plan regularly with logging and monitoring to ensure that it’s working as expected. This will help you identify any potential problems before they occur in a real-world disaster.
- **Burmese**: ကျွမ်းကျင်သူ အကြံပြုချက်- သင်၏ BCDR ပြန်လည်ထူထောင်ရေး အစီအစဉ်ကို မျှော်လင့်ထားသည့်အတိုင်း အလုပ်လုပ်ကြောင်း သေချာစေရန်အတွက် မှတ်တမ်းတင်ခြင်းနှင့် စောင့်ကြည့်ခြင်းဖြင့် ပုံမှန်စမ်းသပ်ရန် အရေးကြီးပါသည်။ ၎င်းသည် ဖြစ်ရပ်မှန် ဘေးအန္တရာယ်တွင် မဖြစ်ပွားမီ ဖြစ်နိုင်ချေရှိသော ပြဿနာများကို ခွဲခြားသတ်မှတ်ရန် သင့်အား ကူညီပေးပါမည်။

# Google Cloud services

## Google Cloud services

- **English**: Google Cloud offers a variety of services that can help businesses implement BCDR plans. Google Cloud categories include Compute, Storage, Big Data / Analysis, and additional Services.
- **Burmese**: Google Cloud သည် လုပ်ငန်းများအား BCDR အစီအစဉ်များ အကောင်အထည်ဖော်ရန် ကူညီနိုင်သော ဝန်ဆောင်မှုအမျိုးမျိုးကို ပေးဆောင်သည်။ Google Cloud အမျိုးအစားများတွင် Compute, Storage, Big Data / Analysis နှင့် အပိုဝန်ဆောင်မှုများ ပါဝင်သည်။

- **English**: Some of the popular Google Cloud services for BCDR include:
  - Cloud Storage: Cloud Storage is a highly durable and scalable object storage service that can be used to store backups of data.
  - Cloud SQL: Cloud SQL is a fully managed database service that offers high availability and disaster recovery features.
  - Cloud DNS: Cloud DNS is a fully managed DNS service that can be used to implement DNS failover.
  - Cloud Load Balancing: Cloud Load Balancing is a fully managed load balancing service that can be used to implement load balancing failover.
  - Compute Engine: A Compute Engine is a secure and customizable compute service that lets you create and run virtual machines on Google’s infrastructure.
  - Kubernetes Engine: A Kubernetes Engine cluster has a control plane and machines called nodes for managing multi-cluster infrastructure and securely running optimized AI workloads.
- **Burmese**: BCDR အတွက် လူကြိုက်များသော Google Cloud ဝန်ဆောင်မှုအချို့ ပါဝင်သည်-

  - Cloud Storage: Cloud Storage သည် ဒေတာ အရန်ကူးမှုများကို သိမ်းဆည်းရန် အသုံးပြုနိုင်သော အလွန်ကြာရှည်ခံပြီး စကေးချဲ့နိုင်သော အရာဝတ္ထု သိုလှောင်မှု ဝန်ဆောင်မှုဖြစ်သည်။
  - Cloud SQL: Cloud SQL သည် မြင့်မားသော ရရှိနိုင်မှုနှင့် ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး အင်္ဂါရပ်များကို ပေးဆောင်သည့် စီမံခန့်ခွဲမှုအပြည့်အဝ ဒေတာဘေ့စ် ဝန်ဆောင်မှုဖြစ်သည်။
  - Cloud DNS: Cloud DNS သည် DNS failover ကို အကောင်အထည်ဖော်ရန် အသုံးပြုနိုင်သော စီမံခန့်ခွဲမှုအပြည့်အဝ DNS ဝန်ဆောင်မှုဖြစ်သည်။
  - Cloud Load Balancing: Cloud Load Balancing သည် load balancing failover ကို အကောင်အထည်ဖော်ရန် အသုံးပြုနိုင်သော စီမံခန့်ခွဲမှုအပြည့်အဝ load balancing ဝန်ဆောင်မှုဖြစ်သည်။
  - Compute Engine: Compute Engine သည် Google ၏ အခြေခံအဆောက်အအုံပေါ်တွင် virtual machine များကို ဖန်တီးပြီး လုပ်ဆောင်နိုင်စေသည့် လုံခြုံပြီး စိတ်ကြိုက်ပြင်ဆင်နိုင်သော compute ဝန်ဆောင်မှုတစ်ခုဖြစ်သည်။
  - Kubernetes Engine: Kubernetes Engine cluster တွင် multi-cluster အခြေခံအဆောက်အအုံကို စီမံခန့်ခွဲရန်နှင့် အကောင်းဆုံးပြုလုပ်ထားသော AI workloads များကို လုံခြုံစွာ လုပ်ဆောင်ရန်အတွက် control plane နှင့် nodes ဟုခေါ်သော စက်များရှိသည်။

- **English**: Note: It’s important to understand that Google Cloud services are not a substitute for a comprehensive BCDR plan. Businesses should develop and implement a BCDR plan that’s tailored to their specific needs.
- **Burmese**: မှတ်ချက်- Google Cloud ဝန်ဆောင်မှုများသည် ပြည့်စုံသော BCDR အစီအစဉ်အတွက် အစားထိုးမဟုတ်ကြောင်း နားလည်ရန် အရေးကြီးပါသည်။ လုပ်ငန်းများသည် ၎င်းတို့၏ သီးခြားလိုအပ်ချက်များနှင့်အညီ BCDR အစီအစဉ်ကို ဖန်တီးပြီး အကောင်အထည်ဖော်သင့်သည်။

---

## Google Cloud Backup and Disaster Recovery (DR)

- **English**: Google Cloud Backup and DR is a BCDR tool that you can use to back up, recover, and test data on Google Cloud. Google Cloud Backup and DR offers a variety of features that can help your security team implement BCDR plans, including the ability to:
- **Burmese**: Google Cloud Backup and DR သည် Google Cloud ပေါ်ရှိ ဒေတာကို အရန်ကူးခြင်း၊ ပြန်လည်ရယူခြင်းနှင့် စမ်းသပ်ခြင်းအတွက် သင်အသုံးပြုနိုင်သော BCDR ကိရိယာတစ်ခုဖြစ်သည်။ Google Cloud Backup and DR သည် သင်၏ လုံခြုံရေးအဖွဲ့အား BCDR အစီအစဉ်များကို အကောင်အထည်ဖော်ရန် ကူညီနိုင်သော အင်္ဂါရပ်အမျိုးမျိုးကို ပေးဆောင်သည်၊ ဥပမာ-

  - **English**: Centralize backup management for various Google Cloud and hybrid workloads.
  - **Burmese**: အမျိုးမျိုးသော Google Cloud နှင့် hybrid workloads များအတွက် အရန်ကူးမှု စီမံခန့်ခွဲမှုကို ဗဟိုပြုပါ။
  - **English**: Create application-aware backups, which capture the state of an application and its data at a specific point in time.
  - **Burmese**: သတ်မှတ်ထားသော အချိန်တွင် application တစ်ခု၏ အခြေအနေနှင့် ၎င်း၏ ဒေတာကို ရယူသည့် application-aware backups များကို ဖန်တီးပါ။
  - **English**: Restore using point-in-time recovery, which allows security teams to restore applications and data to any point in time.
  - **Burmese**: လုံခြုံရေးအဖွဲ့များအား မည်သည့်အချိန်တွင်မဆို application များနှင့် ဒေတာကို ပြန်လည်ရယူနိုင်စေသည့် point-in-time recovery ကို အသုံးပြု၍ ပြန်လည်ရယူပါ။
  - **English**: Automate data replication to multiple regions, which can help protect data using regional disaster recovery strategies, like failover and failback, and be used to improve application performance and availability.
  - **Burmese**: failover နှင့် failback ကဲ့သို့သော ဒေသဆိုင်ရာ ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး နည်းဗျူဟာများကို အသုံးပြု၍ ဒေတာကို ကာကွယ်ရန် ကူညီနိုင်ပြီး application စွမ်းဆောင်ရည်နှင့် ရရှိနိုင်မှုကို မြှင့်တင်ရန်အတွက် အသုံးပြုနိုင်သည့် ဒေသများစွာသို့ ဒေတာ ပြန်လည်ကူးယူခြင်းကို အလိုအလျောက်လုပ်ဆောင်ပါ။
  - **English**: Create immutable backups, which are protected from deletion. This can help prevent data from being accidentally deleted or corrupted.
  - **Burmese**: ဖျက်ခြင်းမှ ကာကွယ်ထားသော ပြောင်းလဲ၍မရသော backups များကို ဖန်တီးပါ။ ၎င်းသည် ဒေတာကို မတော်တဆ ဖျက်ခြင်း သို့မဟုတ် ပျက်စီးခြင်းမှ ကာကွယ်ရန် ကူညီနိုင်သည်။
  - **English**: Create testing and development (test / dev) clones of backups, which can be used to test new software or applications without affecting production data.
  - **Burmese**: ထုတ်လုပ်မှုဒေတာကို မထိခိုက်စေဘဲ ဆော့ဖ်ဝဲလ်အသစ် သို့မဟုတ် application များကို စမ်းသပ်ရန်အတွက် အသုံးပြုနိုင်သည့် backups ၏ စမ်းသပ်ခြင်းနှင့် ဖွံ့ဖြိုးတိုးတက်ခြင်း (test / dev) ပုံတူများကို ဖန်တီးပါ။
  - **English**: Provide reporting and analytics, which can help security teams identify and troubleshoot backup and recovery issues.
  - **Burmese**: လုံခြုံရေးအဖွဲ့များအား အရန်ကူးခြင်းနှင့် ပြန်လည်ရယူခြင်းဆိုင်ရာ ပြဿနာများကို ခွဲခြားသတ်မှတ်ရန်နှင့် ဖြေရှင်းရန် ကူညီနိုင်သော အစီရင်ခံခြင်းနှင့် ခွဲခြမ်းစိတ်ဖြာခြင်းကို ပေးဆောင်ပါ။

# Google Cloud services

## Google Cloud services

- **English**: Here’s one common scenario of how BCDR tools can be used in Google Cloud: A company’s security team uses a cloud services provider to host its customer database. To ensure BC, the company uses a BCDR tool—like Google Cloud Backup and DR—to implement a high availability solution for a database. First, the security team initiates a plan to create database backups on a regular basis on cloud storage. Unfortunately, a disruptive event occurs, and the primary database server fails. Fortunately, the data team is able to use the backup and recovery tool to restore the database to a secondary server. And, the business is able to continue operating with the secondary database until the primary database server is restored and tested to function properly.
- **Burmese**: Google Cloud တွင် BCDR ကိရိယာများကို မည်သို့အသုံးပြုနိုင်သည်ကို ဖော်ပြထားသော ဘုံအခြေအနေတစ်ခုမှာ- ကုမ္ပဏီတစ်ခု၏ လုံခြုံရေးအဖွဲ့သည် ၎င်း၏ ဖောက်သည်ဒေတာဘေ့စ်ကို ဟိုတ်ရန် cloud ဝန်ဆောင်မှုပေးသူကို အသုံးပြုသည်။ BC ကို သေချာစေရန်၊ ကုမ္ပဏီသည် ဒေတာဘေ့စ်အတွက် မြင့်မားသော ရရှိနိုင်မှု ဖြေရှင်းချက်ကို အကောင်အထည်ဖော်ရန် Google Cloud Backup and DR ကဲ့သို့သော BCDR ကိရိယာကို အသုံးပြုသည်။ ပထမဦးစွာ၊ လုံခြုံရေးအဖွဲ့သည် cloud သိုလှောင်မှုတွင် ဒေတာဘေ့စ် backups များကို ပုံမှန်ပြုလုပ်ရန် အစီအစဉ်တစ်ခုကို စတင်သည်။ ကံမကောင်းစွာဖြင့်၊ အနှောင့်အယှက်ဖြစ်စေသော အဖြစ်အပျက်တစ်ခု ဖြစ်ပွားပြီး မူလဒေတာဘေ့စ်ဆာဗာ ပျက်ကွက်သွားသည်။ ကံကောင်းစွာဖြင့်၊ ဒေတာအဖွဲ့သည် ဒေတာဘေ့စ်ကို ဒုတိယဆာဗာသို့ ပြန်လည်ရယူရန်အတွက် အရန်ကူးခြင်းနှင့် ပြန်လည်ရယူခြင်း ကိရိယာကို အသုံးပြုနိုင်ခဲ့သည်။ ထို့အပြင်၊ မူလဒေတာဘေ့စ်ဆာဗာကို ပြန်လည်ရယူပြီး ကောင်းမွန်စွာ အလုပ်လုပ်ကြောင်း စမ်းသပ်သည်အထိ လုပ်ငန်းသည် ဒုတိယဒေတာဘေ့စ်ဖြင့် ဆက်လက်လည်ပတ်နိုင်ခဲ့သည်။

---

## Key takeaways

- **English**: BCDR tools are an essential part of any risk and recovery management strategy. By using the right tools and having a plan in place, organizations can minimize the impact of outages and disasters on their business operations and customer service. Google Cloud offers a variety of services that can be used to support business continuity and disaster recovery, making it a good choice for organizations of all sizes.
- **Burmese**: BCDR ကိရိယာများသည် မည်သည့် စွန့်စားမှုနှင့် ပြန်လည်ထူထောင်ရေး စီမံခန့်ခွဲမှု နည်းဗျူဟာ၏ မရှိမဖြစ် အစိတ်အပိုင်းတစ်ခုဖြစ်သည်။ မှန်ကန်သော ကိရိယာများကို အသုံးပြုခြင်းနှင့် အစီအစဉ်တစ်ခုရှိခြင်းဖြင့်၊ အဖွဲ့အစည်းများသည် ရပ်တန့်မှုများနှင့် ဘေးအန္တရာယ်များ၏ သက်ရောက်မှုကို ၎င်းတို့၏ လုပ်ငန်းလည်ပတ်မှုများနှင့် ဖောက်သည်ဝန်ဆောင်မှုအပေါ် သက်ရောက်မှုကို လျှော့ချနိုင်သည်။ Google Cloud သည် လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှုနှင့် ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေးကို ပံ့ပိုးရန်အတွက် အသုံးပြုနိုင်သော ဝန်ဆောင်မှုအမျိုးမျိုးကို ပေးဆောင်ပြီး ၎င်းသည် အရွယ်အစားအားလုံးရှိ အဖွဲ့အစည်းများအတွက် ကောင်းမွန်သော ရွေးချယ်မှုတစ်ခုဖြစ်သည်။
