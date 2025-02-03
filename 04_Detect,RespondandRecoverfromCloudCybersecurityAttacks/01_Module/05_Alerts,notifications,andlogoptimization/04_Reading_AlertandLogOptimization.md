# Guide to event threat detection

[Guide to event threat detection 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/supplement/nXdac/guide-to-event-threat-detection)

## PDF File

[Guide to event threat detection.pdf 🔗](https://1drv.ms/b/c/526c45566c8c239a/EZ4tv1xDyZpLtZhj7f2q1YEBNuGS-bLR0nfd5PYrzqEhXw?e=INpWcV)

# Guide to event threat detection

You’ve learned about how cloud security analysts monitor activity in their environments using
tools and alerts. In this reading, you'll dive deeper into Security Command Center (SCC)
features by exploring one of its log-based monitoring services, Event Threat Detection. You'll
also learn how to trigger an Identity and Access Management (IAM) alert finding, and use Logs
Explorer to query the logs associated with the triggered alert.

# Event Threat Detection

အကျဉ်းချုပ်အနေဖြင့် ပြန်လည်သတိပေးရန်၊ **SCC (Security Command Center)** သည် Google Cloud ၏ စုစည်းထားသော vulnerability နှင့် threat reporting ဝန်ဆောင်မှုဖြစ်သည်။ SCC သည် Google Cloud အရင်းအမြစ်များကို scan လုပ်ပြီး security issues များကို ဖော်ထုတ်ရန် ဝန်ဆောင်မှုများကို အသုံးပြုသည်။ ဥပမာ၊ vulnerabilities များနှင့် misconfigurations များကို စစ်ထုတ်နိုင်သည်။ SCC ၏ built-in services များထဲတွင် **Event Threat Detection** ဝန်ဆောင်မှုကို ပါဝင်ပါသည်။

**Event Threat Detection** ဝန်ဆောင်မှုသည် log-based threat analysis ကို ပေးဆောင်ပြီး Google Cloud logs များကို အဆက်မပြတ် စောင့်ကြည့်၍ potential threats များကို scan လုပ်ပါသည်။ Event Threat Detection သည် threat တစ်ခုကို တွေ့ရှိပါက၊ အောင်မြင်သော findings များကို SCC တွင် ပြသပေးပါသည်။

---

**မှတ်ချက်**: Security Command Center တွင် service tiers နှစ်မျိုးရှိသည် - **Standard** နှင့် **Premium**။ tier type သည် အသုံးပြုနိုင်သော built-in services များနှင့် သူတို့၏ features များကို ဆုံးဖြတ်ပေးသည်။ ဤ program တွင်၊ labs များသည် သင့်အား **Premium tier** သို့ ဝင်ရောက်ခွင့်ပေးပါသည်။

ဒီ query က active ဖြစ်နေပြီး muted မဖြစ်သော findings များအားလုံးကို ပြသပေးပါသည်။ ထို့အပြင်၊ time range field ကို အသုံးပြု၍ query ၏ အချိန်ကာလကို ပြင်ဆင်နိုင်ပါသည်။

2. **Quick Filters**:  
   Predefined attribute filters များထဲမှ တစ်ခု သို့မဟုတ် ထို့ထက်ပိုသော filters များကို ရွေးပြီး query တစ်ခုသို့ ထည့်သွင်းနိုင်ပါသည်။

3. **Finding Query Results**:  
   ရလဒ်များကို ပြသပေးသည်။ ဖော်ထုတ်ချက် (finding) တစ်ခုကို နှိပ်လိုက်လျှင် သူ့ရဲ့ အသေးစိတ်အချက်အလက်များကို ရယူနိုင်ပါသည်။ Findings များတွင် အောက်ပါ properties များ ပါဝင်နိုင်သည် -

- **Category**: Finding type အမည်ကို ပေးသည်။ ဥပမာ - `Persistence: IAM anomalous grant` သည် Identity and Access Management (IAM) အမျိုးအစားနှင့် ပတ်သက်သော category တစ်ခုဖြစ်သည်။

- **Severity**: Finding ရဲ့ severity level ကို ပြသသည် - critical, high, medium, low, သို့မဟုတ် unspecified။

- **Attack Exposure Score**: Finding ရဲ့ attack exposure score ကို မှတ်ပေးသည်။ ဒီ score က security issue တစ်ခုက ဘယ်လောက် critical resources များကို potential threats များအတွက် expose လုပ်နေသည်ကို ပြောပြပေးသည်။

- **Event Time**: Finding ကို ပထမဆုံး detect လုပ်တဲ့အချိန် သို့မဟုတ် နောက်ဆုံး update လုပ်ခဲ့သော timestamp ကို ပြသသည်။

- **Create Time**: SCC တွင် finding ကို ဖန်တီးခဲ့သော timestamp ကို ပြသသည်။

- **Resource Display Name**: Issue တစ်ခုကို detect လုပ်ခဲ့သည့် resource ရဲ့ display name ကို ပေးသည်။

- **Resource Full Name**: Issue တစ်ခုကို detect လုပ်ခဲ့သည့် resource ရဲ့ full name ကို ပေးသည်။

- **Resource Path**: Issue တစ်ခုကို detect လုပ်ခဲ့သည့် resource ရဲ့ path ကို identify လုပ်သည်။

- **Resource Type**: Issue တစ်ခုကို detect လုပ်ခဲ့သည့် resource ရဲ့ type ကို ပြသသည်။

- **Security Marks**: Finding သို့ ထည့်သွင်းထားသော security marks များကို assign လုပ်သည်။

- **Finding Class**: Finding နှင့် ပတ်သက်သော class ကို ပြသသည် - threat, vulnerability, misconfiguration, observation, SCC error, သို့မဟုတ် finding class unspecified။

# Trigger an IAM Detector

**Event Threat Detection** သည် threats များကို ဖော်ထုတ်ပြီး findings များကို detection rules (ဒီအရာကို detectors ဟုလည်း ခေါ်သည်) များကို အသုံးပြု၍ ဖန်တီးပေးသည်။ ဒီ rules များသည် Event Threat Detection က ဘယ်လို logs များကို အသုံးပြု၍ threats များကို ဖော်ထုတ်ရမည်နှင့် အတိအကျ ဘယ်လို threat type များကို စောင့်ကြည့်ရမည်ကို သတ်မှတ်ပေးသည်။ ရှေ့တန်း lab များတွင်၊ သင့်အား **Persistence: IAM anomalous grant detector** ကို trigger လုပ်ရန်အတွက် activity များကို ရိုက်ပြီး SCC တွင် finding တစ်ခုကို မှတ်တမ်းတင်ရန် လုပ်ဆောင်ပါမည်။

ဒီ **finding** က anomalous IAM grant တစ်ခုကို detect လုပ်ခဲ့ပြီးဖြစ်ပြီး၊ အဲဒါက malicious actor တစ်ယောက်သည် cloud environment တစ်ခုသို့ unauthorized access ရယူရန် ကြိုးစားနေသည့် potential indication တစ်ခုဖြစ်နိုင်သည်။ anomalous grant တစ်ခု၏ ဥပမာမှာ gmail.com email account ရှိ external user တစ်ယောက်ကို Google Cloud project တစ်ခုသို့ project owner အဖြစ် invite လုပ်ခြင်းဖြစ်သည်။

ဒီ lab တွင် ဒီ finding ကို trigger လုပ်ရန်အတွက်၊ သင် external user `bad.actor.demo@gmail.com` ကို project owner role တစ်ခု assign လုပ်ပေးပါမည်။ ဒီ external user က qwiklabs.net organization အပြင်ဘက်မှ ရှိနေသော user တစ်ယောက်ဖြစ်သည်။

---

**မှတ်ချက်**: ဒီ lab တွင် qwiklabs.net organization အတွက် student user accounts နှစ်ခု ဖွဲ့စည်းထားပါသည် - username 1 နှင့် username 2။ ဒီ user accounts နှစ်ခု၏ အချက်အလက်များကို Lab Details panel တွင် တွေ့နိုင်ပါသည်။ ဒီ users နှစ်ယောက်လုံးမှာ lab project အတွက် owner roles ရှိပြီး၊ ဒါက alert finding တစ်ခုကို trigger လုပ်ပေးမည်ဖြစ်သည်။ Username 2 က lab provisioning process တစ်ခု၏ အစိတ်အပိုင်းအနေဖြင့် background မှ benign Persistence: IAM anomalous grant finding တစ်ခုကို အလိုအလျောက် trigger လုပ်ပေးမည်ဖြစ်သည်။ သင် username 1 ဖြင့် operate လုပ်ဆောင်ပြီး၊ ဒါက `bad.actor.demo@gmail.com` ကို access ပေးခြင်းဖြင့် genuine Persistence: IAM anomalous grant finding တစ်ခုကို trigger လုပ်ပေးမည်ဖြစ်သည်။

---

# SCC တွင် Findings များကို Analyze လုပ်ခြင်း

IAM detector ကို trigger လုပ်ပြီးနောက်၊ SCC ၏ **Findings** စာမျက်နှာတွင် details များကို ဝင်ရောက်ကြည့်နိုင်ပါသည်။ Finding တစ်ခုကို နှိပ်လိုက်လျှင် detailed view ကို ဝင်ရောက်ကြည့်နိုင်ပြီး၊ ဒီ view တွင် အောက်ပါ tabs များကို select လုပ်၍ finding အကြောင်း ပိုမိုသိရှိနိုင်ပြီး action များ ပြုလုပ်နိုင်ပါသည် -

- **Summary tab**: ဒါက default view ဖြစ်ပြီး၊ finding အကြောင်း key information နှင့် attributes များကို highlight လုပ်ပေးသည်။

- **Source properties tab**: ဒီ tab မှာ finding ရဲ့ sourceProperties object attributes JSON ကို display လုပ်ပေးသည်။ ဒီ lab တွင်၊ ဒီ tab ကို အသုံးပြု၍ properties field details များကို examine လုပ်နိုင်ပါသည်၊ ဒီ field မှာ user ရဲ့ action၊ assigned role၊ နှင့် user ရဲ့ email address အကြောင်း အချက်အလက်များ ပါဝင်ပါသည်။

- **JSON tab**: ဒီ tab မှာ finding ရဲ့ full JSON format ကို တွေ့နိုင်ပါသည်။

# Query Logs Using Logs Explorer

Logs Explorer ကို အသုံးပြု၍ logs များကို filter လုပ်နိုင်သည်ကို သတိရပါ။ ဒီ lab တွင်၊ သင် အောက်ပါ query ကို run လုပ်ပါမည် -

```plaintext
protoPayload.authorizationInfo.permission="resourcemanager.projects.setIamPolicy"
protoPayload.methodName="InsertProjectOwnershipInvite"
```

- `protoPayload.authorizationInfo.permission="resourcemanager.projects.setIamPolicy"`
  ဒီ line က project တစ်ခုအတွက် IAM policy သတ်မှတ်ရန် attempts များနှင့် ပတ်သက်သော logs များကို filter လုပ်ပေးသည်။ ဒီ permission က specific project တစ်ခုအတွက် users, groups, နှင့် service accounts များအတွက် roles နှင့် permissions များကို modify လုပ်နိုင်စွမ်းကို grant လုပ်ပေးသည်။
- `protoPayload.methodName="InsertProjectOwnershipInvite"`
  ဒီ line က InsertProjectOwnershipInvite နှင့် ပတ်သက်သော logs များကို filter လုပ်ပေးသည်၊ ဒါက project တစ်ခု၏ owners ဖြစ်လာရန် users သို့မဟုတ် groups များကို invite လုပ်ရန် attempts များကို ပြသသည်။

ဒီ query နှစ်ခုကို ပေါင်းစပ်၍၊ project ownership ပေးရန် attempts များနှင့် ပတ်သက်သော logs များကို ရှာဖွေနိုင်ပါသည်။ ဒါက user တစ်ယောက်က project တစ်ခုအတွက် new owners များကို invite လုပ်ရန် ကြိုးစားခဲ့သည့် events များကို investigate လုပ်ရာတွင် အသုံးဝင်ပါသည်။

# Key Takeaways

Security events များနှင့် potential security incidents များကို log details များကို အသုံးပြု၍ investigate လုပ်နိုင်သည့် နည်းလမ်းများကို သိရှိနေခြင်းသည် findings များကို context ထည့်ရန် ကူညီပေးပြီး၊ potential attack တစ်ခုအတွင်း ဘာတွေ ဖြစ်ပွားခဲ့သည်ကို နားလည်ရန် ကူညီပေးပါသည်။

### Resources for More Information

Event Threat Detection service အကြောင်း ပိုမိုသိရှိရန်၊ [Overview of Event Threat Detection 🔗](https://cloud.google.com/security-command-center/docs/concepts-event-threat-detection-overview) ကို ဖတ်ရှုပါ။

SCC တွင် queries များကို ဖန်တီးပြီး edit လုပ်နိုင်ရန် ပိုမိုသိရှိရန်၊ [Query findings in the Google Cloud console 🔗](https://cloud.google.com/security-command-center/docs/how-to-build-findings-query-console) ကို ဖတ်ရှုပါ။
