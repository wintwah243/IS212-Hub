# Evaluation of Knowledge (slide17 - 9.6.2026)

This slide addresses a major challenge in data mining: just because a computer finds a "pattern," it doesn't mean that pattern is actually useful or important.

---

## 1. The Problem: Too Much Information

**Massive Volume:** Computers can mine a tremendous amount of "patterns" from a single database.

ကွန်ပျူတာတွေရဲ့ တွက်ချက်နိုင်စွမ်းက မြန်ဆန်လွန်းတဲ့အတွက် Database တစ်ခုတည်းကနေတင် ထောင်နဲ့ချီတဲ့ ဒေတာပုံစံများ (Patterns) ကို တူးဖော်ထုတ်ပေးနိုင်တာက problemတစ်ခုဖြစ်နေပါတယ်။

**The Filter Problem:** If a system gives you 10,000 patterns, you can’t look at all of them. We need a way to figure out which ones are actually "interesting" and represent real knowledge.

အကယ်၍ စနစ် (System) တစ်ခုကနေ Patterns ပေါင်း ၁၀,၀၀၀ ကျော် ထုတ်ပေးလိုက်ရင် လူသားတစ်ယောက်အနေနဲ့ ၎င်းတို့အားလုံးကို လိုက်ဖတ်ပြီး ဆန်းစစ်ဖို့ မဖြစ်နိုင်ပါဘူး။

ဒါကြောင့် ထွက်လာတဲ့ ပုံစံအမြောက်အမြားထဲကမှ မည်သည့်အရာက တကယ်ပဲ စိတ်ဝင်စားစရာကောင်းပြီး လက်တွေ့အသုံးချလို့ရတဲ့ တကယ့်အသိပညာ (Real Knowledge) ဖြစ်လဲဆိုတာကို ခွဲခြားသတ်မှတ်ပေးနိုင်မယ့် Interest Measures (စိတ်ဝင်စားမှု တိုင်းတာချက်များ) လိုအပ်လာတာ ဖြစ်တယ်။

---

## 2. Why Some Patterns Aren't Useful

Not every discovery is a gold mine. Some patterns are ignored because:

**Limited Scope:** They might only work in a very specific dimension space, such as one specific city or one specific hour of the day, and aren't true anywhere else.

ထွက်လာတဲ့ ပုံစံက အလွန်သေးငယ်ပြီး သီးသန့်ဖြစ်လွန်းတဲ့ ရှုထောင့် (Dimension space) တစ်ခုတည်းမှာပဲ မှန်ကန်နေတာမျိုး ဖြစ်တယ်။
ဥပမာ: ဒေတာပုံစံတစ်ခုက သတ်မှတ်ထားတဲ့ မြို့တစ်မြို့တည်း သို့မဟုတ် နေ့ခင်းဘက် သတ်မှတ်ထားတဲ့ တစ်နာရီအတွင်း မှာပဲ မှန်နေပြီး၊ တခြားနေရာ သို့မဟုတ် တခြားအချိန်တွေမှာ လုံးဝအသုံးမဝင်တော့တာမျိုး ဖြစ်တယ်။

**Transient Data:** The pattern might be "temporary." It happened once by chance and will likely never happen again.

ရရှိတဲ့ patternက ရေရှည်မမှန်ဘဲ ယာယီ/ခဏတာ (Temporary) သာ ဖြစ်ပျက်တာမျိုး။ တိုက်ဆိုင်မှုတစ်ခုအနေနဲ့ တစ်ကြိမ်တစ်ခါပဲ ဖြစ်ပျက်ခဲ့ပြီး နောင်အနာဂတ်မှာ ဘယ်တော့မှ ထပ်ဖြစ်လာဖို့ မရှိတဲ့ အချက်အလက်မျိုး ဖြစ်တယ်။

**Not Representative:** The pattern doesn't happen often enough to be worth a business's or scientist's attention.

၎င်းပုံစံက ဒေတာတစ်ခုလုံးထဲမှာ ဖြစ်ပွားတဲ့အကြိမ်ရေ အလွန်နည်းပါးလွန်းတာကြောင့် စီးပွားရေးလုပ်ငန်းရှင်တွေ ဒါမှမဟုတ် သိပ္ပံပညာရှင်တွေအနေနဲ့ အချိန်ပေးပြီး အာရုံစိုက်လေ့လာဖို့ တန်ဖိုးမရှိတာမျိုး ဖြစ်တယ်။

---

## 3. How We Evaluate Knowledge (The Checklist)

To decide if a pattern is worth keeping, we evaluate it based on several factors:

**Accuracy:** How often is the pattern correct?

ဒီ Pattern က ဒေတာအသစ်တွေအပေါ်မှာ ဘယ်လောက်အကြိမ်ရေအထိ မှန်ကန်အောင် ခန့်မှန်းပေးနိုင်သလဲဆိုတာ ဖြစ်တယ်။(It is also called classification accuracy or precision.)

**Coverage:** How much of the total data does this pattern actually explain?

ဒီစနစ်က ရှာဖွေတွေ့ရှိတဲ့ ပုံစံဟာ databaseတစ်ခုလုံးမှာရှိတဲ့ အချက်အလက် စုစုပေါင်းရဲ့ ပမာဏ ဘယ်လောက်အထိကို လွှမ်းခြုံရှင်းပြနိုင်သလဲ ဆိုတာ ဖြစ်တယ်။(It is also called support or recall.)

**Timeliness:** Is the information still relevant, or is it based on old, outdated habits?

ရရှိတဲ့ အချက်အလက်တွေက လက်ရှိအချိန် (Present time) မှာကော အသုံးဝင်နေသေးရဲ့လား၊ ဒါမှမဟုတ် ဟောင်းနွမ်း ခေတ်နောက်ကျသွားတဲ့ အလေ့အထဟောင်း (Outdated habits) တွေအပေါ် အခြေခံထားတာလားဆိုတာ စစ်ဆေးခြင်း ဖြစ်တယ်။

**Novelty vs. Typicality:** Is this a brand new discovery (novelty), or is it just something we already knew was "typical"?

Novelty (ဆန်းသစ်မှု): လူတွေ တစ်ခါမှ မသိသေးတဲ့ လုံးဝအသစ်စက်စက် အသုံးဝင်တဲ့ ရှာဖွေတွေ့ရှိမှုမျိုး ဖြစ်လား။

Typicality (ပုံမှန်ဖြစ်မှု): လူတိုင်း သိပြီးသား ဖြစ်နေတဲ့ ရိုးရိုးပုံမှန် အချက်အလက်ကြီးပဲ ဖြစ်နေမလား (ဥပမာ - "မိုးရွာရင် လမ်းရေစိုတတ်သည်" ဆိုတဲ့ ပုံစံမျိုးက မှန်ပေမဲ့ လူတိုင်းသိလို့ မဆန်းသစ်ပါဘူး)။ ဒါကြောင့် Knowledge ဖြစ်ဖို့ဆိုရင် Novelty ပိုဖြစ်ဖို့ လိုအပ်တယ်။

---

## 4. The Ultimate Goal

The goal of evaluation is to move the system toward directly mining only interesting knowledge. Instead of finding everything and sorting it later, we want the computer to be smart enough to only show us the "interesting" stuff from the start.

---

## Summary

Imagine you are mining for gold. A computer might find thousands of shiny yellow rocks. Most are just "fool's gold" because they are too small, too brittle, or just common stones. Evaluation is the process of testing those rocks for accuracy, size (coverage), and value (novelty) so you only walk away with the real gold.

---

# Key notes from Tchel Hsu Myat Mo

- Transient dataဆိုတာက အချိန်တစ်ခုမှပဲထွက်လာတဲ့ patternကိုခေါ်တာ။

- Typicality data - ပုံမှန်pattern, novelty data - ပုံမှန်မဟူတ်တဲ့pattern



