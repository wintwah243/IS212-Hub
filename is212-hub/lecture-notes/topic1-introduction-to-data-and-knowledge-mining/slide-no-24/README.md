# Major Issues in Data Mining (slide24 - 9.6.2026)

While data mining is powerful, it is not always easy to implement. There are five main "problem areas" or categories of issues that need to be managed:

---

## 1. Mining Methodology

**The Problem:** There isn't just one way to mine data.

**The Issue:** Researchers must develop different methods to find different kinds of knowledge (like associations, clusters, or classifications). This also includes the challenge of mining data at different levels of detail and handling messy data that has "noise" or missing information.

ဒေတာတစ်ခုတည်းကနေ ရှာဖွေချင်တဲ့ ရလဒ်ချင်း မတူညီနိုင်ပါဘူး။ အချို့က ဆက်စပ်မှု (Associations)၊ အချို့က အုပ်စုတူစုခြင်း (Clusters)၊ အချို့က အုပ်စုခွဲခြားခြင်း (Classifications) တွေကို လိုချင်ကြတာဖြစ်လို့ သုတေသီတွေအနေနဲ့ တစ်မျိုးစီအတွက် သီးသန့် အလုပ်လုပ်မယ့် နည်းလမ်း (Methodology) မျိုးစုံကို တီထွင်ဖန်တီးရပါတယ်။

---

## 2. User Interaction

**The Problem:** Data mining shouldn't just be a "black box" where you press a button and get an answer.

**The Issue:** Systems need to be interactive so users can guide the process based on their own interests (subjective measures). It also involves visualization, making sure the results are shown in a way that a human can actually understand and use.

အသုံးပြုသူနဲ့ အပြန်အလှန် တုံ့ပြန်မှု (Interactive) ရှိနေရမယ်။ ဒါမှသာ အသုံးပြုသူက မိမိရဲ့ ကိုယ်ပိုင်စိတ်ဝင်စားမှု လိုအပ်ချက်တွေ (Subjective measures / User beliefs) ပေါ်မူတည်ပြီး Algorithm က ဘယ်ဒေတာကို ပိုဦးစားပေးရမလဲဆိုတာကို ကြားထဲကနေ လမ်းညွှန်ပေး (Guide လုပ်ပေး) နိုင်မှာ ဖြစ်တယ်။

---

## 3. Efficiency and Scalability

**The Problem:** Data is getting bigger every day.

**The Issue:** Algorithms must be efficient (fast enough to be useful) and scalable (able to handle a database that grows from 1,000 rows to 1,000,000,000 rows without breaking). This often requires using high-performance computing or parallel processing.

အသုံးပြုလိုက်တဲ့ Algorithm တွေဟာ အချိန်တိုအတွင်းမှာ တွက်ချက်မှုပြီးစီးအောင် အလုပ်လုပ်နိုင်စွမ်း (Fast enough to be useful) ရှိရပါမယ်။ အဖြေတစ်ခုထွက်ဖို့ ရက်ပေါင်းများစွာ စောင့်ရမယ်ဆိုရင် အဲဒီစနစ်က Real-world မှာ အသုံးမဝင်ပါဘူး။
ဒေတာပမာဏ အဆမတန် တိုးပွားလာတဲ့အခါမှာ စနစ်က ပြိုလဲမသွားဘဲ ကောင်းမွန်စွာ ဆက်လက်ကိုင်တွယ်နိုင်စွမ်း ရှိခြင်း ဖြစ်တယ်။ ဥပမာ - ဒေတာ Row ပေါင်း ၁,၀၀၀ ရှိတဲ့ အခြေအနေကနေ Row ပေါင်း ၁,၀၀၀,၀၀၀,၀၀၀ (၁ ဘီလီယံ) အထိ ကြီးထွားလာရင်တောင် စနစ်က မပိတ်သွားဘဲ တည်ငြိမ်စွာ အလုပ်လုပ်နိုင်ရပါမယ်။

---

## 4. Diversity of Data Types

**The Problem:** Data comes in many "flavours."

**The Issue:** As we saw in earlier slides, data isn't just simple numbers in a table anymore. A major issue is making mining tools work across diverse data types, such as social media posts, satellite maps, streaming sensor data, and old "legacy" computer files.

Mining tools တွေဟာ သမားရိုးကျ ဇယားကွက်တွေထဲက ကိန်းဂဏန်းတွေ၊ စာသားတွေကိုပဲ ကိုင်တွယ်ရုံနဲ့ မလုံလောက်တော့ပါဘူး။(လူမှုကွန်ရက်ပေါ်မှ ပို့စ်များ၊ ဂြိုဟ်တုမြေပုံများ၊ အဆက်မပြတ် စီးဆင်းနေသော ဆင်ဆာဒေတာများနှင့် စနစ်ဟောင်းသုံး ကွန်ပျူတာဖိုင်များ ကဲ့သို့သော) စုံလင်ကွဲပြားလှသည့် ဒေတာအမျိုးအစားအားလုံးတွင် ကောင်းမွန်စွာ အလုပ်လုပ်နိုင်အောင် ဖန်တီးပေးရန် ဖြစ်တယ်။

---

## 5. Data Mining and Society

**The Problem:** Using people's data has consequences.

**The Issue:** This category covers the impact of data mining on the real world. It includes:

**Privacy:** How do we mine data without revealing personal secrets?

အဖွဲ့အစည်းတွေ၊ ကုမ္ပဏီတွေကနေ ဒေတာတွေကို miningလုပ်တဲ့အခါ လူသားတစ်ဦးချင်းစီရဲ့ ကိုယ်ရေးကိုယ်တာ လျှို့ဝှက်ချက်တွေ၊ အချက်အလက်အစစ်အမှန်တွေ လွတ်ထွက်မသွားအောင် (Revealing personal secrets မဖြစ်အောင်) ဘယ်လို ကာကွယ်မလဲဆိုတာ ဖြစ်တယ်။

**Ethics:** Is it fair to use these patterns to make decisions about people?

ဒေတာတွေထဲက ထွက်လာတဲ့ Patterns တွေကို သုံးပြီး လူသားတွေအပေါ် ဆုံးဖြတ်ချက်ချတဲ့နေရာမှာ (ဥပမာ - အလုပ်ခန့်ခြင်း၊ ဘဏ်ချေးငွေ ပေးခြင်း သို့မဟုတ် ပြစ်ဒဏ်သတ်မှတ်ခြင်း) မည်မျှအထိ တရားမျှတမှု ရှိပါသလဲ (Is it fair? ဆိုတာကို စစ်ဆေးခြင်း ဖြစ်တယ်)။

**Security:** How do we keep the mined "knowledge" safe from hackers?

စနစ်တွေကနေ တူးဖော်ရရှိထားတဲ့ အဖိုးတန် အသိပညာ (Mined knowledge) တွေနဲ့ databaseတွေကို Hackersတွေ လက်ထဲ မကျရောက်အောင်၊ အလွဲသုံးစားလုပ်ခြင်း မခံရအောင် ဘယ်လို စနစ်တကျ လုံခြုံအောင် သိမ်းဆည်းမလဲဆိုတဲ့ အချက် ဖြစ်တယ်။

---

## Summary

Think of these issues like the obstacles in a race. To be successful, a data mining system can't just be smart (Methodology); it also has to be friendly to the user (Interaction), fast and strong (Efficiency/Scalability), flexible enough to handle different terrains (Diversity), and it must follow the rules of the road to keep everyone safe (Society).

---

# Key notes from Tchel Hsu Myat Mo

