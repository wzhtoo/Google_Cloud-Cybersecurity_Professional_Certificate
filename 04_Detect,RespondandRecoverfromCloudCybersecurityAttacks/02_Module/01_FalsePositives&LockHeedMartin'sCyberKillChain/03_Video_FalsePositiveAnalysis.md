# False positive analysis

[False positive analysis 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/Mc31R/false-positive-analysis)

# False Positives and False Positive Analysis

## Introduction

- **English**: In this video, you'll learn about false positives and false positive analysis. You'll examine their impact, some common causes, and some best practices for managing them.
- **Burmese**: ဒီဗီဒီယိုမှာ false positives နဲ့ false positive analysis အကြောင်းကို လေ့လာသွားမှာဖြစ်ပါတယ်။ သူတို့ရဲ့ သက်ရောက်မှု၊ အဖြစ်များတဲ့ အကြောင်းရင်းတွေ၊ နဲ့ သူတို့ကို စီမံခန့်ခွဲဖို့ အကောင်းဆုံးနည်းလမ်းတွေကို လေ့လာသွားမှာဖြစ်ပါတယ်။

## What is a False Positive?

- **English**: A false positive is an alert that incorrectly detects the presence of a threat. There are many systems and tools designed to notify you of potential dangers. These types of alerting devices appear in our everyday lives and may include fire alarms or heart rate monitors.
- **Burmese**: False positive ဆိုတာက ခြိမ်းခြောက်မှုတစ်ခုရဲ့ အမှန်တကယ်မရှိဘဲ ရှိနေတယ်လို့ မှားယွင်းစွာ ထောက်လှမ်းမိတဲ့ သတိပေးချက်တစ်ခုဖြစ်ပါတယ်။ အန္တရာယ်တွေကို သတိပေးဖို့ ဒီဇိုင်းထုတ်ထားတဲ့ စနစ်တွေနဲ့ ကိရိယာတွေ အများကြီးရှိပါတယ်။ ဒီလို သတိပေးတဲ့ ကိရိယာတွေက ကျွန်တော်တို့ရဲ့ နေ့စဉ်ဘဝမှာ ပါဝင်နေပြီး မီးသတိပေးချက် ဒါမှမဟုတ် နှလုံးခုန်နှုန်း စောင့်ကြည့်တဲ့ ကိရိယာတွေ ပါဝင်နိုင်ပါတယ်။

## Example of a False Positive

- **English**: Consider this example. You're a cloud security professional. You've configured your intrusion detection system to create an alert if it identifies a threat. One day, the alert goes off. After investigating the alert, you determined that it was generated by normal behavior, so there was no harmful impact. That's a false positive.
- **Burmese**: ဥပမာတစ်ခုကို စဉ်းစားကြည့်ပါ။ သင်က cloud security professional တစ်ယောက်ဖြစ်တယ်။ သင့်ရဲ့ intrusion detection system ကို ခြိမ်းခြောက်မှုတစ်ခုကို ဖော်ထုတ်မိရင် သတိပေးချက်ထုတ်ဖို့ ပြင်ဆင်ထားတယ်။ တစ်နေ့မှာ သတိပေးချက်က ပွင့်သွားတယ်။ သတိပေးချက်ကို စစ်ဆေးပြီးနောက် ဒါက ပုံမှန်အပြုအမူကြောင့် ဖြစ်ပေါ်လာတာကို သိရှိလိုက်တယ်၊ ဒါကြောင့် ဘာအန္တရာယ်မှ မရှိဘူး။ ဒါက false positive တစ်ခုဖြစ်ပါတယ်။

## Impact of False Positives

- **English**: As a Cloud security professional, it's important to recognize false positives because they have a big impact on security operations. Specifically, incident management and attack mitigation. False positives can also negatively impact a team's confidence, effectiveness, speed, and resources.
- **Burmese**: Cloud security professional တစ်ယောက်အနေနဲ့ false positives တွေကို သိရှိဖို့ အရေးကြီးပါတယ်။ ဘာကြောင့်လဲဆိုတော့ သူတို့က security operations အပေါ် ကြီးမားတဲ့ သက်ရောက်မှုရှိလို့ပါ။ အထူးသဖြင့် incident management နဲ့ attack mitigation တို့မှာပါ။ False positives တွေက အဖွဲ့တစ်ဖွဲ့ရဲ့ ယုံကြည်မှု၊ ထိရောက်မှု၊ မြန်ဆန်မှု၊ နဲ့ အရင်းအမြစ်တွေအပေါ် ဆိုးကျိုးသက်ရောက်မှုရှိနိုင်ပါတယ်။

### Alert Fatigue

- **English**: False positives also impact security professionals by creating a phenomenon called alert fatigue. Alert fatigue is the result of all noise and no signal in security environments. Alert fatigue happens when there are so many alerts that need to be addressed, it overwhelms a security team.
- **Burmese**: False positives တွေက alert fatigue လို့ခေါ်တဲ့ ဖြစ်စဉ်တစ်ခုကို ဖန်တီးခြင်းဖြင့် security professionals တွေအပေါ် သက်ရောက်မှုရှိပါတယ်။ Alert fatigue ဆိုတာက security environment တွေမှာ noise တွေအများကြီးရှိပြီး signal မရှိတာကြောင့် ဖြစ်ပေါ်လာတဲ့ ရလဒ်ဖြစ်ပါတယ်။ Alert fatigue က သတိပေးချက်တွေ အများကြီးရှိနေပြီး security team တစ်ဖွဲ့ကို လွန်ကဲစွာ ဖိစီးမှုဖြစ်စေတဲ့အခါမှာ ဖြစ်ပေါ်ပါတယ်။

### Consequences of False Positives

- **English**: False positive alerts can have significant consequences like wasted time, loss of resources, and increased stress levels. They can also increase exposure to attacks because real threats are being misjudged. These misjudged threats are called false negatives.
- **Burmese**: False positive alerts တွေက အချိန်ဖြုန်းတာ၊ အရင်းအမြစ်တွေ ဆုံးရှုံးတာ၊ နဲ့ စိတ်ဖိစီးမှုတွေ တိုးလာတာလို ကြီးမားတဲ့ ဆိုးကျိုးတွေ ရှိနိုင်ပါတယ်။ သူတို့က တကယ့်အန္တရာယ်တွေကို မှားယွင်းစွာ အကဲဖြတ်မိတာကြောင့် တိုက်ခိုက်မှုတွေကို ပိုမိုထိတွေ့စေနိုင်ပါတယ်။ ဒီလို မှားယွင်းစွာ အကဲဖြတ်မိတဲ့ အန္တရာယ်တွေကို false negatives လို့ ခေါ်ပါတယ်။

## Common Causes of False Positives

- **English**: False positives can be created from a range of situations like misconfigurations in tools and systems. Over-engineered detection strategies, or even unaccounted changes within the Cloud environment.
- **Burmese**: False positives တွေက ကိရိယာတွေနဲ့ စနစ်တွေမှာ မှားယွင်းစွာ ပြင်ဆင်ထားတာ၊ over-engineered detection strategies တွေ၊ ဒါမှမဟုတ် Cloud environment အတွင်းက မမျှော်လင့်ထားတဲ့ ပြောင်းလဲမှုတွေလို အခြေအနေမျိုးစုံကနေ ဖြစ်ပေါ်နိုင်ပါတယ်။

## Best Practices for Managing False Positives

- **English**: False positive reduction strategies include continuously testing and fine-tuning security systems. Consistently monitoring logs and alerts, Communicating any configuration changes, and contributing to a culture of continuous learning and improvement.
- **Burmese**: False positive တွေကို လျှော့ချဖို့ နည်းဗျူဟာတွေထဲမှာ security systems တွေကို အဆက်မပြတ် စမ်းသပ်ပြီး ပြင်ဆင်တာ၊ logs နဲ့ alerts တွေကို အမြဲမပြတ် စောင့်ကြည့်တာ၊ configuration changes တွေကို ဆက်သွယ်ပြောဆိုတာ၊ နဲ့ အဆက်မပြတ် သင်ယူပြီး တိုးတက်အောင် ကြိုးစားတဲ့ ယဉ်ကျေးမှုတစ်ခုကို ဖန်တီးတာတွေ ပါဝင်ပါတယ်။

## Conclusion

- **English**: By reducing false positives, you can increase the chances that your team can quickly and confidently identify genuine threats. As you dig deeper into Cloud security operations, remember that effectively managing false positives is one of the keys to maintaining a strong security posture.
- **Burmese**: False positives တွေကို လျှော့ချခြင်းဖြင့် သင့်အဖွဲ့က တကယ့်အန္တရာယ်တွေကို မြန်မြန်ဆန်ဆန်နဲ့ ယုံကြည်စွာ ဖော်ထုတ်နိုင်ဖို့ အခွင့်အလမ်းတွေ တိုးလာနိုင်ပါတယ်။ Cloud security operations တွေကို ပိုမိုနက်နက်နဲနဲ လေ့လာတဲ့အခါမှာ false positives တွေကို ထိရောက်စွာ စီမံခန့်ခွဲခြင်းက ခိုင်မာတဲ့ security posture တစ်ခုကို ထိန်းသိမ်းဖို့ အဓိက အချက်တစ်ခုဖြစ်တယ်ဆိုတာ သတိရပါ။
