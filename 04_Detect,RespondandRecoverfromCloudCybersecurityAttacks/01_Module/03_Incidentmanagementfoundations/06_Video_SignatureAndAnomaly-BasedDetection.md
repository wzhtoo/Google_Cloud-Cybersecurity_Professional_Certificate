# Signature and anomaly-based detection

[Signature and anomaly-based detection 🔗](https://www.coursera.org/learn/detect-respond-and-recover-from-cloud-cybersecurity-attacks/lecture/HBk5I/signature-and-anomaly-based-detection)

A signature actively checks packet patterns for any malicious activity, using factors like IP addresses, used ports, type of protocol, and payload details.

# Signature-Based and Anomaly-Based Detection in Network Security

**Signature-Based Detection** နှင့် **Anomaly-Based Detection** သည် Network Security တွင် အသုံးပြုသော အန္တရာယ်ဖော်ထုတ်ရေး နည်းလမ်းနှစ်မျိုးဖြစ်ပါတယ်။ ဤနည်းလမ်းများသည် မသမာသော လှုပ်ရှားမှုများကို ဖော်ထုတ်ရန် ကူညီပေးပါတယ်။

## **Signature-Based Detection**

**Signature-Based Detection** သည် မသမာသော လှုပ်ရှားမှုများနှင့် ဆက်စပ်နိုင်သော **Patterns** (ပုံစံများ) ကို အသုံးပြုပါတယ်။

### **Signature ၏ အဓိကလုပ်ဆောင်ချက်များ**

- **IP Addresses**, **Ports**, **Protocols**, နှင့် **Payload Details** ကဲ့သို့သော အချက်များကို အသုံးပြု၍ မသမာသော လှုပ်ရှားမှုများကို ဖော်ထုတ်ပါတယ်။
- **Signature Database** ကို ပုံမှန်ပြင်ဆင်ပြီး Update လုပ်ရပါမယ်။

### **Signature Database**

- **Signature Database** တွင် မသမာသော လှုပ်ရှားမှုများကို ဖော်ထုတ်နိုင်သော **Patterns** များ ပါဝင်ပါတယ်။
- Network Traffic ကို စိစစ်ပြီး၊ Signature များနှင့် နှိုင်းယှဉ်ကာ အန္တရာယ်ရှိမရှိ ဆုံးဖြတ်ပါတယ်။

### **ဥပမာ - Python Dictionary Signature**

```python
signature = {
    "source_ip": "192.168.1.100",
    "destination_port": 80,
    "protocol": "TCP",
    "payload": "exploit_payload"
}
```

### Anomaly-Based Detection

**Anomaly-Based Detection** သည် Network ၏ **Normal Behavior** (ပုံမှန်လုပ်ဆောင်မှု) ကို အခြေခံ၍၊ ပုံမှန်မဟုတ်သော လှုပ်ရှားမှုများကို ဖော်ထုတ်ပါတယ်။

### Anomaly-Based Detection ၏ အဓိကလုပ်ဆောင်ချက်များ

- Network ၏ Baseline (ပုံမှန်လုပ်ဆောင်မှု) ကို ဖန်တီးပါတယ်။

- လက်ရှိ Network Traffic ကို Baseline နှင့် နှိုင်းယှဉ်ကာ၊ ပုံမှန်မဟုတ်သော လှုပ်ရှားမှုများကို ဖော်ထုတ်ပါတယ်။

### ဥပမာ - SQL Query for Anomaly Detection

```sql
SELECT source_ip, destination_port, protocol, COUNT(*) as traffic_count
FROM network_traffic
WHERE timestamp BETWEEN '2023-01-01' AND '2023-01-31'
GROUP BY source_ip, destination_port, protocol;
```

- ဤ SQL Query သည် Network ၏ **ပုံမှန်လုပ်ဆောင်မှု** ကို ဖော်ထုတ်ရန် **Source IP, Destination Port**, နှင့် **Protocol** များကို အသုံးပြုပါတယ်။

- **Baseline** ကို ဖန်တီးပြီး၊ လက်ရှိ Traffic ကို နှိုင်းယှဉ်ကာ Anomalies များကို ဖော်ထုတ်ပါတယ်။

# Signature-Based vs Anomaly-Based Detection

- **Signature-Based Detection**

  - သိထားပြီးသော အန္တရာယ်များကို ဖော်ထုတ်ရာတွင် ထိရောက်ပါတယ်။

  - Signature Database ကို ပုံမှန် Update လုပ်ရပါမယ်။

- **Anomaly-Based Detection**

  - မသိသေးသော အန္တရာယ်များကို ဖော်ထုတ်ရာတွင် ထိရောက်ပါတယ်။

  - Network ၏ ပုံမှန်လုပ်ဆောင်မှုကို အခြေခံထားသောကြောင့်၊ ပုံမှန်မဟုတ်သော လှုပ်ရှားမှုများကို ဖော်ထုတ်နိုင်ပါတယ်။

# အကျဉ်းချုပ်

**Signature-Based Detection** နှင့် **Anomaly-Based Detection** သည် Network Security တွင် အရေးပါသော နည်းလမ်းနှစ်မျိုးဖြစ်ပါတယ်။ Signature-Based Detection သည် သိထားပြီးသော အန္တရာယ်များကို ဖော်ထုတ်ရာတွင် ထိရောက်ပြီး၊ Anomaly-Based Detection သည် မသိသေးသော အန္တရာယ်များကို ဖော်ထုတ်ရာတွင် ထိရောက်ပါတယ်။ ဤနည်းလမ်းနှစ်မျိုးကို ပေါင်းစပ်အသုံးပြုခြင်းဖြင့်၊ Network Security ကို ပိုမိုခိုင်မာစေနိုင်ပါတယ်။
