# What Makes a Pattern Interesting? (slide18 and 19 - 9.6.2026)

As we discussed in the previous slide, computers can find thousands of patterns, but not all are useful. This slide gives us a "checklist" to identify the ones that truly matter.

---

## 1. The Four Essential Qualities

For a pattern to be considered "interesting" and qualify as knowledge, it must be:

**Easily Understood:** It should be clear enough for humans to grasp the meaning behind the data.

ထွက်လာတဲ့ ရလဒ် ဒါမှမဟုတ် Pattern ဟာ သင်္ချာညီမျှခြင်းတွေ၊ ရှုပ်ထွေးလွန်းတဲ့ ကုဒ်တွေချည်းပဲ ဖြစ်မနေဘဲ၊ လူသားတစ်ယောက်အနေနဲ့ ဒီဒေတာရဲ့ နောက်ကွယ်က အဓိပ္ပာယ်ကို ရှင်းရှင်းလင်းလင်း နားလည်နိုင်စွမ်း ရှိရမယ်။

**Valid:** It must work on new or test data with a degree of certainty. This proves the pattern is a real rule and not just a random fluke in the original data.

ဒီ Pattern ဟာ လက်ရှိ Training dataပေါ်မှာတင် မှန်နေရုံနဲ့ မလုံလောက်ဘူး။ ဒေတာအသစ်တွေ ဒါမှမဟုတ် စမ်းသပ်ဒေတာ (New or Test data) တွေအပေါ်မှာပါ အတိုင်းအတာတစ်ခုအထိ တိကျမှန်ကန်စွာ အလုပ်လုပ်နိုင်ရမယ်။

**Potentially Useful:** There must be a practical way to use this information to solve a problem or improve a process.

ရှာတွေ့ထားတဲ့ အချက်အလက်ကို သုံးပြီး လက်တွေ့ဘဝက ပြဿနာတစ်ခုခုကို ဖြေရှင်းနိုင်တာမျိုး (သို့မဟုတ်) လုပ်ငန်းခွင် လုပ်ဆောင်ချက်တွေကို ပိုမိုကောင်းမွန်အောင် အဆင့်မြှင့်တင်နိုင်မယ့် လက်တွေ့ကျကျ အသုံးချနိုင်မည့် နည်းလမ်းရှိရမယ်။

**Novel:** It should be new. If a pattern just tells you something you already knew, it isn't providing any new knowledge.

လုံးဝအသစ်အဆန်း ဖြစ်ရမယ်။

**Hypothesis Validation:** A pattern is also considered interesting if it confirms a theory or "hunch" that the user was specifically trying to prove.

အထက်ပါ ၄ ချက်အပြင်၊ အသုံးပြုသူ/ပညာရှင်က ကြိုတင်တွေးတောထားတဲ့ သီအိုရီ သို့မဟုတ် စိတ်ကူးထင်မြင်ချက် (Hunch) တစ်ခုကို ဟုတ်မဟုတ် ကွက်တိ အတည်ပြု သက်သေပြပေးနိုင်တဲ့ Pattern မျိုးဆိုရင်လည်း အာ့patternကို စိတ်ဝင်စားဖွယ်ကောင်းသော Pattern ဟု သတ်မှတ်တယ်။

---

## 2. Objective vs. Subjective Measures

We use two different types of "yardsticks" to measure how interesting a pattern is:

**A. Objective Measures (The Math)** These are based on statistics and probability. For example, when looking at "Association Rules" (like "People who buy coffee also buy sugar"), we look at:

လူတစ်ဦးတစ်ယောက်ရဲ့ အမြင်ပေါ်မှာ မူတည်ခြင်းမရှိဘဲ၊ Statistics နဲ့ Probability သင်္ချာနည်းလမ်းတွေအပေါ်မှာပဲ တိုက်ရိုက်အခြေခံပြီး တွက်ချက်တာ ဖြစ်တယ်။

**Support:** The percentage of transactions in the database that actually follow this rule.
Databaseတစ်ခုလုံးမှာရှိတဲ့ အရောင်းအဝယ် (Transactions) စုစုပေါင်းထဲကမှ ဒီ Rules အတိုင်း အမှန်တကယ် ဖြစ်ပျက်နေတဲ့ အရေအတွက် ရာခိုင်နှုန်း ဖြစ်တယ်။ (ဥပမာ - ဆိုင်သို့လာသမျှ လူ ၁၀၀ ထဲတွင် ဝင်ငွေမြင့်ပြီး ကော်ဖီဝယ်သူ ၂၀ ရှိလျှင် Support က 20% ဖြစ်တယ်)။

**Confidence:** The "degree of certainty" or how often the rule is actually true when the first condition is met.

ပထမအခြေအနေ ဖြစ်ပွားပြီးတဲ့နောက် (ဒီဥပမာမှာ ကော်ဖီဝယ်ပြီးနောက်)၊ ဒုတိယအခြေအနေ (သကြားပါတွဲဝယ်ဖို့) ဘယ်လောက်အထိ ရာခိုင်နှုန်း သေချာမှုရှိလဲ (Degree of certainty) ဆိုတာကို တိုင်းတာတာ ဖြစ်တယ်။

**B. Subjective Measures (The Human Element)** Sometimes, even if the math is strong, a pattern isn't useful to a specific person.

သင်္ချာနည်းအရ Rule ကြီးက ဘယ်လောက်ပဲ အားကောင်းနေပါစေ (Strong Math ဖြစ်နေပါစေ)၊ အသုံးပြုမယ့် လူသား (User) ရဲ့ လုပ်ငန်းခွင် လိုအပ်ချက် ဒါမှမဟုတ် သူ့ရဲ့ ရည်ရွယ်ချက်နဲ့ မကိုက်ညီရင် အသုံးမဝင်ဘူးလို့ သတ်မှတ်တာ ဖြစ်တယ်။

**User Beliefs:** These measures are based on what the user finds important or what they believe about their data.
Math identifies the strength of a pattern, but human judgment identifies its relevance.

အသုံးပြုသူက သူ့dataအပေါ်မှာ ဘာကို အရေးကြီးတယ်လို့ သတ်မှတ်ထားလဲ၊ သူ ဘာကို သိချင်နေလဲ (Relevance) ဆိုတဲ့ လူသားတို့၏ ဆုံးဖြတ်ချက် (Human judgment) ပေါ်မှာ အခြေခံတယ်။

---

## Summary

Think of this slide as the quality control step. To turn "data patterns" into "knowledge," we use math (Objective) to make sure the pattern is strong and reliable, and we use human common sense (Subjective) to make sure it is actually helpful and new.

---

# Key notes from Tchel Hsu Myat Mo

