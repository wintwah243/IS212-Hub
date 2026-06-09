# Completeness and Optimization (slide20 - 9.6.2026)

Once we know what makes a pattern "interesting" (from the previous slides), we have to ask if our computer systems are actually good at finding them. This slide introduces two key questions that developers of data mining systems must answer.

---

## 1. Completeness: "Can we find everything?"

**The Question:** Can a data mining system generate all of the interesting patterns that exist in a database?

**What it means:** Completeness refers to the thoroughness of the algorithm. A "complete" system is one that doesn't miss any valuable nuggets of information.

Database တစ်ခုလုံးထဲမှာ ရှိသမျှသော စိတ်ဝင်စားဖွယ် Pattern အားလုံးကို တစ်ခုမှ မကျန်ရအောင် စနစ်က တူးဖော်ပေးနိုင်စွမ်း ရှိ/မရှိ (Thoroughness) ကို တိုင်းတာခြင်း ဖြစ်တယ်။ "ပြည့်စုံသောစနစ်" ဆိုတာက တန်ဖိုးရှိတဲ့ အချက်အလက်အသေးအမွှားလေး (Nuggets) ကိုပင် လုံးဝကျန်ခဲ့ခြင်း မရှိစေရပါ။

**The Challenge:** Because databases are so huge, it is very difficult to search every single possible combination to ensure nothing was overlooked.

ဒေတာပမာဏက အဆမတန် ကြီးမားလွန်းတဲ့အတွက် ဖြစ်နိုင်ခြေရှိတဲ့ Combination ပေါင်းစုံကို လိုက်လံရှာဖွေဖို့ဆိုတာ computational ကုန်ကျစရိတ် အရမ်းများပြီး လက်တွေ့မှာ အလွန်ခက်ခဲပါတယ်။

---

## 2. Optimization: "Can we find ONLY the good stuff?"

**The Question:** Can a data mining system generate only interesting patterns?

**What it means:** This is known as an optimization problem.

စနစ်ကနေ မလိုအပ်တဲ့ အမှိုက်ဒေတာတွေကို ဖယ်ထုတ်ပြီး၊ တကယ်စိတ်ဝင်စားဖို့ကောင်းတဲ့ (Interesting ဖြစ်တဲ့) Patterns တွေကိုပဲ ကွက်တိ ထုတ်ပေးနိုင်စွမ်း ရှိ/မရှိကို ဆိုလိုခြင်း ဖြစ်တယ်။

**The Challenge:** If a system is "complete" but not "optimized," it might give you 100 useful patterns mixed in with 1,000,000 useless ones. An optimized system uses smart shortcuts to ignore the "junk" data and focus only on the patterns that meet our interestingness criteria (like high accuracy or novelty).

အကယ်၍ Algorithm တစ်ခုက Completeness သာရှိပြီး Optimized မဖြစ်ဘူးဆိုရင်၊ တကယ်အသုံးဝင်တဲ့ ပုံစံ ၁၀၀ ကို ရှာဖွေပေးနိုင်လိမ့်မယ်။ ဒါပေမဲ့ အဲဒီ ၁၀၀ ကို အသုံးမဝင်တဲ့ အမှိုက်ပုံစံ ၁,၀၀၀,၀၀၀ ကြားထဲ ညှပ်ပြီး ထုတ်ပေးတတ်ပါတယ်။ ဒါကြောင့် Junk (အမှိုက်) တွေကို အလိုအလျောက် ကျော်ဖြတ်ပြီး "Good stuff" တွေကိုပဲ Focus လုပ်နိုင်ဖို့ Smart Shortcuts (Heuristics) တွေ သုံးရပါတယ်။

---

## Summary

Think of a data mining system like a metal detector on a beach:

**Completeness** is making sure the detector is sensitive enough to find every single coin buried in the sand. You don't want to walk over a gold ring and not hear a beep.

**Optimization** is making sure the detector only beeps for gold and silver, rather than beeping for every rusty nail or bottle cap it finds. You want the most value for your time without digging up trash.

---

# Key notes from Tchel Hsu Myat Mo

