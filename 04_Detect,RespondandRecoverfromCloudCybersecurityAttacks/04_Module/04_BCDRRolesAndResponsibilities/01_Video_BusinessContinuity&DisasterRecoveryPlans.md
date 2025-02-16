# Business continuity and disaster recovery plans

[Business continuity and disaster recovery plans 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/8jwAo/business-continuity-and-disaster-recovery-plans)

# Business Continuity and Disaster Recovery (BCDR)

## Introduction

- **English**: Ready to learn more about a vital part of Cloud security? In this video, we'll discuss the differences between business continuity and disaster recovery, also known as BCDR. We'll also discuss how to build BCDR plans and examine how they're used in Google Cloud.
- **Burmese**: Cloud လုံခြုံရေး၏ အရေးကြီးသော အစိတ်အပိုင်းတစ်ခုအကြောင်း ပိုမိုလေ့လာရန် အဆင်သင့်ဖြစ်ပြီလား။ ဤဗီဒီယိုတွင်၊ BCDR ဟုလည်းလူသိများသော လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှုနှင့် ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေးကြား ကွာခြားချက်များကို ဆွေးနွေးပါမည်။ BCDR အစီအစဉ်များကို မည်သို့တည်ဆောက်ပုံနှင့် Google Cloud တွင် ၎င်းတို့ကို မည်သို့အသုံးပြုပုံကိုလည်း ဆွေးနွေးပါမည်။

- **English**: Business continuity or BC is an organization's ability to maintain their everyday productivity by establishing a risk disaster recovery plan. Disaster recovery or DR is a strategic and systematic approach to recovering essential infrastructure and systems when a disaster happens.
- **Burmese**: လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှု သို့မဟုတ် BC ဆိုသည်မှာ အန္တရာယ် ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး အစီအစဉ်ကို တည်ထောင်ခြင်းဖြင့် အဖွဲ့အစည်းတစ်ခု၏ နေ့စဉ် ထုတ်လုပ်မှု စွမ်းရည်ကို ထိန်းသိမ်းနိုင်စွမ်းဖြစ်သည်။ ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး သို့မဟုတ် DR ဆိုသည်မှာ ဘေးအန္တရာယ်တစ်ခု ဖြစ်ပွားသောအခါ မရှိမဖြစ် လိုအပ်သော အခြေခံအဆောက်အအုံနှင့် စနစ်များကို ပြန်လည်ရယူရန်အတွက် နည်းဗျူဟာမြောက်ပြီး စနစ်တကျ ချဉ်းကပ်နည်းတစ်ခုဖြစ်သည်။

- **English**: Business continuity and disaster recovery work towards the same goal. Ensuring your organization is impacted as little as possible during a disaster or event. Security professionals often refer to these two concepts together as BCDR.
- **Burmese**: လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှုနှင့် ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေးသည် တူညီသော ရည်မှန်းချက်သို့ ဦးတည်လုပ်ဆောင်သည်။ ဘေးအန္တရာယ် သို့မဟုတ် အဖြစ်အပျက်တစ်ခုအတွင်း သင်၏ အဖွဲ့အစည်းကို တတ်နိုင်သမျှ သက်ရောက်မှုအနည်းဆုံးဖြစ်စေရန် သေချာစေခြင်း။ လုံခြုံရေး ကျွမ်းကျင်သူများသည် ဤအယူအဆနှစ်ခုကို BCDR အဖြစ် မကြာခဏ ရည်ညွှန်းကြသည်။

---

## BCDR Plans

- **English**: Let's explore disaster recovery and business continuity plans in more detail. When building either of these plans, there are three considerations to keep in mind. First, both plans start with a risk assessment. A risk assessment helps you and your team identify threats and evaluate their impact. This can also help you thoroughly document and set up a priority list.
- **Burmese**: ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေးနှင့် လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှု အစီအစဉ်များကို အသေးစိတ် လေ့လာကြည့်ကြပါစို့။ ဤအစီအစဉ်များ တစ်ခုခုကို တည်ဆောက်သည့်အခါ၊ သတိပြုရမည့် အချက်သုံးခုရှိသည်။ ပထမဦးစွာ၊ အစီအစဉ်နှစ်ခုလုံးသည် အန္တရာယ် အကဲဖြတ်မှုဖြင့် စတင်သည်။ အန္တရာယ် အကဲဖြတ်မှုသည် သင်နှင့် သင့်အဖွဲ့အား ခြိမ်းခြောက်မှုများကို ခွဲခြားသတ်မှတ်ရန်နှင့် ၎င်းတို့၏ သက်ရောက်မှုကို အကဲဖြတ်ရန် ကူညီပေးသည်။ ၎င်းသည် သင့်အား အသေးစိတ် မှတ်တမ်းတင်ရန်နှင့် ဦးစားပေးစာရင်းကို သတ်မှတ်ရန်လည်း ကူညီနိုင်သည်။

- **English**: Next, a business impact analysis is necessary for you and your team to identify which critical operations need to be prioritized when a disaster happens. Finally, organizations use strategic planning to outline various disaster scenarios so they can focus their efforts on minimizing disruption, recovering lost information, and restoring regular business operations as soon as possible.
- **Burmese**: ထို့နောက်၊ ဘေးအန္တရာယ်တစ်ခု ဖြစ်ပွားသောအခါ မည်သည့် အရေးကြီးသော လုပ်ငန်းလည်ပတ်မှုများကို ဦးစားပေးသင့်သည်ကို ခွဲခြားသတ်မှတ်ရန်အတွက် သင်နှင့် သင့်အဖွဲ့အတွက် လုပ်ငန်း သက်ရောက်မှု ခွဲခြမ်းစိတ်ဖြာမှု လိုအပ်ပါသည်။ နောက်ဆုံးတွင်၊ အဖွဲ့အစည်းများသည် အနှောင့်အယှက်ကို အနည်းဆုံးဖြစ်စေရန်၊ ဆုံးရှုံးသွားသော သတင်းအချက်အလက်များကို ပြန်လည်ရယူရန်နှင့် တတ်နိုင်သမျှအမြန်ဆုံး ပုံမှန် လုပ်ငန်းလည်ပတ်မှုများကို ပြန်လည်ထူထောင်ရန် ကြိုးပမ်းမှုများအပေါ် အာရုံစိုက်နိုင်စေရန်အတွက် မတူညီသော ဘေးအန္တရာယ် အခြေအနေများကို ဖော်ပြရန် နည်းဗျူဟာမြောက် စီမံကိန်းရေးဆွဲမှုကို အသုံးပြုကြသည်။

- **English**: All three of these considerations are necessary for teams to create business continuity and disaster recovery plans that help ensure successful outcomes. Both plans consider what systems need to be prioritized and how to address prioritized systems during a disaster. But each plan considers these factors differently.
- **Burmese**: ဤအချက်သုံးခုစလုံးသည် အဖွဲ့များအား အောင်မြင်သော ရလဒ်များကို သေချာစေရန် ကူညီပေးသည့် လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှုနှင့် ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး အစီအစဉ်များကို ဖန်တီးရန်အတွက် မရှိမဖြစ် လိုအပ်ပါသည်။ အစီအစဉ်နှစ်ခုလုံးသည် မည်သည့်စနစ်များကို ဦးစားပေးသင့်သည်နှင့် ဘေးအန္တရာယ်တစ်ခုအတွင်း ဦးစားပေးစနစ်များကို မည်သို့ကိုင်တွယ်ရမည်ကို ထည့်သွင်းစဉ်းစားသည်။ သို့သော် အစီအစဉ်တစ်ခုစီသည် ဤအချက်များကို မတူညီစွာ ထည့်သွင်းစဉ်းစားသည်။

- **English**: Every organization is unique. Each organization's goals and plans for disaster recovery and business continuity must be tailored to their needs.
- **Burmese**: အဖွဲ့အစည်းတစ်ခုစီသည် ထူးခြားသည်။ ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေးနှင့် လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှုအတွက် အဖွဲ့အစည်းတစ်ခုစီ၏ ရည်မှန်းချက်များနှင့် အစီအစဉ်များသည် ၎င်းတို့၏ လိုအပ်ချက်များနှင့်အညီ ဖြစ်ရမည်။

---

## Google Cloud Tools and Features

- **English**: Let's explore some of the tools and features in Google Cloud that a security team can use to implement both BC and DR plans. An important part of Google Cloud's BC and DR strategy is using the BCDR recovery tool. This tool is a powerful asset that provides additional assurance that your systems can get back up and running quickly after a disaster.
- **Burmese**: BC နှင့် DR အစီအစဉ်နှစ်ခုလုံးကို အကောင်အထည်ဖော်ရန် လုံခြုံရေးအဖွဲ့တစ်ဖွဲ့မှ အသုံးပြုနိုင်သည့် Google Cloud ရှိ ကိရိယာများနှင့် အင်္ဂါရပ်အချို့ကို လေ့လာကြည့်ကြပါစို့။ Google Cloud ၏ BC နှင့် DR နည်းဗျူဟာ၏ အရေးကြီးသော အစိတ်အပိုင်းတစ်ခုမှာ BCDR ပြန်လည်ထူထောင်ရေး ကိရိယာကို အသုံးပြုခြင်းဖြစ်သည်။ ဤကိရိယာသည် ဘေးအန္တရာယ်တစ်ခုပြီးနောက် သင်၏ စနစ်များသည် လျင်မြန်စွာ ပြန်လည်လည်ပတ်နိုင်ကြောင်း နောက်ထပ် အာမခံချက်ကို ပေးဆောင်သည့် အားကောင်းသော ပိုင်ဆိုင်မှုတစ်ခုဖြစ်သည်။

- **English**: Also, Google Cloud's automation features allow for automatic backups and failover systems. This key feature ensures that your data remains intact and your operations continue functioning even when disaster strikes.
- **Burmese**: ထို့အပြင်၊ Google Cloud ၏ အလိုအလျောက်လုပ်ဆောင်ခြင်း အင်္ဂါရပ်များသည် အလိုအလျောက် backups နှင့် failover စနစ်များကို ခွင့်ပြုသည်။ ဤအဓိက အင်္ဂါရပ်သည် ဘေးအန္တရာယ်တစ်ခု ဖြစ်ပွားပါကပင် သင်၏ ဒေတာ မပျက်မစီးကြောင်းနှင့် သင်၏ လုပ်ငန်းလည်ပတ်မှုများ ဆက်လက်လုပ်ဆောင်နိုင်ကြောင်း သေချာစေသည်။

- **English**: Business continuity and disaster recovery plans are important for any security team, and they should be tested continuously. Now that you know more about BC and DR plans, you can build effective plans to manage disasters and support your organization.
- **Burmese**: လုပ်ငန်း ဆက်လက်လည်ပတ်နိုင်မှုနှင့် ဘေးအန္တရာယ် ပြန်လည်ထူထောင်ရေး အစီအစဉ်များသည် မည်သည့် လုံခြုံရေးအဖွဲ့အတွက်မဆို အရေးကြီးပြီး ၎င်းတို့ကို အဆက်မပြတ် စမ်းသပ်သင့်သည်။ ယခု BC နှင့် DR အစီအစဉ်များအကြောင်း ပိုမိုသိရှိရပြီဖြစ်သောကြောင့် ဘေးအန္တရာယ်များကို စီမံနိုင်သည်။
