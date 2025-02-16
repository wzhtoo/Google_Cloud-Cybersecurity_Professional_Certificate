# Alert and log optimization

[Alert and log optimization 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/supplement/B9mf5/alert-and-log-optimization)

## PDF File

[Alert and log optimization.pdf 🔗](https://1drv.ms/b/c/526c45566c8c239a/ESIaDM_aQyVFhvbcq2OovBwBZByHj3LGuZ_eTuRJ3sTywA?e=e24Uat)

# Alert and log optimization

So far, you've learned how alerts provide security teams with real-time information about
potential threats in their environment. Remember, not every alert signals an actual threat. An
alert may be a false positive, which is an alert that incorrectly detects the presence of a threat.
In this reading, you'll explore how to set up alerts and notifications and how to use them in
Google Cloud. You'll also learn about the advantages of metrics and some of the challenges
that can happen with alerts.

# Cloud Monitoring နှင့် သတိပေးချက်မူဝါဒများ

Cloud Monitoring သည် Google Cloud ပရောဂျက်တွင် ရှိနေသော cloud အရင်းအမြစ်များမှ ဒေတာများကို စုဆောင်းပြီး၊ ထို cloud အရင်းအမြစ်များ၏ ကျန်းမာရေး၊ အလုပ်လုပ်ဆောင်မှုနှင့် အသုံးပြုနိုင်မှုကို စောင့်ကြည့်ပါသည်။ ထို့နောက် CPU (Central Processing Unit) အသုံးပြုမှု၊ မှတ်ဉာဏ်အသုံးပြုမှု၊ ကွန်ရက်လုပ်ငန်းများ စသည့် မှတ်တမ်းများကို အသုံးပြု၍ cloud ပတ်ဝန်းကျင်အကြောင်း အသိဉာဏ်များ ဖန်တီးပေးသည်။

Cloud Monitoring တွင် သင်သည် ဤမှတ်တမ်းများသည် သတ်မှတ်ထားသော အဆင့်ကို ကျော်လွှားသည့်အခါ သတိပေးချက်များ ဖြစ်ပေါ်စေရန် **သတိပေးချက်မူဝါဒများ** ဖွဲ့စည်းနိုင်ပါသည်။ သတိပေးချက်မူဝါဒတစ်ခုသည် သင်သတိပေးချင်သော အခြေအနေများကို သတ်မှတ်ပြီး ထိုအခြေအနေများ ဖြစ်ပေါ်သည့်အခါ သင့်အား မည်သို့ အသိပေးမည်ကို သတ်မှတ်ပေးသည်။ Cloud Monitoring တွင် သင် မှတ်တမ်းများအပေါ် မူတည်၍ အမျိုးအစားနှစ်မျိုးသော သတိပေးချက်မူဝါဒများ ဖွဲ့စည်းနိုင်ပါသည်။ အဆိုပါ အမျိုးအစားနှစ်မျိုးမှာ **မှတ်တမ်းအခြေခံ** နှင့် **မှတ်တမ်းစာအုပ်အခြေခံ** ဖြစ်သည်။

# မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒ

**မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒ** များသည် cloud အရင်းအမြစ်များ၏ ကျန်းမာရေးနှင့် လုပ်ဆောင်မှုများကို စောင့်ကြည့်ရာတွင် အသုံးဝင်ဆုံးဖြစ်သည်။ ဥပမာ၊ သင်သည် ပံ့ပိုးထားသော virtual machine (VM) တစ်ခု၏ CPU အသုံးပြုမှုသည် 80% ကျော်လွှားသည့်အခါ သတိပေးချက် ဖြစ်ပေါ်စေရန် သတ်မှတ်နိုင်သည်။ အောက်ပါအတိုင်း **မှတ်တမ်းအခြေခံ သတိပေးချက်စနစ်** တစ်ခုကို ဖန်တီးရန်၊ ဖွဲ့စည်းရန် နှင့် စမ်းသပ်ရန် လိုအပ်သော အဆင့်များကို လေ့လာကြည့်ပါ။

### မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒ ဖန်တီးရန် လိုအပ်သော အဆင့်များ

1. **Cloud Monitoring ဝဘ် UI ကို ဝင်ရောက်ပါ**  
   ပထမဆုံး Google Cloud Console တွင် ဝင်ရောက်ပြီး **Monitoring** ဝဘ် UI ကို ဖွင့်ပါ။

2. **Alerting စာမျက်နှာသို့ သွားပါ**  
   ဘယ်ဘက်ဘားတွင် `Alerting` ကဏ္ဍကို ရွေးပြီး `Create Policy` ကို နှိပ်ပါ။

3. **Target ကို ရွေးပါ**  
   သင် မှတ်တမ်းကို စောင့်ကြည့်လိုသော cloud အရင်းအမြစ် (ဥပမာ - VM, Database, Load Balancer စသည်) ကို ရွေးပါ။

4. **Condition ကို သတ်မှတ်ပါ**  
   သတိပေးချက် ဖြစ်ပေါ်မည့် အခြေအနေကို သတ်မှတ်ပါ။ ဥပမာ၊ CPU အသုံးပြုမှုသည် 80% ကျော်လွှားသည့်အခါ သတိပေးချက် ဖြစ်ပေါ်စေရန် သတ်မှတ်နိုင်သည်။

5. **သတိပေးချက် ပုံစံကို ရွေးပါ**  
   သတိပေးချက် ဖြစ်ပေါ်သည့်အခါ သင့်အား မည်သို့ အသိပေးမည်ကို သတ်မှတ်ပါ။ ဥပမာ - Email, SMS, သို့မဟုတ် PagerDuty စသည့် အသိပေးနည်းလမ်းများကို ရွေးပါ။

6. **သတိပေးချက်မူဝါဒကို သိမ်းဆည်းပါ**  
   အဆင့်အားလုံး ပြည့်စုံပြီးပါက `Save` ကို နှိပ်၍ သတိပေးချက်မူဝါဒကို သိမ်းဆည်းပါ။

7. **စမ်းသပ်ပါ**  
   သတိပေးချက်မူဝါဒ အလုပ်လုပ်နေကြောင်း အတည်ပြုရန် စမ်းသပ်ပါ။ သတ်မှတ်ထားသော အခြေအနေများကို ကျော်လွှားသည့်အခါ သတိပေးချက် ဖြစ်ပေါ်မည်ကို အတည်ပြုပါ။

---

### အကျိုးကျေးဇူးများ

- **လုံခြုံရေး ပိုမိုမြင့်တက်စေသည်**: မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒများသည် ဘေးအန္တရာယ်များကို အမြန်တွေ့ရှိပြီး တုံ့ပြန်နိုင်စေသည်။
- **စနစ် ထိရောက်မှု မြင့်စေသည်**: လုပ်ဆောင်မှု ပြဿနာများကို အမြန် ဖြေရှင်းနိုင်စေသည်။
- **အချက်အလက်များ ပိုမိုရှင်းလင်းစေသည်**: စနစ်အားလုံး၏ အလုပ်လုပ်ဆောင်မှုကို စောင့်ကြည့်နိုင်စေသည်။

# မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒ ဖန်တီးခြင်း

1. **Google Cloud console သို့ ဝင်ရောက်ပါ**: [https://console.cloud.google.com](https://console.cloud.google.com)
2. ဘယ်ဘက်ထောင့်တွင် ရှိနေသော Navigation menu (လိုင်းသုံးကြောင်း) ကို နှိပ်ပါ။
3. **Monitoring** ကို နှိပ်ပါ။
4. **Alerting** ကို နှိပ်ပါ။
5. **Create policy** ခလုတ်ကို နှိပ်ပါ။

---

## မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒ ဖွဲ့စည်းခြင်း

1. **Resource type** နေရာတွင် **VM instance** ကို ရွေးပါ။
2. **Metric** နေရာတွင် **CPU utilization** ကို ရွေးပါ။
3. **Condition type** နေရာတွင် **Threshold** ကို ရွေးပါ။
4. **Threshold** နေရာတွင် **80%** ထည့်ပါ။
5. **Aggregation** နေရာတွင် **Average** ကို ရွေးပါ။
6. **Per** နေရာတွင် **1 minute** ကို ရွေးပါ။
7. **For** နေရာတွင် **5 minutes** ကို ရွေးပါ။

---

## Console Notification System ကို အသုံးပြု၍ မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒကို စမ်းသပ်ခြင်း

1. **Test notification** အပိုင်းတွင် မကြာသေးမီက ဖွဲ့စည်းထားသော notification channel ကို ရွေးပါ။
2. **Send test notification** ခလုတ်ကို နှိပ်ပါ။
3. အကယ်၍ သင့်အား email test notification ကို ရရှိပါက၊ notification system သည် မှန်ကန်စွာ ဖွဲ့စည်းထားသည်ဟု ဆိုလိုသည်။

---

## မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒကို လက်တွေ့ စမ်းသပ်ခြင်း

1. VM instance `vm1` ၏ CPU utilization ကို လက်တွေ့ 80% ထက် ပိုမိုတိုးမြှင့်ပါ။
2. သတိပေးချက်မူဝါဒ ဖြစ်ပေါ်ပြီး သတိပေးချက် ထုတ်လုပ်ရန် စောင့်ပါ။
3. သင့်အား email notification ကို ရရှိပြီးသည်ကို အတည်ပြုပါ။

---

## မှတ်တမ်းအခြေခံ သတိပေးချက်မူဝါဒများအကြောင်း ပိုမိုသိရှိရန်

- Google Cloud Monitoring တွင် သတိပေးချက်မူဝါဒ ဖန်တီးပုံ: [https://cloud.google.com/monitoring/alerts](https://cloud.google.com/monitoring/alerts)
- Cloud Monitoring အတွက် မှတ်တမ်း: [https://cloud.google.com/monitoring/docs](https://cloud.google.com/monitoring/docs)

---

# မှတ်တမ်းစာအုပ်အခြေခံ သတိပေးချက်မူဝါဒ

**မှတ်တမ်းစာအုပ်အခြေခံ သတိပေးချက်မူဝါဒ** များသည် လုံခြုံရေးနှင့် ပတ်သက်သော ဖြစ်ရပ်များကို စောင့်ကြည့်ရာတွင် အသုံးဝင်ဆုံးဖြစ်သည်။ ဤသတိပေးချက်မူဝါဒများသည် log data ကို စောင့်ကြည့်ပြီး သတ်မှတ်ထားသော ဖြစ်ရပ်တစ်ခု မှတ်တမ်းစာအုပ်တွင် ပေါ်လာသည့်အခါ သင့်အား အသိပေးနိုင်သည်။ ဥပမာ၊ အသုံးပြုသူအကောင့်တစ်ခုသည် service account တစ်ခု၏ လုံခြုံရေး key ကို ဝင်ရောက်သုံးစွဲသည့်အခါ သတိပေးချက် ဖြစ်ပေါ်စေရန် ဖန်တီးနိုင်သည်။ အောက်ပါအတိုင်း **မှတ်တမ်းစာအုပ်အခြေခံ သတိပေးချက်စနစ်** တစ်ခုကို ဖန်တီးရန်၊ ဖွဲ့စည်းရန် နှင့် စမ်းသပ်ရန် လိုအပ်သော အဆင့်များကို လေ့လာကြည့်ပါ။

# မှတ်တမ်းစာအုပ်အခြေခံ မှတ်တမ်းဖန်တီးခြင်း

1. **Google Cloud console တွင် Logging > Logs Explorer ကို ရွေးပါ။**
2. မှတ်တမ်းစာအုပ်အခြေခံ မှတ်တမ်းဖန်တီးရန် **More > Create log-based metric** ကို နှိပ်ပါ။
3. အောက်ပါအချက်အလက်များကို ထည့်ပါ။
   - **Name**: Security Key Access
   - **Description**: Tracks the number of times a user account accesses the security key of a service account
   - **Filter**: `resource.type="service_account" AND protoPayload.service_account.email=([YOUR_SERVICE_ACCOUNT_EMAIL]) AND protoPayload.event_type="security_key_access"`
   - **Value extractor**: `count(*)`
4. **Create** ကို နှိပ်ပါ။

---

## မှတ်တမ်းစာအုပ်အခြေခံ သတိပေးချက် ဖန်တီးခြင်း

1. **More > Create alert from metric** ကို နှိပ်ပါ။
2. **Alert details pane** တွင် အောက်ပါအချက်အလက်များကို ထည့်ပါ။
   - **Name**: Security Key Access Alert
   - **Description**: Alert when a user account accesses the security key of a service account
3. **Next** ကို နှိပ်ပါ။

# Logs Explorer တွင် Security Key Access မှတ်တမ်းကို နှိပ်ပါ။

Logs Explorer တွင် **Security Key Access** မှတ်တမ်းကို နှိပ်ပါ။ လက်ရှိအချိန်အတွက် data point တစ်ခုကို တွေ့ရပါမည်။

---

## Notification များကို ဖွဲ့စည်းပြီးပါက

Notification များကို ဖွဲ့စည်းပြီးပါက၊ သင့်အား သတိပေးချက် ဖြစ်ပေါ်ခဲ့သည့်အကြောင်း email notification ကို ရရှိပါမည်။

---

## မှတ်တမ်းစာအုပ်အခြေခံ သတိပေးချက်မူဝါဒများအကြောင်း ပိုမိုသိရှိရန်

- မှတ်တမ်းစာအုပ်အခြေခံ သတိပေးချက်များ ဖန်တီးခြင်းနှင့် စီမံခန့်ခွဲခြင်း: [https://cloud.google.com/logging/docs/alerting/log-based-alerts](https://cloud.google.com/logging/docs/alerting/log-based-alerts)

---

# Incident Response Process ကို မှတ်တမ်းများဖြင့် တိုးတက်စေခြင်း

အဖွဲ့အစည်းတစ်ခု၏ incident response process ၏ ထိရောက်မှုကို တိုင်းတာရန် နည်းလမ်းတစ်ခုမှာ **မှတ်တမ်းများ** ကို အသုံးပြုခြင်းဖြစ်သည်။ မှတ်တမ်းများကို စောင့်ကြည့်ခြင်းဖြင့် အဖွဲ့အစည်းများသည် ကောင်းမွန်စွာ လုပ်ဆောင်နေသော နယ်ပယ်များနှင့် တိုးတက်ရန် လိုအပ်သော နယ်ပယ်များကို ဖော်ထုတ်နိုင်သည်။ မှတ်တမ်းများသည် လုံခြုံရေးအဖွဲ့များအား ဒေတာများကို အခြေခံ၍ ကောင်းစွာ ဆုံးဖြတ်ချက်များ ချရန် ကူညီပေးပြီး incident response process ကို တိုးတက်စေရန် အသုံးပြုနိုင်သည်။

မှတ်တမ်းအမျိုးအစားများကို မည်သို့ တိုင်းတာရန် လိုအပ်သည် ပေါ်မူတည်၍ မတူညီသော အမျိုးအစားများ ရှိသည်။ ဥပမာ၊ နေ့စဉ်ဖြစ်ရပ်အရေအတွက် မှတ်တမ်းသည် **အချိန်အခြေခံ မှတ်တမ်း** တစ်ခုဖြစ်သည်။ အချိန်အခြေခံ မှတ်တမ်းများသည် အချိန်ကာလတစ်ခုအတွင်း ဖြစ်ပေါ်နေသော ပြောင်းလဲမှုများကို စောင့်ကြည့်ရန် အသုံးဝင်သည်။ ထို့အပြင် လုံခြုံရေး ပရောဂျက်ကို အခြားအဖွဲ့အစည်းများနှင့် နှိုင်းယှဉ်ရန် အသုံးပြုနိုင်သည်။

---

## Cloud Monitoring Operations Metrics များ

### Cloud Security Monitoring Metrics

- **Failed login attempts**: Cloud console သို့မဟုတ် အခြား cloud အရင်းအမြစ်များသို့ ဝင်ရောက်ရန် မအောင်မြင်သော အကြိမ်အရေအတွက်
- **Login attempts**: Cloud console သို့မဟုတ် အခြား cloud အရင်းအမြစ်များသို့ ဝင်ရောက်ရန် ကြိုးစားမှုများ၏ အကြိမ်အရေအတွက်
- **Security alerts**: ဖြစ်ပေါ်ခဲ့သော လုံခြုံရေး သတိပေးချက်များ၏ အကြိမ်အရေအတွက်
- **Unusual activity**: Cloud usage တွင် ပုံမှန် ပုံစံမှ ကွဲလွဲသော လုပ်ဆောင်မှုများ

### General Cloud Operations Monitoring Metrics

- **Application errors**: Application များတွင် ဖြစ်ပေါ်သော အမှားအယွင်းများ၏ အကြိမ်အရေအတွက်
- **Application latency**: Application တစ်ခုသည် request တစ်ခုကို အမှိုက်ပြန်ပေးရန် ကြာချိန်
- **API call errors**: API calls များ မအောင်မြင်ဘဲ ပျက်ကွက်သော အကြိမ်အရေအတွက်
- **API call latency**: API call တစ်ခုကို လုပ်ဆောင်ရန် ကြာချိန်
- **API call volume**: Cloud အရင်းအမြစ်များသို့ ပြုလုပ်ထားသော API calls များ၏ အကြိမ်အရေအတွက်
- **CPU utilization**: အသုံးပြုနေသော CPU အချိန်၏ ရာခိုင်နှုန်း
- **Disk utilization**: အသုံးပြုနေသော disk space ရာခိုင်နှုန်း
- **Memory utilization**: အသုံးပြုနေသော memory ရာခိုင်နှုန်း
- **Network traffic**: Network တစ်ခုမှ ပို့ဆောင်နေသော ဒေတာပမာဏ
- **System logs**: ဖန်တီးထားသော system logs များ၏ အကြိမ်အရေအတွက်

### Additional Cloud Monitoring Metrics

- **Cache metrics**: Cache servers များအတွက် မှတ်တမ်းများ၊ hit rate နှင့် miss rate စသည်
- **Container metrics**: Kubernetes containers များအတွက် မှတ်တမ်းများ၊ CPU usage, memory usage, network traffic စသည်
- **Database metrics**: Database servers များအတွက် မှတ်တမ်းများ၊ query latency နှင့် connection count စသည်
- **Load balancer metrics**: Load balancers များအတွက် မှတ်တမ်းများ၊ request throughput နှင့် response time စသည်
- **Messaging metrics**: Messaging queues များအတွက် မှတ်တမ်းများ၊ message throughput နှင့် latency စသည်

---

## Cloud Monitoring Metrics များအကြောင်း ပိုမိုသိရှိရန်

- Google Cloud Security Command Center (SCC): [https://cloud.google.com/security-command-center](https://cloud.google.com/security-command-center)

---

**မှတ်ချက်**: မှတ်တမ်းများသည် KPIs (Key Performance Indicators) များနှင့် ကွဲပြားသည်။ မှတ်တမ်းများသည် workflow သို့မဟုတ် business process တစ်ခု၏ အခြေအနေကို စောင့်ကြည့်သည်။ သို့သော် KPIs များသည် workflow တစ်ခု၏ အဓိက ရည်မှန်းချက်များ၊ ရည်ရွယ်ချက်များ သို့မဟုတ် ပန်းတိုင်များကို ထိရောက်စွာ အောင်မြင်မှုကို တိုင်းတာရန် သတ်မှတ်ထားသော တိကျသော တန်ဖိုးများဖြစ်သည်။

---

## Pro-tip: Personalized Dashboards

လုံခြုံရေးဖြေရှင်းချက်များစွာသည် သင့်အား ဒေတာများကို တစ်နေရာတည်းတွင် ပြသရန် personalized dashboards များ ဖန်တီးနိုင်စေရန် ပေးဆောင်သည်။ ဥပမာ၊ **Chronicle SIEM** သည် လုံခြုံရေးဖြစ်ရပ်များနှင့် ပတ်သက်သော အချက်အလက်များကို အချိန်ပေါ်မူတည်၍ အကျဉ်းချုပ်ပေးသည်။
