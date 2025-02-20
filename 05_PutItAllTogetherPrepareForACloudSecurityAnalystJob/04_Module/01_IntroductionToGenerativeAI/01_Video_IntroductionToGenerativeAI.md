# Introduction to Generative AI

[Introduction to Generative AI 🔗](https://www.coursera.org/learn/put-it-all-together-prepare-for-a-cloud-security-analyst-job/lecture/TJ28r/introduction-to-generative-ai)

# မျိုးဆက် AI နိဒါန်း 🤖

## မိတ်ဆက် 🤝

- **အင်္ဂလိပ်**: Hi, and welcome to "Introduction to Generative AI." Don't know what that is? Then you're in the perfect place. I'm Roger Martinez and I am a Developer Relations Engineer at Google Cloud, and it's my job to help developers learn to use Google Cloud. In this course, I'll teach you four things, how to define generative AI, explain how generative AI works, describe generative AI model types, describe generative AI applications. But let's not get swept away with all of that yet, let's start by defining what generative AI is first. Generative AI has become a buzzword, but what is it? Generative AI is a type of artificial intelligence technology that can produce various types of content, including text, imagery, audio, and synthetic data.
- **မြန်မာ**: ဟိုင်း၊ "မျိုးဆက် AI နိဒါန်း" သို့ ကြိုဆိုပါတယ်။ ဘာလဲ မသိဘူးလား။ ဒါဆို သင်သည် ပြီးပြည့်စုံသော နေရာတွင် ရှိနေပါသည်။ ကျွန်ုပ် Roger Martinez ဖြစ်ပြီး Google Cloud တွင် Developer Relations Engineer တစ်ဦးဖြစ်ပြီး၊ ကျွန်ုပ်၏ အလုပ်မှာ developer များအား Google Cloud ကို အသုံးပြုရန် သင်ယူရန် ကူညီပေးခြင်းဖြစ်သည်။ ဤသင်တန်းတွင်၊ မျိုးဆက် AI ကို မည်သို့ အဓိပ္ပာယ်ဖွင့်ဆိုပုံ၊ မျိုးဆက် AI မည်သို့အလုပ်လုပ်ပုံကို ရှင်းပြပုံ၊ မျိုးဆက် AI မော်ဒယ်အမျိုးအစားများကို ဖော်ပြပုံနှင့် မျိုးဆက် AI အသုံးချမှုများကို ဖော်ပြပုံ အပါအဝင် အချက်လေးခုကို သင်ကြားပေးပါမည်။ သို့သော် ထိုအရာအားလုံးနှင့် အတူ မပျံ့လွင့်သွားပါစေနှင့်၊ မျိုးဆက် AI ဆိုသည်ကို ဦးစွာ အဓိပ္ပာယ်ဖွင့်ဆိုခြင်းဖြင့် စတင်ကြပါစို့။ မျိုးဆက် AI သည် ခေတ်စားသော စကားလုံးတစ်ခု ဖြစ်လာခဲ့ပြီ၊ သို့သော် ၎င်းသည် ဘာလဲ။ မျိုးဆက် AI သည် စာသား၊ ပုံရိပ်များ၊ အသံနှင့် ပေါင်းစပ်ဒေတာများ အပါအဝင် အမျိုးမျိုးသော အကြောင်းအရာများကို ထုတ်လုပ်နိုင်သည့် artificial intelligence နည်းပညာတစ်မျိုးဖြစ်သည်။

---

## Artificial Intelligence ဆိုတာဘာလဲ။ 🤖

- **အင်္ဂလိပ်**: But what is artificial intelligence? Since we are going to explore generative artificial intelligence, let's provide a bit of context. Two very common questions asked are: What is artificial intelligence? And what is the difference between AI and machine learning? Let's get into it. So one way to think about it is that AI is a discipline, like how physics is a discipline of science. AI is a branch of computer science that deals with the creation of intelligent agents and are systems that can reason, learn, and act autonomously. Are you with me so far? Essentially, AI has to do with the theory and methods to build machines that think and act like humans. Pretty simple, right?
- **မြန်မာ**: Artificial intelligence ဆိုတာဘာလဲ။ ကျွန်ုပ်တို့သည် မျိုးဆက် artificial intelligence ကို လေ့လာရန် သွားသောကြောင့်၊ အနည်းငယ် အကြောင်းအရာ ပေးကြပါစို့။ မေးလေ့ရှိသော မေးခွန်းနှစ်ခုမှာ- Artificial intelligence ဆိုတာဘာလဲ။ AI နဲ့ machine learning ကွာခြားချက်ကဘာလဲ။ စတင်ကြပါစို့။ ထို့ကြောင့် ၎င်းကို စဉ်းစားရန် နည်းလမ်းတစ်ခုမှာ AI သည် ရူပဗေဒသည် သိပ္ပံ၏ စည်းကမ်းတစ်ခုကဲ့သို့ စည်းကမ်းတစ်ခုဖြစ်သည်။ AI သည် ကွန်ပျူတာသိပ္ပံ၏ အခက်အလက်တစ်ခုဖြစ်ပြီး၊ ၎င်းသည် အသိဉာဏ်ရှိသော agent များ ဖန်တီးခြင်းနှင့် ကျိုးကြောင်းဆင်ခြင်နိုင်၊ သင်ယူနိုင်ပြီး ကိုယ်ပိုင်အုပ်ချုပ်နိုင်သော စနစ်များနှင့် သက်ဆိုင်သည်။ ယခုအထိ ကျွန်ုပ်တို့နှင့် အတူရှိနေပါသလား။ အခြေခံအားဖြင့်၊ AI သည် လူကဲ့သို့ တွေးခေါ်လုပ်ဆောင်နိုင်သော စက်များကို တည်ဆောက်ရန် သီအိုရီနှင့် နည်းလမ်းများနှင့် သက်ဆိုင်သည်။ အတော်လေး ရိုးရှင်းတယ်ဟုတ်လား။

---

## Machine Learning ဆိုတာဘာလဲ။ ⚙️

- **အင်္ဂလိပ်**: Now, let's talk about machine learning. Machine learning is a subfield of AI. It is a program or system that trains a model from input data. The trained model can make useful predictions from new, never before seen data drawn from the same one used to train the model. This means that machine learning gives the computer the ability to learn without explicit programming. So what do these machine learning models look like? Two of the most common classes of machine learning models are unsupervised and supervised ML models. The key difference between the two is that with supervised models, we have labels. Labeled data is data that comes with a tag, like a name, a type, or a number.
- **မြန်မာ**: ယခု machine learning အကြောင်း ပြောကြပါစို့။ Machine learning သည် AI ၏ အခက်အလက်တစ်ခုဖြစ်သည်။ ၎င်းသည် input data မှ မော်ဒယ်တစ်ခုကို လေ့ကျင့်ပေးသော ပရိုဂရမ် သို့မဟုတ် စနစ်တစ်ခုဖြစ်သည်။ လေ့ကျင့်ထားသော မော်ဒယ်သည် မော်ဒယ်ကို လေ့ကျင့်ရန် အသုံးပြုသည့် အရာတစ်ခုတည်းမှ ရယူထားသော၊ အသစ်၊ အရင်က မမြင်ဖူးသော ဒေတာမှ အသုံးဝင်သော ခန့်မှန်းချက်များကို ပြုလုပ်နိုင်သည်။ ဆိုလိုသည်မှာ machine learning သည် ကွန်ပျူတာအား အတိအကျ ပရိုဂရမ်မပါဘဲ သင်ယူနိုင်စွမ်းကို ပေးသည်။ ဤ machine learning မော်ဒယ်များသည် မည်သို့ပုံစံရှိသနည်း။ Machine learning မော်ဒယ်များ၏ အသုံးအများဆုံး အတန်းနှစ်ခုမှာ unsupervised နှင့် supervised ML မော်ဒယ်များဖြစ်သည်။ နှစ်ခုကြား အဓိက ကွာခြားချက်မှာ supervised မော်ဒယ်များတွင် ကျွန်ုပ်တို့တွင် label များရှိသည်။ Labeled data ဆိုသည်မှာ အမည်၊ အမျိုးအစား သို့မဟုတ် နံပါတ်ကဲ့သို့သော tag တစ်ခုပါရှိသော data ဖြစ်သည်။

# Supervised vs. Unsupervised Learning: Understanding the Difference

**Supervised Learning** နှင့် **Unsupervised Learning** သည် Machine Learning ၏ အဓိက နည်းလမ်းနှစ်မျိုးဖြစ်ပြီး၊ ၎င်းတို့၏ ကွာခြားချက်များကို နားလည်ရန် အရေးကြီးပါတယ်။ ဤသင်ခန်းစာတွင်၊ ဤနည်းလမ်းနှစ်မျိုး၏ ဥပမာများကို ဖော်ပြထားပါတယ်။

---

## **Supervised Learning**

**Supervised Learning** တွင်၊ Model သည် **Labeled Data** (တံဆိပ်ကပ်ထားသော ဒေတာ) များကို အသုံးပြု၍ သင်ယူပါတယ်။ ဤနည်းလမ်းသည် အတိတ်ဒေတာများကို အခြေခံ၍ အနာဂတ်တန်ဖိုးများကို ခန့်မှန်းရန် ရည်ရွယ်ပါတယ်။

### **ဥပမာ - Restaurant Tips Prediction**

- **ပြဿနာ** - စားသောက်ဆိုင်တစ်ခုတွင်၊ မတူညီသော မှာယူမှုအမျိုးအစား (Pickup or Delivery) အပေါ်မူတည်၍ လက်ဆောင်ငွေ (Tip) ကို ခန့်မှန်းရန်။
- **ဒေတာ** - အတိတ်ဒေတာများတွင်၊ မှာယူမှု၏ **Total Bill Amount** နှင့် **Tip Amount** ပါဝင်ပါတယ်။
- **Model** - Total Bill Amount နှင့် Order Type (Pickup/Delivery) ကို အသုံးပြု၍၊ အနာဂတ် Tip Amount ကို ခန့်မှန်းပါတယ်။

---

## **Unsupervised Learning**

**Unsupervised Learning** တွင်၊ Model သည် **Unlabeled Data** (တံဆိပ်မကပ်ထားသော ဒေတာ) များကို အသုံးပြု၍ သင်ယူပါတယ်။ ဤနည်းလမ်းသည် ဒေတာများကို သဘာဝအတိုင်း အုပ်စုဖွဲ့ရန် ရည်ရွယ်ပါတယ်။

### **ဥပမာ - Employee Clustering**

- **ပြဿနာ** - ဝန်ထမ်းများ၏ **Tenure** (အလုပ်သက်တမ်း) နှင့် **Income** (ဝင်ငွေ) ကို အသုံးပြု၍၊ မည်သူသည် Fast Track (အမြန်တိုးတက်မှု) တွင် ရှိသည်ကို အုပ်စုဖွဲ့ရန်။
- **Model** - Tenure နှင့် Income ကို အသုံးပြု၍၊ ဝန်ထမ်းများကို သဘာဝအုပ်စုများအဖြစ် ခွဲခြားပါတယ်။

---

## **Supervised vs. Unsupervised Learning: Graphical Representation**

- **Supervised Learning** - ဒေတာများကို **Labeled** အဖြစ် သတ်မှတ်ပြီး၊ Model သည် အတိတ်ဒေတာများကို အခြေခံ၍ အနာဂတ်တန်ဖိုးများကို ခန့်မှန်းပါတယ်။
- **Unsupervised Learning** - ဒေတာများကို **Unlabeled** အဖြစ် သတ်မှတ်ပြီး၊ Model သည် ဒေတာများကို သဘာဝအုပ်စုများအဖြစ် ခွဲခြားပါတယ်။

---

## **Generative AI နှင့် ဆက်စပ်မှု**

- **Supervised Learning** - Generative AI တွင်၊ Labeled Data များကို အသုံးပြု၍၊ အနာဂတ်တန်ဖိုးများကို ခန့်မှန်းရန် သင်ယူပါတယ်။
- **Unsupervised Learning** - Generative AI တွင်၊ Unlabeled Data များကို အသုံးပြု၍၊ ဒေတာများကို သဘာဝအုပ်စုများအဖြစ် ခွဲခြားရန် သင်ယူပါတယ်။

---

**အကျဉ်းချုပ်**  
Supervised Learning နှင့် Unsupervised Learning သည် Machine Learning ၏ အခြေခံဖြစ်ပြီး၊ Generative AI ကို နားလည်ရာတွင် အရေးပါသော အစိတ်အပိုင်းများဖြစ်ပါတယ်။ Supervised Learning သည် Labeled Data ကို အသုံးပြု၍ ခန့်မှန်းခြင်းကို ဦးတည်ပြီး၊ Unsupervised Learning သည် Unlabeled Data ကို အသုံးပြု၍ အုပ်စုဖွဲ့ခြင်းကို ဦးတည်ပါတယ်။

# Supervised Learning တွင် Error နှင့် Optimization

**Supervised learning** တွင်၊ testing data values, X, ကို model ထဲသို့ ထည့်သွင်းပေးပါတယ်။ Model က prediction တစ်ခုကို ထုတ်ပေးပြီး model ကို train ရန် အသုံးပြုခဲ့သော training data နှင့် နှိုင်းယှဉ်ပါတယ်။ predicted test data values များနှင့် actual training data values များ အလွန်ကွာခြားပါက၊ ၎င်းကို "Error" ဟုခေါ်သည်။ Model သည် predicted နှင့် actual values များ ပိုမိုနီးကပ်လာသည်အထိ ဤ error ကို လျှော့ချရန် ကြိုးစားသည်။ ၎င်းသည် ဂန္ထဝင် optimization ပြဿနာတစ်ခုဖြစ်သည်။

---

# Deep Learning

## မိတ်ဆက်

Neural networks သည် အမှတ်အသားပြုထားသော ဒေတာနှင့် မအမှတ်အသားပြုထားသော ဒေတာနှစ်မျိုးလုံးကို အသုံးပြုနိုင်ပါသည်။ ၎င်းကို semi-supervised learning ဟု ခေါ်သည်။ semi-supervised learning တွင် neural network ကို အမှတ်အသားပြုထားသော ဒေတာ အနည်းငယ်နှင့် မအမှတ်အသားပြုထားသော ဒေတာ အများအပြားဖြင့် လေ့ကျင့်သည်။ အမှတ်အသားပြုထားသော ဒေတာသည် neural network ကို တာဝန်များ၏ အခြေခံအယူအဆများကို လေ့လာရန် အကူအညီပြုမည်ဖြစ်ပြီး၊ မအမှတ်အသားပြုထားသော ဒေတာသည် neural network ကို နမူနာအသစ်များသို့ သွားရောက်နိုင်ရန် အကူအညီပြုမည်ဖြစ်သည်။ ယခုတွင် AI စာပညာစနစ်တွင် generative AI သည် မည်သည့်နေရာတွင် ပါဝင်ကြောင်းကို နောက်ဆုံးတွင် ရောက်ရှိလာပါသည်။ Gen AI သည် deep learning ၏ အစိတ်အပိုင်းတစ်ခုဖြစ်သဖြင့်၊ ၎င်းသည် artificial neural networks ကို အသုံးပြုပြီး၊ အမှတ်အသားပြုထားသောနှင့် မအမှတ်အသားပြုထားသော ဒေတာနှစ်မျိုးလုံးကို အကူအညီဖြင့်၊ မအကူအညီဖြင့် နှင့် semi-supervised နည်းလမ်းများဖြင့် လုပ်ဆောင်နိုင်ပါသည်။ Large language models သည်လည်း deep learning ၏ အစိတ်အပိုင်းတစ်ခုဖြစ်ပါသည်။ ကြည့်ပါ၊ ကျွန်ုပ်သည် ၎င်းကို Gen AI သို့ ပြန်လည်ဆောင်ကြဉ်းပေးလိုက်ပါပြီ။ ကျွန်ုပ်ကောင်းတယ်။

## Deep Learning ဆိုတာဘာလဲ။

Deep learning မော်ဒယ်များ သို့မဟုတ် machine learning မော်ဒယ်များကို ယေဘူယျအားဖြင့် two types အဖြစ်ခွဲခြားနိုင်သည်၊ generative နှင့် discriminative တို့ဖြစ်ပါသည်။

## Discriminative မော်ဒယ်

Discriminative မော်ဒယ်သည် ဒေတာအချက်များအတွက် အမှတ်အသားများကို သတ်မှတ်ရန် သို့မဟုတ် ခန့်မှန်းရန် အသုံးပြုသည့် မော်ဒယ်တစ်မျိုးဖြစ်သည်။ Discriminative မော်ဒယ်များသည် မကြာခဏ အမှတ်အသားပြုထားသော ဒေတာအချက်များ၏ dataset တွင် လေ့ကျင့်ကြပြီး၊ ၎င်းတို့သည် ဒေတာအချက်များ၏ features နှင့် အမှတ်အသားများအကြား ဆက်ဆံရေးကို လေ့လာကြသည်။ Discriminative မော်ဒယ်ကို လေ့ကျင့်ပြီးပြီးနောက်၊ ၎င်းကို ဒေတာအချက်အသစ်များအတွက် အမှတ်အသားကို ခန့်မှန်းရန် အသုံးပြုနိုင်သည်။

## Generative မော်ဒယ်

Generative မော်ဒယ်သည် ရှိပြီးသား ဒေတာ၏ လေ့လာထားသော probability distribution အပေါ် အခြေခံကာ ဒေတာအချက် အသစ်များကို ဖန်တီးသည်။ Generative မော်ဒယ်များသည် အကြောင်းအရာအသစ်များကို ဖန်တီးသည်။ ဥပမာအားဖြင့်- ဤနေရာတွင်၊ discriminative မော်ဒယ်သည် conditional probability distribution သို့မဟုတ် အထွေထွေ probability ကို သင်ယူ၍၊ ရှိသော ဒေတာ X အရ အထွေထွေ output Y သို့သွားပြီး၊ ၎င်းသည် သတ်မှတ်ထားသော ၎င်းအချက်အလက်ကို နောက်ဆုံးတွင် ရွေးချယ်သည်၊ ဤကဲ့သို့ မှန်ကန်စွာ ခွဲခြား၍ cat မဟုတ်ဘဲ dog ဟု သတ်မှတ်သည်။ Generative မော်ဒယ်သည် joint probability distribution သို့မဟုတ် X နှင့် Y, P of XY ကို သင်ယူပြီး၊ ဤသည် dog ဖြစ်သည်ကို ခန့်မှန်းပြီး၊ dog ရုပ်ပုံကို ပြန်ဖန်တီးနိုင်သည်။ ကောင်းစွာမှီခိုနိုင်သော ခွေးလေးပါ။ ၎င်း၏ အမည်ကို Fred ဟု အမည်တပ်လိုက်သည်။ အကျဉ်းချုပ်အားဖြင့်၊ generative မော်ဒယ်များသည် ဒေတာအချက်အသစ်များကို ဖန်တီးနိုင်ပြီး၊ discriminative မော်ဒယ်များသည် မတူညီသော ဒေတာအချက်များအကြား ခွဲခြားပေးသည်။

## Traditional Machine Learning မော်ဒယ်နှင့် Generative AI မော်ဒယ်

Traditional machine learning မော်ဒယ်သည် ဒေတာနှင့် အမှတ်အသား၊ သို့မဟုတ် သင့်ရဲ့ ခန့်မှန်းလိုသော အရာများအကြား ဆက်စပ်မှုကို လေ့လာရန် ကြိုးစားသည်။ အောက်ခြေတွင်ပါတဲ့ရုပ်ပုံသည် အကြောင်းအရာအပေါ်ပုံစံများကို လေ့လာပြီး အကြောင်းအရာအသစ်များကို ဖန်တီးနိုင်စေရန် ကြိုးစားနေသော generative AI မော်ဒယ်ဖြစ်သည်။

သင့်အား "Is It Gen AI or Not?" ဆိုတဲ့ဂိမ်းကို ရင်ဆိုင်ခေါ်မလားဆိုရင်၊ ကျွန်ုပ်သည် သင့်ကို ကူညီပါမည်။

ဤပုံသည် ဘာဟာက Gen AI နှင့် ဘာဟာက မဟုတ်ကြောင်း ခွဲခြားဖို့ ကောင်းတဲ့နည်းလမ်းတစ်ခုကို ပြသသည်။

Output, သို့မဟုတ် Y, သို့မဟုတ် အမှတ်အသားသည် နံပါတ်တစ်ခု သို့မဟုတ် အတန်းတစ်ခုဖြစ်သည့်အခါမှာ Gen AI မဟုတ်ပါဘူး။ ဥပမာ၊ spam သို့မဟုတ် spam မဟုတ်သော နံပါတ်နှင့် probability တို့ဖြစ်သည်။

Output သည် သဘာဝဘာသာစကားဖြစ်သော စကား သို့မဟုတ် စာသား၊ အသံ သို့မဟုတ် ယခင်က Fred ကဲ့သို့ ရုပ်ပုံဖြစ်သည့်အခါမှာ Gen AI ဖြစ်သည်။

### သင်ခန်းစာနည်းပညာနှင့် သက်ဆိုင်သောနည်းလမ်း

ဤကွာခြားချက်ကို သင်ခန်းစာနည်းပညာဖြင့်မြင်နိုင်ရန် အတော်လေးမိုးသည်။ y = f(x) ဆန်းစစ်ချက်သည် input များကွဲပြားခြားနားသောအချက်အလက်ဖြင့် နည်းပြုလုပ်မှု၏ အမှုထမ်း output ကိုတွက်ချက်သည်။ Y သည် မော်ဒယ် output ကို ကိုယ်စားပြုပြီး၊ F သည်တွက်ချက်မှု သို့မဟုတ် မော်ဒယ်တွင် အသုံးပြုသည် function ကို ကိုယ်စားပြုပါသည်၊ X သည် formula သင်္ချာပညာတွင် အသုံးပြုသည့် input သို့မဟုတ် input များကို ကိုယ်စားပြုပါသည်။

Input များသည် data ဖြစ်ပါသည်။ comma separated value files, text files, audio files, သို့မဟုတ် Fred ကဲ့သို့ image files တို့ဖြစ်သည်။ ထို့ကြောင့် မော်ဒယ် output သည် အားလုံး input များ၏ function ဖြစ်သည်။ Y သည် နံပါတ်ဖြစ်သည့် အခါမျိုးများတွင်၊ ဥပမာ၊ sales ခန့်မှန်းချက်အဖြစ်၊ ၎င်းသည် generative AI မဟုတ်ပါ။

Y သည် စာပိုဒ်ဖြစ်သည့် အခါမျိုးများတွင်၊ sales ကို အဓိပ္ပါယ်ဖွင့်ဆိုရန် ကဲ့သို့သော တုံ့ပြန်ချက်ကို အကြောင်းဖန်တီးနိုင်သော text response တစ်ခုကို မေးခွန်းထည့်ထားခြင်းဖြစ်သည်။ မော်ဒယ်သည် အကြီးမားသော အချက်အလက်များပေါ်တွင် ထည့်သွင်းသင်ကြားထားခြင်းမော်ဒယ်များသည် training code နှင့် labeled data ကို အသုံးပြုကာ မော်ဒယ်တစ်ခုကို ဖန်တီးရပါသည်။

သုံးသပ်သည့် ရည်မှန်းချက် သို့မဟုတ် ပြဿနာအပေါ်မူတည်ပြီး၊ မော်ဒယ်သည် ခန့်မှန်းချက်၊ အသင်းခွဲခြားမှု သို့မဟုတ် clustering ပြုလုပ်နိုင်သည်။

အခုတော့၊ generative AI ပရိုဆက်၏ အားသာချက်များကို ပိုမိုကောင်းမွန်စွာ ကြည့်ပါစို့။

## Generative AI ပရိုဆက်

Generative AI ပရိုဆက်သည် training code, labeled data နှင့် unlabeled data များကို အားလုံးအမျိုးအစားသုံးပြီး foundation မော်ဒယ်တစ်ခုကို ဆောက်နိုင်ပါသည်။ Foundation မော်ဒယ်က အကြောင်းအရာအသစ်များကို ဖန်တီးနိုင်ပြီး၊ စာသား, code, ရုပ်ပုံများ, အသံ, ဗီဒီယိုများ နှင့် အခြားအရာများကို ဖန်တီးနိုင်သည်။ ကျွန်ုပ်တို့သည် အခြားသောမျိုးစုံအမျိုးအစားများ၏ ရှေးဦးကနေ neural networks တွေကိုထောက်ပံ့ပါသည်။

လက်မခံနိုင်ပုံသည် ကျွန်ုပ်တို့၏ အသီးအသီး အပူမတူသော ဆက်သွယ်မှုများကို ကုန်ကျသိပ်မိန်ဆက်ရန် ကြိုးစားရကြသည်။ ပြီးတော့ ပို၍ ကောင်းသော ပုံစံပါ။ ဒါမှမဟုတ်၊ "Is this a cat?" ဆိုပြီး မေးမြန်းနိုင်သည်၊ "A cat," ဆိုင်းငံ့ခြင်း ဖြစ်စေ၊ "Not a cat." အမျိုးမျိုးဖြစ်ပါသည်။

ယခု ပိုမိုပေါ့ပါးသော ကျွန်ုပ်တို့အသုံးပြုနေသော AI အထောက်အထားသည် သင့်ကို စာပိုဒ်သေးငယ်ငယ်မျှ ကမ္ဘာဖြစ်စေမှာဖြစ်သည်။ ဟုတ်ပါတယ်၊ AI မော်ဒယ်သုံးပြီး ရေးဆွဲထားသော ချက်ပြုတ်စာအုပ်ကိုတွေ့ရကြမှာပါ။

ဗုဒ္ဓဟုကို မေးလျှင် "What's a cat?" ဟုမေးလျှင် ၎င်းသည် ဤအသိပညာမကို အပြီးအပြည့် အဖြေချင်းပြုနိုင်မည်ဟု မေးခွန်းနားစားသည်။

ယခု အခုပြီးမှ စံချိန်စိပ်အဖြေမေးထားသော generative AI ဖြစ်သည်။ Generative AI သည် ရှိပြီးသားအကြောင်းအရာထဲမှ သင်ယူထားသောအကြောင်းအရာပေါ် အခြေခံ၍ အကြောင်းအရာအသစ်များကို ဖန်တီးပေးသော အမျိုးအစားအတစ်ခု ဖြစ်သည်။ ရှိပြီးသားအကြောင်းအရာမှ သင်ယူခြင်းဖြစ်စဉ်ကို training ဟုခေါ်ပြီး၊ ၎င်းသည် သင်္ချာပညာသုံးမော်ဒယ်တစ်ခုကို ဖန်တီးပေးခြင်းဖြစ်သည်။

## Generative AI မော်ဒယ်များ

ပေးထားသော prompt များအပေါ်တွင် Gen AI သည် statistical model ကို အသုံးပြုကာ မျှော်မှန်းထားသည့် တုံ့ပြန်ချက်ကို ခန့်မှန်းပြီး အကြောင်းအရာအသစ်ကို ဖန်တီးသည်။ ၎င်းသည် ဒေတာ၏ အခြေခံဖွဲ့စည်းပုံကို သင်ယူပြီး၊ သင်ကြားထားသော ဒေတာနှင့် ဆင်တူသော နမူနာအသစ်များကို ဖန်တီးနိုင်သည်။ မူလက ပြောခဲ့သလို၊ generative language မော်ဒယ်တစ်ခုသည် ပြထားသည့် နမူနာများမှ သင်ယူထားသည့် အချက်အလက်ကို ချက်ချင်း အသစ်အဖြစ် ဖန်တီးနိုင်သည်။ ထို့ကြောင့် ကျွန်ုပ်တို့ "generative" ဆိုသော ဝေါဟာရကို အသုံးပြုပါသည်။

### Generative AI မော်ဒယ်အမျိုးအစား

သဘာဝသံများပြည့်သော ဘာသာစကားအမျိုးအစား အသစ်ဖြစ်သော စာသားအမြစ်များကို ဖန်တီးသည့် large language မော်ဒယ်များသာ generative AI ၏ အမျိုးအစားတစ်ခုသာဖြစ်သည်။

Generative image မော်ဒယ်သည် input အနေဖြင့် ရုပ်ပုံကို ထည့်သွင်းပြီး၊ စာသား၊ အခြား ရုပ်ပုံ သို့မဟုတ် ဗီဒီယိုအဖြစ် output ထုတ်နိုင်သည်။ ဥပမာ- output စာသားအနေဖြင့် ဉာဏ်ကောင်းရာ နှင့် အဖြေများကို ရယူနိုင်ပြီး၊ output ရုပ်ပုံအနေဖြင့် ရုပ်ပုံ ပြည့်စုံမှုကို ဖန်တီးနိုင်သည်၊ output ဗီဒီယိုအနေဖြင့် ရုပ်ရှင်ပုံစံ အနုမြူဗေဒကို ဖန်တီးနိုင်သည်။

Generative language မော်ဒယ်သည် input အနေဖြင့် စာသားကို ထည့်သွင်းပြီး၊ စာသား အခြားစာသား၊ ရုပ်ပုံ၊ အသံ၊ သို့မဟုတ် ဆုံးဖြတ်ချက်များအဖြစ် output ထုတ်နိုင်သည်။ ဥပမာ- output စာသားအနေဖြင့် မေးခွန်းနှင့် အဖြေများကို ဖန်တီးနိုင်ပြီး၊ output ရုပ်ပုံအနေဖြင့် ရုပ်ရှင်ကို ဖန်တီးနိုင်သည်။ Generative language မော်ဒယ်သည် သင်ကြား ဒေတာမှ လေ့လာပြီး သင်ယူထားသော ပုံစံများကို လေ့လာကာ သင်ယူသည်။ ဤနမူနာကို ကြည့်ပါ- training data မှ သိရှိထားသော အချက်အလက်များအပေါ်မူတည်ကာ ဤစာပိုဒ်ကို ဘယ်လို ဖြည့်စွက်ရမည်ကို ခန့်မှန်းပါသည်။ "I'm making a sandwich with peanut butter and... Jelly." အလွန်ရိုးရှင်းပါသည်။ ၎င်းအား စာသားအချို့ပေးပြီးသည်နှင့်၊ ၎င်းသည် ဆက်လက်ပေးရမည့်အရာကို ခန့်မှန်းနိုင်သည်။ ထို့ကြောင့် generative language မော်ဒယ်များသည် ပုံစံများကို ခွဲခြားစနစ်များဖြစ်သည်။ ၎င်းတို့သည် သင်ပေးသည့် ဒေတာအပေါ်မူတည်ကာ ပုံစံများကို သင်ယူကြသည်။ ဒီကိစ္စအတွက် Gemini ကို အသုံးပြုကာ ထပ်မံ သရုပ်ပြပါမည်၊ ၎င်းသည် အကြီးအကျယ် အချက်အလက်များပမာဏ တစ်ခုအပေါ် ကျင့်သုံးကာ မေးခွန်းများနှင့် prompt များအတွက် လူ့ရဲ့ တုံ့ပြန်မှုများကဲ့သို့ ပြုလုပ်နိုင်သည်။ ပြန်လည် တုံ့ပြန်မှုသည် မည်လောက်အချက်အလက် အပြည့်အဝ ဖြစ်နိုင်သည်ကို ကြည့်ပါ။

### Generative AI နှင့် Transformer မော်ဒယ်များ

**Generative AI နှင့် Transformers:**

- **Transformers:** ၂၀၁၈ ခုနှစ်တွင် စတင်မိတ်ဆက်ခဲ့ပြီး သဘာဝဘာသာစကား လေ့လာရေးတွင် ပြောင်းလဲမှုကြီးစွာ ဖြစ်ပေါ်စေခဲ့သည်။ Input sequence ကို process လုပ်ပေးသည့် encoder နှင့် output sequence ကို create ပေးသည့် decoder တို့ ပါဝင်သည်။
- **Generative AI ၏ စွမ်းအား:** ဤမော်ဒယ်များ၏ စွမ်းအားမှာ အရာဝတ္ထုများ၏ အဓိပ္ပါယ်နှင့် ပတ်သက်၍ မှန်ကန်သော တုံ့ပြန်မှုများကို ဖန်တီးနိုင်စွမ်း ဖြစ်သည်။

**စိန်ခေါ်မှုများ - Hallucinations:**

- **Hallucinations ဆိုသည်မှာ?** ဤဟာ မော်ဒယ်မှ ဖန်တီးထားသော နားမလည်ဘဲ စကားများ ဖြစ်သည်။
- **အကြောင်းရင်းများ:**
  - လေ့လာရေးဒေတာ မလုံလောက်ခြင်း။
  - ညစ်ပတ်သော ဒေတာများနှင့် လေ့လာရေးလုပ်ခြင်း။
  - အကြောင်းအရာ မလုံလောက်ခြင်း။
  - ကန့်သတ်ချက်များ မရှိခြင်း။

**Hallucinations ၏ အကျိုးသက်ရောက်မှု:**

- **နားလည်မှု:** Output ကို နားလည်ရခက်စေသည်။
- **တိကျမှု:** မှားသော သတင်းအချက်အလက်များ ဖန်တီးရန် အလားအလာကို မြှင့်တင်စေသည်။

### Generative AI နှင့် မော်ဒယ်အမျိုးအစားများ

**Prompts:**
Prompt ဆိုသည်မှာ, လက်တွေ့မှာ Prompt လို့ခေါ်ဆိုသော ချင်းတစ်ခုကို ကြီးမားသော ဘာသာစကားမော်ဒယ် (LLM) ထံသို့ input အဖြစ် ပေးပို့ပြီး ၎င်း မော်ဒယ်၏ output ကို ထိန်းချုပ်ရန် အသုံးပြုနိုင်ပါသည်။ Prompt design ဆိုသည်မှာ, LLM မှ မျှော်မှန်းထားသော output ကို ဖန်တီးနိုင်သော prompt များကို ဖန်တီးခြင်း ဖြစ်သည်။ Generative AI သည်, ရွေးချယ်ထားသော input data များကို ဖော်ပြထားခြင်းဖြင့် ပုံမှန်အနေဖြင့် လေ့လာသည့် အချက်များကို လေ့လာခြင်းဖြစ်သည်။ Browser-based prompt တွင် အသုံးပြုသူများသည် သူတို့၏အကြောင်းအရာများကို ဖန်တီးနိုင်ပါသည်။

**မော်ဒယ်အမျိုးအစားများ:**

1. **Text-to-Text:**

   - သဘာဝဘာသာစကား input ကို လက်ခံပြီး output အနေဖြင့် စာသား output ကို ထုတ်ပေးပါသည်။
   - ၎င်းတို့သည် စာသား parities တစ်ချိန်တည်းတွင် လေ့လာသည့် mappings ကို လေ့လာရန် လေ့လာထားပါသည်။ ဥပမာ၊ ဘာသာပြန်ခြင်း။

2. **Text-to-Image:**

   - စာသားအတိုချုံးများနှင့် ဖော်ပြထားသော image များ၏ ကြီးမားသော အစုလိုက်ဖိုင်များကို လေ့လာရန် လေ့လာထားပါသည်။
   - Diffusion ဆိုသည်မှာ ဤနည်းကို ပြုလုပ်ရန် အသုံးပြုသော နည်းတစ်ခုဖြစ်သည်။

3. **Text-to-Video:**

   - Text input ကို video ကိုယ်စားပြုမှုအနေဖြင့် ဖန်တီးရန် ကြိုးပမ်းပါသည်။
   - Text input သည် စာကြောင်းတစ်ကြောင်းမှ စတင်၍ စာသားအပြည့်အဝရှိရာအထိ ဖြစ်နိုင်ပြီး၊ output ကို input text ကိုယ်စားပြုသော video အဖြစ် ဖြစ်စေသည်။

4. **Text-to-3D:**

   - အသုံးပြုသူ၏ စာသားဖော်ပြချက်ကို အခြေခံပြီး သုံးသပ်ရာတွင် သုံးသပ်ထားသော သုံးလုံး ပုံတစ်ခုကို ဖန်တီးပါသည်။
   - ဂိမ်းများ သို့မဟုတ် တခြားသော 3D ကမ္ဘာများတွင် အသုံးပြုရန် အထောက်အကူပြုပါသည်။

5. **Text-to-Task:**
   - Text input ကို အခြေခံပြီး သတ်မှတ်ထားသော လုပ်ဆောင်ချက် သို့မဟုတ် လုပ်ဆောင်ချက်တစ်ခုကို ပြုလုပ်ရန် လေ့လာထားပါသည်။
   - ဒီအလုပ်များသည် မေးခွန်းဖြေခြင်း၊ ရှာဖွေခြင်း၊ ခန့်မှန်းခြင်း၊ သို့မဟုတ် တစ်ဆက်တစ်စပ် လုပ်ဆောင်ချက်များကို လုပ်ဆောင်ရန် ဖြစ်နိုင်ပါသည်။

**Foundation Models:**
Foundation models များသည် ကြီးမားသော AI မော်ဒယ်များဖြစ်ပြီး ကြီးမားသော ဒေတာအရေအတွက်များအပေါ်တွင် ရှုပ်ထွေးသောစည်းကြပ်မော်ဒယ်များ သို့မဟုတ် Downstream tasks များနှင့် လိုက်ဖက်ရန် သင့်လျော်သောကြောင့် Adapt or Fine-tune ရန် ရည်ရွယ်ထားသော ကြီးမားသော မော်ဒယ်များ ဖြစ်သည်။ Foundation models များသည် နောက်ထပ် အများကြီးသော စက်မှုလုပ်ငန်းများကို ပြောင်းလဲရန် အာရုံစိုက်ပြီး အလွန်ကို ကျွမ်းကျင်ပါသည်။

**ဥပမာများ:**

- **Vertex AI Model Garden:**
  - Foundation models များကို ကောက်နှုတ်ပေးသည်၊ မော်ဒယ်များပါဝင်သည်:
    - **Language models:** PaLM API for chat and text.
    - **Vision models:** Stable diffusion, text descriptions မှ အရည်အသွေးမြင့် images များကို ဖန်တီးရာတွင် ထိရောက်သောအနေဖြင့် ပြသခဲ့သည်။

**အသုံးပြုမှု နမူနာများ:**

- **Sentiment Analysis:**
  - ထုတ်ကုန် သို့မဟုတ် ဝန်ဆောင်မှုများအကြောင်း ကောင်းကောင်းပြောပြရန် Classification models ကို အသုံးပြုပါ။
- **Occupancy Analytics:**
  - Vision tasks အတွက် သတ်မှတ်ထားသော မော်ဒယ်များကို အသုံးပြုပါ။

Foundation models များသည်, စီမံချက်များကို လုပ်ဆောင်ခြင်း သို့မဟုတ် ပြီးစီးရန် အလွန်ကို နယ်ပယ်အသီးသီးမှာ ကျွမ်းကျင်သောမော်ဒယ်များ ဖြစ်ပါသည်။

### Foundation Models နှင့် Generative AI

Foundation models များသည် ကြီးမားသော AI မော်ဒယ်များဖြစ်ပြီး ကြီးမားသော ဒေတာအရေအတွက်များအပေါ်တွင် ရှုပ်ထွေးသောစည်းကြပ်မော်ဒယ်များ သို့မဟုတ် Downstream tasks များနှင့် လိုက်ဖက်ရန် သင့်လျော်သောကြောင့် Adapt or Fine-tune ရန် ရည်ရွယ်ထားသော ကြီးမားသော မော်ဒယ်များ ဖြစ်သည်။ Foundation models များသည် နောက်ထပ် အများကြီးသော စက်မှုလုပ်ငန်းများကို ပြောင်းလဲရန် အာရုံစိုက်ပြီး အလွန်ကို ကျွမ်းကျင်ပါသည်။ ဥပမာ - Sentiment Analysis, Image Captioning, Object Recognition စသဖြင့်။

### Generative AI Applications နှင့် Code Generation

**Code Generation:**
Generative AI သည် သင်၏ အက်ပ်များအတွက် ကုဒ်အားလုံးကို ကူညီနိုင်ပါသလား? အမှန်ပင် အားလုံးပင်လုပ်နိုင်ပါသည်။ ဒီမှာ Generative AI applications များကို မြင်ရမည် ဖြစ်သည်။ ဤနေရာတွင် code block တစ်ခုကို ကြည့်ကြပါစို့။ ဤနေရာတွင်, Python မှ JSON သို့ ပြောင်းလဲခြင်းအတွက် Code file conversion problem ကို input ထည့်လိုက်ပါသည်။ "I have a Pandas Dataframe with two columns - one with a file name and one with the hour in which it is generated: I am trying to convert it into a JSON file in the format shown on screen:" ဟု Gemini ကို prompt box မှာ ထည့်လိုက်ပါသည်။ Gemini သည် သင်ပြုလုပ်ရန်လိုအပ်သော အဆင့်များကို ပြန်လည်ပေးပါသည်။ နောက်ဆုံး output သည် JSON format အနေနှင့် ဖြစ်လာသည်။ အလွန်အမင်းကြီးကို သိသာပါသည်။

ထို့အပြင်, Generative AI များသည် code generation အတွက် ရှုပ်ထွေးသော function များကို ရှင်းလင်းသော စာသားဖြင့် ရေးသားခြင်း၊ SQL queries ကို ဆောင်ရွက်ရန်, အခြား Programming Language တစ်ခုမှ တစ်ခုသို့ ဘာသာပြန်ခြင်း၊ Documentation နှင့် Tutorials များကို ဖန်တီးခြင်း စသဖြင့် ကူညီပေးနိုင်ပါသည်။

### Vertex AI Studio

**Vertex AI Studio:**
Google Cloud မှ Generative AI ကို ပိုမိုကောင်းမွန်အောင် အသုံးချနိုင်ရန် သုံးနည်း သုံးပုံများကို ဖော်ပြပါမည်။

1. **Vertex AI Studio:** Generative AI မော်ဒယ်များကို ဖန်တီးရန်နှင့် Deploy ရန်အတွက် tools များနှင့် resources များကို ပံ့ပိုးပေးပြီး Developer များအတွက် အလွန်အဆင်ပြေသည်။
2. **Vertex AI:** Coding အတွေ့အကြုံမရှိသူများအတွက် အထူးသင့်လျော်ပြီး, Generative AI Search နှင့် Conversation များကို ဖန်တီးနိုင်သည်။
3. **PaLM API:** Google's large language models နှင့် Gen AI tools များကို Test နှင့် Experiment လုပ်ရန် အတွက် PaLM API ကို အသုံးပြုနိုင်သည်။

Google Cloud ၏ Vertex AI Studio ကို အသုံးပြု၍ Generative AI မော်ဒယ်များကို အလွယ်တကူ စတင်ရန် အထောက်အကူပြုသည်။ သင်၏ အက်ပ်များတွင် လွယ်ကူစွာ အသုံးပြုနိုင်ပါသည်။

### Vertex AI Studio နှင့် Vertex AI

**Vertex AI Studio:**
Vertex AI Studio သည် Google Cloud တွင် သင့်အက်ပ်လီကေးရှင်းများအတွက် အသုံးချနိုင်သော generative AI မော်ဒယ်များကို ရှာဖွေရန်နှင့် စိတ်ကြိုက်ပြုပြင်ရန် အလွန်မြန်ဆန်စွာ ပြုလုပ်နိုင်စေသည်။ Vertex AI Studio သည် Developer များအတွက် generative AI မော်ဒယ်များကို ဖန်တီးရန်နှင့် Deploy ပြုလုပ်ရန် လွယ်ကူစေသော tools နှင့် resources များစွာကို ပံ့ပိုးပေးပါသည်။ ဥပမာအားဖြင့်, ကြိုတင်လေ့လာထားသော မော်ဒယ်များ Library, မော်ဒယ် Fine-tuning Tool, မော်ဒယ်ကို production သို့ deploy Tool, Developer များအတွက် Community forum များ ပါဝင်သည်။

**Vertex AI:**
Vertex AI သည် coding အတွေ့အကြုံ မရှိသူများအတွက် အထူးသင့်လျော်ပြီး, Vertex AI Search နှင့် Conversation (ဟောင်းက Gen AI App Builder) ဖြင့် Customers နှင့် Employees အတွက် Generative AI Search နှင့် Conversations များကို Build ပြုလုပ်နိုင်ပါသည်။ Coding အနည်းငယ် သို့မဟုတ် အလုံးစုံ မရှိပါက Build ပြုလုပ်နိုင်ပြီး, machine learning အတွေ့အကြုံ မလိုအပ်ပါ။

**Google Cloud တွင် အခြား Generative AI Services များ:**

1. **Library of Pre-trained Models:** ကြိုတင်လေ့လာထားသော မော်ဒယ်များ Library
2. **Tool for Fine-tuning Models:** မော်ဒယ် Fine-tuning Tool
3. **Tool for Deploying Models to Production:** မော်ဒယ်ကို production သို့ deploy Tool
4. **Community Forum for Developers:** Developer များအတွက် Community forum

Google Cloud ၏ Vertex AI Studio ကို အသုံးပြု၍ Generative AI မော်ဒယ်များကို အလွယ်တကူ စတင်ရန် အထောက်အကူပြုသည်။ သင်၏ အက်ပ်များတွင် လွယ်ကူစွာ အသုံးပြုနိုင်ပါသည်။

### Vertex AI နှင့် PaLM API

**Vertex AI:**
Vertex AI သည် သင်၏ chatbots, digital assistants, custom search engines, knowledge bases, training applications, နှင့် အခြားစီမံချက်များကို ဖန်တီးရန် ကူညီပေးပါသည်။

**PaLM API:**
PaLM API သည် Google's large language models နှင့် Generative AI tools များကို စမ်းသပ်ရန်နှင့် စမ်းသပ်မှုများပြုလုပ်ရန် ပံ့ပိုးပေးသည်။ Prototype လုပ်ရာတွင် မြန်ဆန်ပြီး လွယ်ကူစေရန် PaLM API ကို Maker Suite နှင့် ပေါင်းစပ်ပြီး အသုံးပြုနိုင်ပါသည်။ ၎င်း၏ graphical user interface ကို အသုံးပြု၍ API ကို ရရှိနိုင်ပါသည်။

### Tools များနှင့် Gemini AI Model

**Tools များ:**
Tool Suite တွင် မော်ဒယ် training tool, မော်ဒယ် deployment tool, နှင့် မော်ဒယ် monitoring tool အပါအဝင် tools များစွာ ပါဝင်သည်။

- **Model Training Tool:** သည် tool မှ သတ်မှတ်ထားသော algorithms များကို အသုံးပြု၍ အသုံးပြုသူ၏ ဒေတာအပေါ်တွင် ML မော်ဒယ်များကို လေ့ကျင့်ပေးပါသည်။
- **Model Deployment Tool:** သည် tool မှ မော်ဒယ်များကို production သို့ အမျိုးမျိုးသော deployment ရွေးချယ်မှုများဖြင့် deploy ရန် ကူညီပေးပါသည်။
- **Model Monitoring Tool:** သည် tool မှ မော်ဒယ်များ၏ performance ကို production တွင် monitor လုပ်ရန် dashboard နှင့် အမျိုးမျိုးသော metrics များဖြင့် ကူညီပေးပါသည်။

**Gemini AI Model:**
Gemini သည် multimodal AI model တစ်ခုဖြစ်ပြီး, traditional language models များကဲ့သို့ စာသားသာမက, ပုံများကိုခွဲခြမ်းစိတ်ဖြာပြီး, audio ၏ နူးညံ့မှုများကို နားလည်ရန်နှင့် programming code ကိုပင် သဘောပေါက်နိုင်စွမ်း ရှိသည်။ Gemini သည် AI အတွက် မပြုလုပ်နိုင်သော ရှုပ်ထွေးသော အလုပ်များကို ပြုလုပ်နိုင်စေသည်။ Gemini ၏ advanced architecture ကြောင့်, ၎င်းသည် များစွာသော applications များအတွက် အသုံးပြုရန် အလွန်ကို သင့်လျော်ပြီး ကျယ်ပြန့်သော scalability ရှိသည်။ Model Garden ကို အမြဲတမ်း အသစ်သော မော်ဒယ်များဖြင့် update လုပ်ပေးနေပါသည်။

Generative AI အကြောင်းကို အခြေခံအချက်များကို လေ့လာပြီးကြပါပြီ။ အခြားသော AI အသုံးချမှုနည်းလမ်းများကို သိရှိရန် များစွာသော အခြားအတောအတွင်း Video များကို ကြည့်ပါ။
