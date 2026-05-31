# Shörolipi (সরলিপি)
### Shörol (সরল) + Shör (স্বর) + Lipi (লিপি)
maintainers: @rank-coder @Shoshostro

![shorolipi](https://socialify.git.ci/KhiproTeam/shorolipi/image?description=1&forks=1&issues=1&language=1&logo=https://github.com/KhiproTeam/shorolipi-logo/blob/main/shorolipi.png?raw=true&name=1&pattern=Circuit%20Board&pulls=1&stargazers=1&theme=Auto)

## কী এই shörolipi?
Type Banglish exactly the way it sounds.\
Banglish typing is messy, ambiguous, and inefficient. Shörolipi fixes this with just 26 keys — no obscure symbols, no extra effort. It can be implemented seamlessly on any QWERTY keyboard and captures the exact Bengali pronunciation, making typing faster, clearer, and phonetically precise.\
বাংলিশ লিখুন নিখুঁত উচ্চারণ-অনুসারে।\
আমাদের বাংলিশ টাইপিং অগোছালো, দ্বিধাপূর্ণ, এবং খামতিতে ভরা। সরলিপি মাত্র ২৬টি কী (key) ব্যবহার করে এর সমাধান দেয় — কোনো অস্পষ্ট প্রতীক বা বাড়তি পরিশ্রম ছাড়াই। এটি যেকোনো QWERTY কিবোর্ডে অনায়াসেই ব্যবহার করা যায় এবং বাংলার প্রতিটি ধ্বনি প্রকাশের ক্ষমতা রাখে। টাইপিংকে করে তোলে আরও দ্রুত, স্বচ্ছ এবং উচ্চারণগতভাবে স্পষ্ট।\
এর উপযুক্ত ব্যবহার হতে পারে ভিনভাষীদের সহজে বাংলা শেখাতে, কিংবা বাংলা টেক্সট অসমর্থিত প্ল্যাটফর্মে, কিংবা দৈনন্দিন টেক্সটিংয়ে।
### Key Features
```mermaid
flowchart LR
    A("রোমান বা লাতিন লিপিতে বাংলা লিখতে পারব")  --> B("পড়া যাবে দ্ব্যর্থহীনভাবে (unabmiguosly)")
    A --> E("বাংলার **সকল ধ্বনির উচ্চারণ** লেখা সম্ভব হবে") --> g("অতি সহজে **আঞ্চলিক ভাষা**ও লেখা যাবে")
    A --> C("**মাত্র ২৬টি বর্ণ** দিয়ে লেখা যাবে") --> D("সহজেই ফিট হবে আমাদের পরিচিত সব কিবোর্ডে")
    A --> F("ইংরেজির মতোই দ্রুত লেখা যাবে")
    A 
    
```
## উদাহরণ
```mermaid
flowchart TD
A("পোরা
(ভিতরে ঢোকানো)") --> B("pora")
E("পরা
(পরিধান করা)") --> F("pöra")
G("পোড়া
(দহন হয়েছে এমন)") --> H("poṛa")
C("পড়া
(পাঠ করা)") --> D("pöṛa")
```
```mermaid
flowchart TD
I("মেলা (মিলিত হওয়া) ") --> J("mela")
K("মেলা
(মেলে ধরা / জনসমাগম / প্রচুর)
(ম্যালা)") --> L("mëla")
```
## ফোনে যেমন দেখাবে

![Screenshot_20251204_012309](https://github.com/user-attachments/assets/874fe7dc-16db-4bd6-894b-842f15ca9886)

> [!NOTE]
> ফোনে লেখার সময় লং প্রেস করে পরিবর্তিত বর্ণের (ṛ ḍ ö ŋ ë ṭ) পরিবর্তে মূল qwerty লেআউটের বর্ণগুলো (q w f z x v) লেখা যাবে। ফলে চাইলে ইংরেজিতে সুইচ না করেও বাংলা ইংরেজি মিলিয়ে একসাথে লেখা যাবে।

## হাইলাইটস
- বেশিরভাগ ধ্বনি আমাদের পরিচিত উপায়েই লেখা হবে। যেসব ধ্বনি লাতিন হরফে সরাসরি লেখা যায় না সেগুলোর জন্য বিশেষ হরফ ব্যবহার করা হবে, যেমন:

|    |    |        |   |   |   |    |   |   |
| :-:|:-:| :-:| :-: | :-: |:-:|:-:|:-:|:-:|
| অ | অ্যা | ঙ / ং | ট | ঠ | ড | ঢ | ড় | ঢ় | 
| ö |  ë   |   ŋ   | ṭ | ṭh| ḍ  | ḍh| ṛ | ṛh |
|    |    |        |   |   |   |    |   |   |

- এই লিপি সম্পূর্ণরূপে উচ্চারণ-নির্ভর হবে। যেমন:

```mermaid
flowchart TD
A("বাসা") --> B("basha")
c("স্রোত") --> d("srot")
e("শাখা") --> f("shakha")
g("শ্রেণি") --> h("sreni")
i("ষাট") --> j("shaṭ")

```

```mermaid
flowchart TD
e("ক্যান
(why)") --> f("kën")
A("কেন
(why)") --> B("këno")
c("কেনো
(you buy)") --> d("keno")
```

## কীভাবে / কোথায় ব্যবহার করব?
1. ফোনে Heliboard -এ কাস্টোম লেআউট তৈরি করে লেখা যাবে
2. লিনাক্স পিসিতে [bn-shorolipi.mim for m17n](bn-shorolipi.mim) ব্যবহার করে লেখা যাবে।

## এক নজরে (ওভারভিউ)
Placeholder

## ইনস্টলেশন নির্দেশনা 
Placeholder


## আপনার মতামত দিন কিংবা ডেভেলপমেন্টে অবদান রাখুন
🔗 টেলিগ্রাম গ্রুপ: [**বাংলা লিখন বিপ্লব | shörolipi**](https://t.me/BanglaScriptRevolution)

### Authors
Nafee [@rank-coder](https://github.com/rank-coder)\
Tareq Rahman [@shoshostro](https://github.com/Shoshostro)

## বিস্তারিত নির্দেশনা
### ক্যাপিটালাইজেশন তথা বড়ো হাতের বর্ণের ব্যবহার
<details>
    <summary>পড়তে ক্লিক করুন</summary>

1. বাক্যের শুরুতে বড়ো হাতের বর্ণ ব্যবহার করা হবে। যাতে বাক্যের শুরু সহজে খুঁজে পাওয়া যায় এবং পড়তে সুবিধা হয়।
2. মানুষের নাম, জায়গার নাম, ইত্যাদি, তথা **নামবাচক বিশেষ্যের** প্রথম বর্ণতে বড়ো হাতের বর্ণ ব্যবহার করা হবে। যেমন: Mirpur, Khulna, Robindronath, ইত্যাদি।
3. যদি ভবিষ্যতে shörolipi ব্যবহার করে কোনো অ্যাক্রোনিম (acronym), অথবা অ্যাব্রেভিয়েশন (abbreviation) তৈরি করা হয় তবে সেগুলোও বড়ো হাতের বর্ণে লেখা হবে।
4. অন্যান্য সকল ক্ষেত্রে সর্বদা ছোটো হাতের অক্ষর লেখা হবে।
</details>

### আঞ্চলিক ভাষা লেখা
দৈনন্দিন আলাপচারিতায় কিংবা আঞ্চলিক ভাষা লেখার সময় নিজের উচ্চারণ অনুযায়ী লেখা যাবে। যেমন: boltesi, jaitesi, ইত্যাদি।
### ঙ, ং ইত্যাদির উচ্চারণ লেখা
<details>
    <summary>পড়তে ক্লিক করুন</summary>

ঙ, ং লেখা হবে ŋ দিয়ে। যেমন:  

```mermaid
flowchart TD
a("রাঙা") --> b("raŋa")
c("বঙ্গ") --> d("böŋgo")
e("এবং") --> f("eböŋ")
g("বাংলা") --> h("baŋla")
```
</details>

### ঞ এর উচ্চারণ লেখা
<details>
    <summary>পড়তে ক্লিক করুন</summary>
Placeholder
    </details>

### অ এবং ও এর উচ্চারণ
<details>
    <summary>পড়তে ক্লিক করুন</summary>
Placeholder
            </details>

### শ, স, এবং, ষ এর উচ্চারণ
<details>
    <summary>পড়তে ক্লিক করুন</summary>
Placeholder
                </details>

### ন এবং ণ
<details>
    <summary>পড়তে ক্লিক করুন</summary>
Placeholder
                    </details>

### ট, ঠ, ড, ঢ এর উচ্চারণ লেখা
<details>
    <summary>পড়তে ক্লিক করুন</summary>                    
Placeholder
</details>

### ড়, ঢ় এর উচ্চারণ লেখা
<details>
    <summary>পড়তে ক্লিক করুন</summary>
Placeholder
    </details>

### চন্দ্রবিন্দুর উচ্চারণ লেখা
চন্দ্রবিন্দুর উচ্চারণ লেখা যথাসম্ভব এড়িয়ে যাওয়া হবে, যেহেতু আমাদের মূল লক্ষ্য হলো লিখনপদ্ধতিকে সহজ করা। তবে একান্ত প্রয়োজনে চন্দ্রবিন্দুর উচ্চারণ লেখারও উপায় আছে।

### হ সংবলিত যুক্তবর্ণের উচ্চারণ লেখা
<details>
    <summary>পড়তে ক্লিক করুন</summary>
aobhan
</details>

### উপযুক্ত কিছু ফন্টের তালিকা
যেসব ফন্টে ṛ ḍ ö ŋ ë ṭ এই বর্ণগুলো খারাপ দেখায় না, এবং পড়তে অসুবিধা হয় না সেরকম কিছু ফন্টের তালিকা:
#### ইংরেজি ফন্ট
| Font | ScrnShot |
| --- | --- |
| Times New Roman | ![Times New Roman](/img/tnr.png) |
| Arial | ![Arial](/img/arl.png) |
| Ubuntu | ![Ubuntu](/img/ubn.png) |
| Courier | ![Courier](/img/cou.png) |
| Noto Serif | ![Noto Serif](/img/nsf.png) |
| Noto Sans | ![Noto Sans](/img/nsn.png) |
| Roboto | ![Roboto](/img/rbt.png) |
| Inter | ![Inter](/img/itr.png) |