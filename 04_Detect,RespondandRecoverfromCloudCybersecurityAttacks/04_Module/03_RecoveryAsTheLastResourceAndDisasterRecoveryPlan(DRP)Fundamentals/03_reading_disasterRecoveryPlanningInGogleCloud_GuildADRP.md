# Disaster recovery planning in Google Cloud: Build a DRP

[Disaster recovery planning in Google Cloud: Build a DRP 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/supplement/F1UCe/disaster-recovery-planning-in-google-cloud-build-a-drp)

## PDF File

[Disaster recovery planning in Google Cloud: Build a DRP.pdf 🔗](https://1drv.ms/b/c/526c45566c8c239a/ERxrE_mwDc9Eip9yXSWzzSoBjAK8q-5evrWjE9xDuwwIDA?e=pWeouV)

- **English**:

  Disaster recovery planning in Google Cloud: Build a DRP

  So far, you’ve learned that recovery is important as a last resource, and your last line of defense is the Disaster Recovery Plan (DRP). As a cloud security professional, you and your team need to build and manage a cloud-hosted DRP that outlines the steps your team needs to follow to recover critical cloud resources and defines Recovery Point Objectives (RPO) and Recovery Time Objectives (RTO).

  In this reading, you’ll learn more about Google Cloud services and tools you can use to build and design a DRP with RPOs and RTOs.

  **Google Cloud services and tools for building a DRP**

  Here’s a list of some of the services and tools Google Cloud offers, and when you can use each to build a DRP:

  - **Cloud Storage**: Cloud Storage is a highly durable and scalable object storage service that can be used to store backups of your data and workloads. You can use Cloud Storage to create snapshots of your Compute Engine disks, which can then be restored in the event of a disaster. You can also use Cloud Storage to store backups of your Cloud SQL databases.

  - **Cloud Backup and DR**: Cloud Backup and DR is a managed backup and disaster recovery service that provides a centralized way to protect your data and workloads running on Google Cloud and on-premises. Cloud Backup and DR can be used to create and manage backups of your Compute Engine disks, Cloud SQL databases, and Cloud Storage buckets. It can also be used to restore your backups to Google Cloud, or to an on-premises environment.

  - **Cloud Spanner**: Cloud Spanner is a fully managed, mission-critical relational database service that offers transactional consistency at global scale, schemas; SQL (ANSI 2011); automatic, synchronous replication for high availability; and automatic, asynchronous global replication for disaster recovery. Cloud Spanner can be used to store your most critical data and ensure that it’s always available and accessible, even in the event of a disaster.

  - **Cloud Bigtable**: Cloud Bigtable is a fully managed, NoSQL database service for large analytical and operational workloads. Bigtable offers a pay-per-use model, in-memory storage, and in-memory analytics. It also supports synchronous cross-region replication for disaster recovery. Cloud Bigtable can be used to store your large and complex datasets and ensure that they’re always available and accessible, even in the event of a disaster.

  - **Cloud Load Balancing**: Cloud Load Balancing is a load balancer that distributes traffic across multiple servers or instances. Load balancing can be used to improve the performance and availability of your applications. Cloud Load Balancing can be used to distribute traffic across your production and DR environments. This way, if there’s a disaster in your production environment, you can quickly switch to your DR environment without any disruption to your users.

  - **Cloud Interconnect**: Cloud Interconnect is a dedicated, high-performance connection between your on-premises network and Google Cloud. Cloud Interconnect can be used to replicate your data and workloads to Google Cloud for disaster recovery. You can also use Cloud Interconnect to connect your DR environment to your production environment. This way, if there’s a disaster in your production environment, you can quickly switch to your DR environment without any disruption to your users.

  **Designing a DRP with RPOs and RTOs in Google Cloud**

  **DRP design factors**

  When designing a DRP in Google Cloud, it’s important to consider these factors:

  - **RPO**: the maximum acceptable amount of time for data to be lost from an application because of a major incident

    - A low RPO—less than 2 hours—indicates a business can afford little or no data loss time

    - A medium RPO—between 2 and 24 hours—indicates a business can afford little or some data loss time

    - A high RPO—between 1 and 7 days—indicates a business can afford a longer data loss time

  - **RTO**: the target time allowed for the recovery of a service in the event of a disaster

    - A low RTO—between 5 and 60 minutes—indicates a business can afford little or no data loss time

    - A medium RTO—between 1 and 8 hours—indicates a business can afford little or some data loss time

    - A high RTO—between 8 and 24 hours—indicates a business can afford a longer data loss time

  - **Workload requirements**: the requirements of your applications and workloads, including availability, performance, and security

  - **Budget**: the amount of money that you’re willing to spend on your DRP

- **Burmese**:

  Google Cloud တွင် Disaster recovery planning: DRP တစ်ခုတည်ဆောက်ပါ

  ယနေ့အထိ၊ ပြန်လည်ရယူမှုသည် နောက်ဆုံးအရင်းအမြစ်နှင့် သင့်၏ နောက်ဆုံးကာကွယ်ရေးမြောက်သော Disaster Recovery Plan (DRP) သည် အရေးကြီးသည်ကို သင်လေ့လာခဲ့ပါသည်။ Cloud လုံခြုံရေး ပညာရှင်တစ်ဦးအနေဖြင့် သင့်နှင့် သင့်အဖွဲ့သည် အရေးကြီးသော cloud အရင်းအမြစ်များကို ပြန်လည်ရယူရန် လိုက်နာရမည့် လုပ်ဆောင်ချက်များကို ဖော်ပြကာ Recovery Point Objectives (RPO) နှင့် Recovery Time Objectives (RTO) များကို သတ်မှတ်ထားသည့် cloud-hosted DRP တစ်ခုကို တည်ဆောက်၍ စီမံခန့်ခွဲရန် လိုအပ်ပါသည်။

  ဤစာရင်းအသွားတွင်၊ RPO နှင့် RTO များပါဝင်သည့် DRP တစ်ခုကို တည်ဆောက်၍ ဒီဇိုင်းဆွဲရန် အသုံးပြုနိုင်သော Google Cloud ဝန်ဆောင်မှုများနှင့် ကိရိယာများကို လူသိရှင်ကြား ပေးပါမည်။

  **DRP တစ်ခုဆောက်ရန် Google Cloud ဝန်ဆောင်မှုများနှင့် ကိရိယာများ**

  Google Cloud မှ ပံ့ပိုးပေးသည့် ဝန်ဆောင်မှုများနှင့် ကိရိယာများအနက် မှတ်သားရန် အချို့အကြောင်းများနှင့် DRP တစ်ခုတည်ဆောက်ရန် မည်သည့်အခါတွင် သင်အသုံးပြုနိုင်သည့်အချိန်များမှာ–

  - **Cloud Storage**: Cloud Storage သည် သင့်ဒေတာနှင့် workloads များ၏ backup များကို သိမ်းဆည်းရန် အသုံးပြုနိုင်သော ခိုင်မာပြီး အတိုင်းအတာကျယ်ပြန့်သော object storage ဝန်ဆောင်မှုဖြစ်သည်။ Compute Engine disks များ၏ snapshot များကို ဖန်တီးရန် Cloud Storage ကို အသုံးပြုနိုင်ပြီး၊ disaster ဖြစ်ပွားပါက ပြန်လည်ထူထောင်နိုင်သည်။ Cloud Storage ကို သင့် Cloud SQL databases များ၏ backup များကို သိမ်းဆည်းရန်လည်း အသုံးပြုနိုင်သည်။

  - **Cloud Backup and DR**: Cloud Backup and DR သည် Google Cloud နှင့် on-premises များပေါ်တွင် လည်ပတ်သော သင့်ဒေတာနှင့် workloads များကို ကာကွယ်ရန် စင်္ကြံပေးသည့် managed backup နှင့် disaster recovery ဝန်ဆောင်မှုဖြစ်သည်။ Cloud Backup and DR ကို သင့် Compute Engine disks များ၊ Cloud SQL databases များနှင့် Cloud Storage buckets များ၏ backup များကို ဖန်တီးပြီး စီမံခန့်ခွဲရန် အသုံးပြုနိုင်သည်။ ၎င်းကို သင့် backup များကို Google Cloud သို့မဟုတ် on-premises ပတ်ဝန်းကျင်သို့ ပြန်လည်ထူထောင်ရန်လည်း အသုံးပြုနိုင်သည်။

  - **Cloud Spanner**: Cloud Spanner သည် အပြည့်အဝ စီမံခန့်ခွဲထားသော၊ အရေးပါတဲ့ relational database ဝန်ဆောင်မှုဖြစ်ပြီး၊ ကမ္ဘာတစ်ခုလုံးအတိုင်းအတာတွင် transactional consistency ကို ပေးစွမ်းသည်။ Schema များ၊ SQL (ANSI 2011)၊ မြင့်မားသော ရရှိနိုင်ရေးအတွက် အော်တို၊ synchronous replication များနှင့် disaster recovery အတွက် အော်တို၊ asynchronous ကမ္ဘာလုံးဆိုင်ရာ replication များကို ပံ့ပိုးသည်။ Cloud Spanner ကို သင့်အရေးကြီးဆုံးဒေတာများကို သိမ်းဆည်းရန် အသုံးပြုနိုင်ပြီး၊ disaster ဖြစ်ပွားသည့်အခါတွင်တောင် အမြဲရရှိနိုင်စေရန် သေချာစေသည်။

  - **Cloud Bigtable**: Cloud Bigtable သည် အကြီးစား analytical နှင့် operational workloads များအတွက် အပြည့်အဝ စီမံခန့်ခွဲထားသော NoSQL database ဝန်ဆောင်မှုဖြစ်သည်။ Bigtable သည် အသုံးပြုသလောက် ပေးချေနည်းကို ပံ့ပိုးပြီး၊ in-memory storage နှင့် in-memory analytics ကို ပံ့ပိုးသည်။ Disaster recovery အတွက် synchronous cross-region replication ကိုလည်း ပံ့ပိုးသည်။ Cloud Bigtable ကို သင့်အကြီးစားနှင့် ရှုပ်ထွေးသော dataset များကို သိမ်းဆည်းရန် အသုံးပြုနိုင်ပြီး၊ disaster ဖြစ်ပွားသည့်အခါတွင်တောင် အမြဲရရှိနိုင်စေရန် သေချာစေသည်။

  - **Cloud Load Balancing**: Cloud Load Balancing သည် traffic ကို ဆာဗာများ သို့မဟုတ် instances များအကြား ဖြန့်ဝေပေးသော load balancer ဖြစ်သည်။ Load balancing ကို သင့် application များ၏ စွမ်းဆောင်ရည်နှင့် ရရှိနိုင်ရေးကို တိုးတက်စေရန် အသုံးပြုနိုင်သည်။ Cloud Load Balancing ကို သင့်ထုတ်လုပ်မှုနှင့် DR ပတ်ဝန်းကျင်များအကြား traffic ကို ဖြန့်ဝေရန် အသုံးပြုနိုင်သည်။ ဒီလိုဖြင့်၊ သင့်ထုတ်လုပ်မှု ပတ်ဝန်းကျင်တွင် disaster ဖြစ်ပွားပါက၊ သင်၏ သုံးစွဲသူများကို အနှောင့်အယှက်မဖြစ်စေဘဲ သင့် DR ပတ်ဝန်းကျင်သို့ လျင်မြန်စွာ ပြောင်းနိုင်သည်။

  - **Cloud Interconnect**: Cloud Interconnect သည် သင့် on-premises network နှင့် Google Cloud အကြား dedicated, high-performance ချိတ်ဆက်မှုဖြစ်သည်။ Cloud Interconnect ကို disaster recovery အတွက် သင့်ဒေတာနှင့် workloads များကို Google Cloud သို့ အပြန်အလှန် ပြန်လည်စီစဉ်ရန် အသုံးပြုနိုင်သည်။ သင့် DR ပတ်ဝန်းကျင်ကို သင့်ထုတ်လုပ်မှု ပတ်ဝန်းကျင်နှင့် ချိတ်ဆက်ရန်လည်း Cloud Interconnect ကို အသုံးပြုနိုင်သည်။ ဒီလိုဖြင့်၊ သင့်ထုတ်လုပ်မှု ပတ်ဝန်းကျင်တွင် disaster ဖြစ်ပွားပါက၊ သင်၏ သုံးစွဲသူများကို အနှောင့်အယှက်မဖြစ်စေဘဲ သင့် DR ပတ်ဝန်းကျင်သို့ လျင်မြန်စွာ ပြောင်းနိုင်သည်။

  **Google Cloud တွင် RPO များနှင့် RTO များအားဖြင့် DRP တစ်ခုဒီဇိုင်းဆွဲခြင်း**

  **DRP ဒီဇိုင်းလုပ်ရန် အချက်များ**

  Google Cloud တွင် DRP တစ်ခုကို ဒီဇိုင်းဆွဲပြီး ဖန်တီးရာတွင် အောက်ပါအချက်များကို တွေးထင်ရန် အရေးကြီးပါသည်–

  - **RPO**: အရေးပါတဲ့ ဖြစ်ရပ်ကြောင့် application မှ ဒေတာ ပျောက်ဆုံးနိုင်သည့် အမြင့်ဆုံး ခွင့်ပြုနိုင်သော အချိန်

    - RPO အနည်းစား— 2 နာရီ အတွင်း — စီးပွားရေးလုပ်ငန်းသည် ဒေတာ ပျောက်ဆုံးခြင်း အနည်းငယ် သို့မဟုတ် မရှိဖို့ လက်ခံနိုင်ကြောင်းကို ဖော်ပြသည်

    - RPO အလတ်စား— 2 နာရီ မှ 24 နာရီ ကြား — စီးပွားရေးလုပ်ငန်းသည် ဒေတာ ပျောက်ဆုံးခြင်း အနည်းငယ် သို့မဟုတ် အချို့ရှိဖို့ လက်ခံနိုင်ကြောင်းကို ဖော်ပြသည်

    - RPO အမြင့်— 1 နေ့ မှ 7 နေ့ ကြား — စီးပွားရေးလုပ်ငန်းသည် ဒေတာ ပျောက်ဆုံးခြင်း အချိန် ပမာဏ ရာကို လက်ခံနိုင်ကြောင်းကို ဖော်ပြသည်

  - **RTO**: disaster ဖြစ်ပွားသောအခါ ဝန်ဆောင်မှုတစ်ခုကို ပြန်လည်ရယူရန် ခွင့်ပြုထားသော အချိန်

    - RTO အနည်းစား— 5 မိနစ် မှ 60 မိနစ် ကြား — စီးပွားရေးလုပ်ငန်းသည် ဒေတာ ပျောက်ဆုံးခြင်း အနည်းငယ် သို့မဟုတ် မရှိဖို့ လက်ခံနိုင်ကြောင်းကို ဖော်ပြသည်

    - RTO အလတ်စား— 1 နာရီ မှ 8 နာရီ ကြား — စီးပွားရေးလုပ်ငန်းသည် ဒေတာ ပျောက်ဆုံးခြင်း အနည်းငယ် သို့မဟုတ် အချို့ရှိဖို့ လက်ခံနိုင်ကြောင်းကို ဖော်ပြသည်

    - RTO အမြင့်— 8 နာရီ မှ 24 နာရီ ကြား — စီးပွားရေးလုပ်ငန်းသည် ဒေတာ ပျောက်ဆုံးခြင်း အချိန် ပမာဏ ရာကို လက်ခံနိုင်ကြောင်းကို ဖော်ပြသည်

  - **Workload requirements**: သင့် application များနှင့် workloads များ၏ လိုအပ်ချက်များ၊ ရရှိနိုင်ချင်း၊ စွမ်းဆောင်ရည်နှင့် လုံခြုံရေး

  - **Budget**: သင့် DRP အတွက် သင် သုံးစွဲနိုင်ရန် ပြင်ဆင်ထားသော လုပ်ငန်းသုံး စရိတ်ပမာဏ

- **English**:

  Disaster recovery planning in Google Cloud: Build a DRP

  Once you’ve considered the DRP design factors, you need to plan your responses to DR patterns. DR patterns indicate how your system’s site environment can recover from a security incident. There are three parts to the DR pattern: cold, warm, and hot. Here’s an explanation of each, according to the National Institute of Standards and Technology (NIST):

  1. **Cold Site**: A cold site is a backup facility that has the necessary electrical and physical components of a computer facility but doesn’t have the computer equipment in place. The site is ready to receive the necessary replacement computer equipment in the event that the user has to move from their main computing location to an alternate site.

  2. **Warm Site**: A warm site is an environmentally conditioned workspace that’s partially equipped with information systems and telecommunications equipment to support relocated operations in the event of a significant disruption.

  3. **Hot Site**: A hot site is a fully operational offsite data processing facility equipped with hardware and software to be used in the event of an information system disruption.

  These three pattern levels are comparable to how you might respond to an unexpected weather cold front that moves in and turns the temperature outside to ice cold. Here’s an example:

  - **Cold Weather**: Requires you to take immediate action. Your warm clothes are in a different location than you are, so you need to request their quick delivery from their local storage location. You also need time to clean the clothes before you wear them since they haven’t been used recently.

  - **Warm Weather**: Requires you to take action soon. You have a set of warm clothes at your location, but you need time to clean the clothes before you wear them since they haven’t been used recently.

  - **Hot Weather**: Requires you to schedule action in the near future. You have two sets of hot weather clothes at your location, and they’re both kept clean and ready to wear. So if one set is damaged, you have a full, equal set of clothes that you can use right away.

  For more information, please check out this resource: [CISSP Study Guide: Disaster Recovery - Hot, Cold, and Warm Sites](https://resources.infosecinstitute.com/topic/disaster-recovery-hot-cold-warm-sites/).

- **Burmese**:

  Google Cloud တွင် Disaster recovery planning: DRP တစ်ခုတည်ဆောက်ပါ

  DRP ဒီဇိုင်းပုံစံအချက်များကို စဉ်းစားပြီးပြီဆိုသည့်အခါ၊ DR ပုံစံများအပေါ် သင့်တုံ့ပြန်လုပ်ဆောင်ချက်များကို စီမံထုတ်ရပါမည်။ DR ပုံစံများသည် သင့် system ၏ site ပတ်ဝန်းကျင်တစ်ခုကို လုံခြုံရေး ဖြစ်စဉ်တစ်ခုမှ ပြန်လည်ရယူနိုင်စေရန် כיצדပြုလုပ်နိုင်သည်ကို ဖော်ပြသည်။ DR ပုံစံတွင် အစိတ်အပိုင်း သုံးခုရှိသည်။ အအေး၊ ပူနွေး၊ ပူများဖြစ်သည်။ အောက်တွင် National Institute of Standards and Technology (NIST) အရ သည့်တစ်ခုစီကို ရှင်းလင်းပြီးဖော်ပြပါသည်–

  1. **အအေးဆိုဒ် (Cold Site)**: အအေးဆိုဒ်သည် လျှပ်စစ်နှင့် ရုပ်ပိုင်းဆိုင်ရာ computer ဖက်စီလီတစ်ခု၏ ပစ္စည်းကိရိယာ အစိတ်အပိုင်းများကို ပိုင်ဆိုင်ထားသော်လည်း computer ပစ္စည်းကိရိယာများ မရှိသေးသော backup ဆိုင်ရာ လုပ်ငန်းခွင်တစ်ခုဖြစ်သည်။ ဤဆိုဒ်သည် သုံးစွဲသူများသည် ၎င်း၏ မူရင်း computing တည်နေရာမှ အစားထိုးဆိုဒ်သို့ ရွှေ့ပြောင်းရမည့် အရေးပေါ်အခါမျိုးတွင် လိုအပ်သော အစားထိုး computer ပစ္စည်းကိရိယာများကို လက်ခံရန် အဆင်သင့်ဖြစ်၏။

  2. **ပူနွေးဆိုဒ် (Warm Site)**: ပူနွေးဆိုဒ်သည် ပတ်ဝန်းကျင်အနေအထား ကောင်းမွန်သည့် လုပ်ငန်းခွင်ဖြစ်ပြီး အပိုင်းအစ ရှိသည့် information systems နှင့် ဆက်သွယ်ရေးပစ္စည်းကိရိယာများဖြင့် ပံ့ပိုးထားပြီး အနှောင့်အယှက် အရေးကြီး ဖြစ်ပွားသောအခါ ရွှေ့ပြောင်းထားသော လည်ပတ်မှုများကို ကူညီပံ့ပိုးနိုင်သည်။

  3. **ပူရှိန်ဆိုဒ် (Hot Site)**: ပူရှိန်ဆိုဒ်သည် အပြည့်အဝ လည်ပတ်နိုင်သည့် offsite data processing ဖက်စီလီတစ်ခုဖြစ်ပြီး hardware နှင့် software များဖြင့် စုံလင်ပြီး information system အနှောင့်အယှက် ဖြစ်ပွားသောအခါ အသုံးပြုနိုင်သည်။

  ဤသုံးခုသော ပုံစံအဆင့်များကို သင့်အနေန̃ ာ် ခေါ်ဆောင်ထားခြင်းမရှိသည့် အလွန်အေးသော ရာသီဥတု တစ်မျိုး အကျပ်အတည်းကြုံနေရသည့်အခါတွင် တွဲလျက် ပြန်လည်များမြင်နိုင်သည်။ ဥပမာအနေဖြင့်–

  - **အေးသောရာသီဥတု**: ချက်ချင်း လုပ်ဆောင်ရန် လိုအပ်သည်။ သင့်ပူနွေးအဝတ်အစားများသည် သင်ရှိရာနေရာနှင့်မတူသော နေရာတွင် ရှိသည်။ အဆိုပါအဝတ်အစားများကို ၎င်းတို့၏ ဒေသတွင်းသိုလှောင်ရာနေရာမှ လျင်မြန်စွာ ပို့ဆောင်ပေးရန် တောင်းဆိုရန် လိုအပ်သည်။ ထို့အပြင် အဝတ်အစားများသည် မကြာသေးမီကမှ အသုံးမပြုပြီးဖြစ်သောကြောင့် ဝတ်ဆင်ရန် မတိုင်မီ စင်ကြယ်အောင် လုပ်ဆောင်ရန် လိုအပ်သည်။

  - **ပူနွေးသောရာသီဥတု**: မကြာမီ လုပ်ဆောင်ရန် လိုအပ်သည်။ သင့်နေရာတွင် ပူနွေးအဝတ်အစားများရှိပါသော်လည်း မကြာသေးမီကမှ အသုံးမပြုပြီးဖြစ်သောကြောင့် ဝတ်ဆင်ရန် မတိုင်မီ စင်ကြယ်အောင် လုပ်ဆောင်ရန် လိုအပ်သည်။

  - **ပူရှိန်သောရာသီဥတု**: အနာဂတ်အနီးတွင် လုပ်ဆောင်ရန် အစီအစဉ်ဆွဲနိုင်သည်။ သင့်နေရာတွင် ပူရှိန်ရာသီ 衣 ဝတ်အစားအစုံ နှစ်စုံရှိပြီး၊ နှစ်စုံလုံးကို စင်ကြယ်စွာ ထိန်းသိမ်းထားသည်။ ထို့ကြောင့် အစုံတစ်စုံပျက်စီးသွားပါက၊ ချက်ချင်းအသုံးပြုနိုင်သော အပြည့်အစုံ တူညီသည့် အဝတ်အစားအစုံ တစ်စုံ ရှိပါသည်။

  အသေးစိတ် သိရှိလိုပါက ဤအရင်းအမြစ်ကို ကြည့်ရှုပါ– [CISSP Study Guide: Disaster Recovery - Hot, Cold, and Warm Sites](https://www.cybrary.it/blog/disaster-recovery-hot-cold-warm-sites)။

- **English**:

  **Connect DR patterns with RPO and RTO**

  Once you’ve chosen a site, you’re ready to choose the appropriate Google Cloud services and tools to implement your DRP. Here are some examples of how you can use Google Cloud services and tools to design a DRP with different RPOs and RTOs:

  - **Low RPO and low RTO**: Use the **Cloud Backup and Data Recovery (DR) Continuous Data Protection (CDP)** feature, which provides continuous replication of data at the block level, ensuring that the most recent data is immediately available for recovery in the event of a disaster. You can also use the **Replication to Multiple Regions** feature, which provides redundancy and disaster protection. This way, if there’s a disaster in your primary region, you can quickly switch to the secondary region without losing any data. These features are both **hot DR**, meaning they minimize data loss and help achieve a low RPO and RTO.

  - **Medium RPO and medium RTO**: Use **Cloud Storage** to store daily backups of your data, as this is a **warm DR** that can tolerate a few hours of downtime. You can then schedule regular backups and restore your data from the backups in the event of a disaster.

  - **High RPO and high RTO**: Use **Cloud Storage** to store weekly backups of your data to make use of a **cold DR** site. A cold DR site is a replica of your production environment that isn’t kept up to date with your production data. You can then restore your data to the cold DR site in the event of a disaster and start your applications up.

  **Key takeaways**

  When designing a DRP, it’s important to consider your needs related to your RPO and RTO, as well as your DR cold, warm, and hot patterns. Google Cloud offers a variety of services and tools that can help you build a DRP that meets your business’s needs. When you build a DRP, you prepare for the worst. But remember, when your DRP is effective and resilient, you can expect the best outcome.

  **Resources for more information**

  For more information on DRP in Google Cloud, please visit these resources:

  - **Google Cloud Best Practices for Disaster Recovery**: [https://devops.com/cloud-disaster-recovery-best-practices/](https://devops.com/cloud-disaster-recovery-best-practices/)
  - **Google Cloud blog post on best practices for building a DRP**: [https://medium.com/google-cloud/disaster-recovery-on-google-cloud-for-data-part-1-9cf08782bac9](https://medium.com/google-cloud/disaster-recovery-on-google-cloud-for-data-part-1-9cf08782bac9)
  - **Google Cloud Disaster Recovery**: [https://cloud.google.com/backup-disaster-recovery/docs](https://cloud.google.com/backup-disaster-recovery/docs)
  - **Google Cloud Disaster Recovery Planning Guide**: [https://cloud.google.com/architecture/dr-scenarios-planning-guide](https://cloud.google.com/architecture/dr-scenarios-planning-guide)
  - **Google Cloud Disaster Recovery Services**: [https://www.techtarget.com/searchdisasterrecovery/definition/cloud-disaster-recovery-cloud-DR](https://www.techtarget.com/searchdisasterrecovery/definition/cloud-disaster-recovery-cloud-DR)

- **Burmese**:

  **DR ပုံစံများကို RPO နှင့် RTO များနှင့် ဆက်စပ်ပါ**

  ဆိုက်တစ်ခု ရွေးချယ်ပြီးနောက်၊ သင့် DRP ကို လက်တွေ့ဖော်ဆောင်ရန် သင့်အား သင့်သင့်လျော်ရှိသော Google Cloud ဝန်ဆောင်မှုများနှင့် ကိရိယာများကို ရွေးချယ်ရန် အသင့် ဖြစ်ပါသည်။ မူကွဲ RPO များနှင့် RTO များပါဝင်သည့် DRP တစ်ခုကို ဒီဇိုင်းဆွဲရန် Google Cloud ဝန်ဆောင်မှုများနှင့် ကိရိယာများကို ပြင်ဆင်အသုံးပြုနိုင်သည့် ဥပမာအချို့မှာ—

  - **အနည်းဆုံး RPO နှင့် အနည်းဆုံး RTO**: **Cloud Backup and Data Recovery (DR) Continuous Data Protection (CDP)** လုပ္ေဆာင္ခ်က္ကို အသံုးျပဳပါ။ ၎င်းသည် ဒေတာကို block အလိုက် ဆက်တိုက် ရှယ်ယာပြုလုပ်ပေးခြင်းအားဖြင့် အန္တရာယ်ဖြစ်ပွားလျှင် နောက်ဆုံးဒေတာကို ချက်ချင်း ပြန်လည်ရယူနိုင်စေသည်။ သင်၏ မူလဒေသတွင် disaster ဖြစ်ပွားပါက ဒေတာဆုံးရှုံးခြင်းမရှိဘဲ ဒုတိယ ဒေသသို့ လျင်မြန်စွာ ပြောင်းနိုင်ရန် redundancy နှင့် disaster ကာကွယ်မှု ပေးသော **Replication to Multiple Regions** လုပ္ေဆာင္ခ်က္ကိုလည္း အသံုးျပဳႏိုင္ပါသည္။ ဤ features များသည် **ပူရှိန် DR** ဖြစ်ပြီး ဒေတာ ပျောက်ဆုံးမှုကို နည်းစေတတ်ပြီး အနည်းဆုံး RPO နှင့် RTO ရရှိရန် ကူညီပါသည်။

  - **အလတ်စား RPO နှင့် အလတ်စား RTO**: သင့်ဒေတာ၏ နေ့စဉ် backup များကို သိမ်းဆည်းရန် **Cloud Storage** ကို အသုံးပြုပါ။ ဤသည်မှာ အနည်းငယ် downtime ကို ခံယူနိုင်သော **ပူနွေး DR** ဖြစ်သည်။ ထို့နောက် သင်သည် ပုံမှန် backup များကို အချိန်ကြားဖြတ် စီစဉ်၍ disaster ဖြစ်ပွားလျှင် backup များမှ သင့်ဒေတာကို ပြန်လည်ထူထောင်နိုင်သည်။

  - **အမြင့် RPO နှင့် အမြင့် RTO**: သင့်ဒေတာ၏ အပတ်စဉ် backup များကို သိမ်းဆည်းရန် **Cloud Storage** ကို အသုံးပြု၍ **အအေး DR ဆိုဒ်** တစ်ခုအသုံးပြုပါ။ အအေး DR ဆိုဒ်သည် သင့်ထုတ်လုပ်မှုပတ်ဝန်းကျင်၏ replica တစ်ခုဖြစ်ပြီး သင့်ထုတ်လုပ်မှုဒေတာနှင့် အဆက်အသွယ်မပြုနိုင်ပါ။ ဆက်လက်ပြီး ဒေတာကို အအေး DR ဆိုဒ်ထဲသို့ ပြန်လည်ထူထောင်၍ သင့် application များကို စတင်နိုင်ပါသည်။

  **အဓိကယူဆချက်များ**

  DRP တစ်ခုကို ဒီဇိုင်းဆွဲရာတွင် သင့် RPO နှင့် RTO နှင့် စပ်လျဉ်း၍ သင့်လိုအပ်ချက်များကို တွေးခေါ်ရင်း၊ DR အအေး၊ ပူနွေးနှင့် ပူရှိန် ပုံစံများကိုလည်း မှတ်မှန်းပါ။ Google Cloud သည် သင့်စီးပွားရေးအတွက် ကိုက်ညီသော DRP တည်ဆောက်ရန် ကူညီနိုင်သော ဝန်ဆောင်မှုများနှင့် ကိရိယာများ အများအပြား ပံ့ပိုးပေးသည်။ DRP တစ်ခု တည်ဆောက်သောအခါ၊ အဆိုးဆုံးအခြေအနေများအတွက် ပြင်ဆင်ထားပါ။ သို့သော် သင့် DRP သည် ထိရောက်ပြီး ခံနိုင်ရည်ရှိလျှင် အကောင်းဆုံးရလဒ်ကို မျှော်လင့်နိုင်သည်ကို မှတ်လို့ပါ။

  **အသေးစိတ်အချက်အလက်များအတွက် အရင်းအမြစ်များ**

  Google Cloud တွင် DRP နှင့် စပ်လျဉ်း၍ အသေးစိတ်သိရှိလိုပါက အောက်ပါ အရင်းအမြစ်များကို လေ့လာပါ—

  - **Disaster Recovery အတွက် Google Cloud အကောင်းဆုံးကျင့်ဝတ်များ**: [https://devops.com/cloud-disaster-recovery-best-practices/](https://devops.com/cloud-disaster-recovery-best-practices/)
  - **DRP တည်ဆောက်ခြင်းအတွက် အကောင်းဆုံးကျင့်ဝတ်များအပေါ် Google Cloud ဘလော့ပို့စ်**: [https://medium.com/google-cloud/disaster-recovery-on-google-cloud-for-data-part-1-9cf08782bac9](https://medium.com/google-cloud/disaster-recovery-on-google-cloud-for-data-part-1-9cf08782bac9)
  - **Google Cloud Disaster Recovery**: [https://cloud.google.com/backup-disaster-recovery/docs](https://cloud.google.com/backup-disaster-recovery/docs)
  - **Google Cloud Disaster Recovery Planning Guide**: [https://cloud.google.com/architecture/dr-scenarios-planning-guide](https://cloud.google.com/architecture/dr-scenarios-planning-guide)
  - **Google Cloud Disaster Recovery Services**: [https://www.techtarget.com/searchdisasterrecovery/definition/cloud-disaster-recovery-cloud-DR](https://www.techtarget.com/searchdisasterrecovery/definition/cloud-disaster-recovery-cloud-DR)
