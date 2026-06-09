# Which Technologies are used? (slide21, 22, 23 - 9.6.2026)

Data mining is an "interdisciplinary" field, meaning it doesn't just use one type of technology. Instead, it adopts techniques from many different domains to solve complex problems.

Data Mining ဆိုတာ သီးသန့်ရပ်တည်နေတဲ့ နည်းပညာတစ်ခုတည်း မဟုတ်ဘဲ၊ ရှုပ်ထွေးလှတဲ့ ဒေတာပြဿနာတွေကို ဖြေရှင်းဖို့အတွက် အခြားသော နည်းပညာနယ်ပယ်ပေါင်းစုံက ချဉ်းကပ်မှုတွေကို စုစည်းအသုံးချထားတာ ဖြစ်တယ်။

---

## 1. The Core Technologies (The Big Picture)

Think of data mining as a hub where these different fields meet:

**Statistics:** Using mathematical functions and probability to describe how data behaves.

ဒေတာတွေရဲ့ သဘာဝနဲ့ ပြန့်နှံ့ပုံတွေကို သင်္ချာနည်းလမ်းများ (Mathematical functions) နှင့် Probability များအသုံးပြုကာ တိကျစွာ ပုံဖော်တွက်ချက်ရန်ဖြစ်တယ်။

**Machine Learning:** Teaching computers to recognize patterns and make decisions automatically.

ကွန်ပျူတာ/AI ကို ဒေတာတွေထဲက Patterns တွေကို အလိုအလျောက် မှတ်မိစေရန်နှင့် လူကိုယ်တိုင် Rules တွေ လိုက်ရေးပေးစရာမလိုဘဲ သူ့အလိုလို ဆုံးဖြတ်ချက်များ (Decisions) ချမှတ်နိုင်စေရန် သင်ကြားပေးရန်ဖြစ်တယ်။

**Database Systems & Data Warehousing:** Providing the "storage rooms" and tools (like OLAP) to organize and analyze massive amounts of data.

အဆမတန် များပြားလှတဲ့ ဒေတာအမြောက်အမြားကို စနစ်တကျ သိမ်းဆည်းမယ့် "သိုလှောင်ခန်း (Storage rooms)" များနှင့် ခွဲမ်းစိတ်ဖြာမည့် ကိရိယာများ (ဥပမာ - OLAP Cube) ပံ့ပိုးပေးရန်ဖြစ်တယ်။

**Information Retrieval (IR):** The science of searching through documents to find specific information.

(စာရွက်စာတမ်းများ၊ အီးမေးလ်များနှင့် ဝက်ဘ်စာမျက်နှာများကဲ့သို့သော) Unstructured Documents တွေထဲကနေ မိမိအလိုရှိတဲ့ သီးသန့် အချက်အလက်တွေကို ရှာဖွေဖော်ထုတ်ရန်ဖြစ်တယ်။

**Visualization:** Turning complex data into charts and graphs so humans can understand it.

ရှုပ်ထွေးလွန်းတဲ့ နည်းပညာဆိုင်ရာ ဒေတာရလဒ်တွေကို လူသားတွေ မျက်စိနဲ့ကြည့်ရုံနဲ့ ချက်ချင်း နားလည်သဘောပေါက်နိုင်မယ့် Charts တွေ၊ Graphs တွေအဖြစ် ပြောင်းလဲပေးရန်ဖြစ်တယ်။

**High-Performance Computing:** Using powerful computers to process data very quickly.

ဒေတာပမာဏ ဘယ်လောက်ပဲ များများ စက္ကန့်ပိုင်းအတွင်း အလွန်လျင်မြန်စွာ Process လုပ်နိုင်ဖို့အတွက် အဆင့်မြင့် စွမ်းအားမြင့် ကွန်ပျူတာစနစ်များကို အသုံးပြုရန်ဖြစ်တယ်။

---

## 2. Focus on Machine Learning (How Computers Learn)

This is one of the most important parts of data mining. There are several ways a computer can "learn" from data:

**Supervised Learning:** The computer learns using "labeled examples" (where we already know the answer). For example, teaching it to recognize spam emails by showing it thousands of emails already marked as "spam".

ဒေတာတွေမှာ "အဖြေတွဲပါဝင်ပြီးသား (Labeled Examples)" တွေကို ပြသပြီး ကွန်ပျူတာကို သင်ကြားပေးတာ ဖြစ်တယ်။

ဥပမာ: အီးမေးလ် ထောင်ပေါင်းများစွာကို "Spam ဟုတ်တယ်/မဟုတ်ဘူး" ဆိုပြီး အဖြေတပ်ထားတဲ့ ဒေတာတွေကို မော်ဒယ်ကို ပေးဖတ်ပြီး Spam ခွဲခြားတတ်အောင် လေ့ကျင့်ပေးခြင်းမျိုး ဖြစ်တယ်။

**Unsupervised Learning:** The computer looks at data without any labels and tries to find its own groups. This is often used for Clustering.

ဒေတာတွေမှာ ဘာအဖြေ (Labels) မျှ ကြိုတင်သတ်မှတ်ပေးမထားဘဲ၊ ကွန်ပျူတာက ၎င်းရဲ့ Algorithm အပေါ် အခြေခံပြီး ဒေတာတွေအချင်းချင်း ဆင်တူရာအလိုက် သူ့အလိုလို အုပ်စုခွဲခြားခြင်း လုပ်ဆောင်တဲ့ နည်းလမ်း ဖြစ်ပါတယ်။

**Semi-supervised Learning:** A mix of both labeled and unlabeled data is used to help the computer learn better.

အဖြေပါတဲ့ Labeled Data ပမာဏ နည်းနည်းနဲ့ အဖြေမပါတဲ့ Unlabeled Data ပမာဏ အများကြီးကို ပေါင်းစပ် (Mix) ပြီး မော်ဒယ်ကို ပိုမိုစွမ်းဆောင်ရည်ကောင်းမွန်အောင် သင်ယူခိုင်းခြင်း ဖြစ်တယ်။

**Active Learning:** The system lets a human user play an active role in the learning process to guide the computer.

Modelက သူဝေခွဲမရတဲ့ ဒေတာအချက်အလက်တွေ ကြုံလာရတဲ့အခါ၊  Human expert ကို မေးမြန်းအကူအညီတောင်းပြီး လမ်းညွှန်မှုရယူကာ ဆက်လက်သင်ယူတဲ့ စနစ် ဖြစ်တယ်။

**Transfer Learning:** Taking a model that was trained for one task and adapting it to a new, similar task. This is very useful when you don't have much data for the new task.

လုပ်ငန်းတာဝန်တစ်ခုအတွက် သေချာလေ့ကျင့်သင်ယူထားပြီးသားPre-trained Model ရဲ့ အသိပညာတွေကို ယူပြီး၊ ၎င်းနဲ့ ဆင်တူတဲ့ လုပ်ငန်းတာဝန်အသစ်တစ်ခုမှာ ပြန်လည်အသုံးပြု/အလိုက်သင့်ပြင်ဆင် (Adapt) တဲ့ နည်းလမ်း ဖြစ်တယ်။

---

## 3. Focus on Data Warehousing & IR

**Data Warehouses:** These systems provide multidimensional data analysis, allowing you to look at your data from many different angles (this is called OLAP).

လုပ်ငန်းစုကြီးတစ်ခုလုံးမှာရှိတဲ့ ဒေတာအမြောက်အမြားကို စုစည်းသိမ်းဆည်းပြီး Multidimensional data analysis (ဘက်စုံရှုထောင့်မှ ဒေတာဆန်းစစ်ခြင်း) ကို လုပ်ဆောင်ပေးတယ်။

**Information Retrieval (IR):** This technology focuses on searching for information within documents. It often uses probabilistic models to figure out which words or documents are most relevant to what you are looking for.

(အီးမေးလ်များ၊ ဝက်ဘ်စာမျက်နှာများနှင့် စာရွက်စာတမ်းများကဲ့သို့သော) Textual Documents တွေထဲကနေ မိမိအလိုရှိတဲ့ သီးသန့် သတင်းအချက်အလက်တွေကို ရှာဖွေဖော်ထုတ်တဲ့ နည်းပညာ ဖြစ်တယ်။
ဉပမာ အသုံးပြုသူ ရှာဖွေလိုက်တဲ့ စကားလုံး (Query) နဲ့ မည်သည့် စာရွက်စာတမ်းက အကိုက်ညီဆုံး၊ အဆက်စပ်ဆုံး ဖြစ်မလဲ (Most relevant) ဆိုတာကို တွက်ချက်ဖို့အတွက် Probabilistic modelsကို အဓိက အသုံးပြုတယ်။

---

## Summary

Data mining is like a multipurpose toolkit. It takes the math from statistics, the brainpower from machine learning, the storage from databases, and the search skills from information retrieval to turn "raw data" into "useful knowledge".

---

# Key notes from Tchel Hsu Myat Mo

