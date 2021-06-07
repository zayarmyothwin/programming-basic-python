# programming-basic-python created on 7 June 2021
## Saturngod ရဲ့ Programming Basic စာအုပ်ဖတ်ပီးထုတ်ထားတဲ့ note များ
-------------------------------------------------------------
## အခန်း (၁) Programming ဆိုတာ
### Sequential
Programming မှာcodeတွေကတစ်ကြောင်းစီအလုပ်လုပ်တယ်။
### Variable
Variable ဆိုတာက data တွေကိုခဏတာ memory ပေါ်မှာသိမ်းထားပေးတဲ့နေရာပါ။ variable ကိုနာမည်ပေးဖို့လိုတယ်။ variable အမျိုးအစားလဲသတ်မှတ်ပေးဖို့လိုပါတယ်။
```python
counter=100 # An integer assignment
miles=100.0 # A floating point
name="John" # A String
boolean=True # Boolean value True and False only
```
### Bit and Stroage Data on Memory
Variable က memory ပေါ်မှာနေရာယူပီးခဏသိမ်းတယ်။Program ပိတ်လိုက်တဲ့အခါမှာ memory ပေါ်ကနေလည်းရှင်းလင်းလိုက်တယ်။ Computer မှာ 0 နဲ့ 1 ဘဲရှိတယ်။အဲ့ဒါကိုbitလို့ခေါ်တယ်။
* 8 bit ကို 1 byte။ 8 bit က binary system အရ 00000000 ကနေ 11111111 ထိရှိတယ်။
* binary value 11111111 ကို decimal ပြောင်း 255 ရလာပါတယ်။ 8 bit မှာအများဆုံးသိမ်းနိုင်တဲ့တန်ဖိုး။
* Integer ဟာ 32 bit ရှိပါတယ်။ Integer တန်ဖိုးမှာ unsigned နဲ့ signed ဆိုပီးရှိတယ်။ Unsign ဟာအပေါင်းကိန်းတွေဘဲဖစ်တဲ့အတွက် 32 bit အပြည့်အသုံးပြုနိုင်တယ်။ Signed ကတော့ +/- ပါတဲ့အတွက်ကြောင့် 31 bit ဘဲအသုံးပြုနိုင်တယ်။ 1 bit ကို အပေါင်းလားအနုတ်လားဆုံးဖြတ်ဖို့အတွက်ပေးရတယ်။

### Operators
Operators ဆိုတာကတော့ပေါင်းနှုတ်မြှောက်စားပါ။ Programming မှာ
* အပေါင်း +
* အနှုတ် -
* အမြှောက် * 
* အစား /
* အကြွင်း % 

## အခန်း (၂) Programming
### Pseudo code
Pseudo code ဆိုတာအတုအယောက်code ပုံမှန် english လိုဘဲရေးထားတာ။ Input, output, processing တွေအတွက်အောက်ပါ keyword တွေကိုအသုံးပြူတယ်။
* Input: READ, OBTAIN, GET
* Output: PRINT, DISPLAY, SHOW
* Compute: COMPUTE, CALCULATE, DETERMINE
* Initialize: SET, INIT
* Add one: INCREMENT, INCREASE, DECREMENT, DECREASE

### Flow Chart
Flow chart ဆိုတာကဘာပြီးရင်ဘာလုပ်မယ်ဆိုတာကို အဆင့်ဆင့်ပုံတွေနဲ့ဆွဲပြထားတာပါ။
#### Terminal
![Terminal](/image-note/terminal.png)
Flow chart အစ သို့မဟုတ် အဆုံး စသည့်နေရာတွေမှာအသုံးပြုပါတယ်။
အစကို start begin
![Start,Begin](/image-note/start-begin.png)
အဆုံးကိုတော့ End, Exit, Return တွေကိုအသုံးပြုပါတယ်။
![End](/image-note/end.png)

#### Line with arrows
တစ်ခုကနေနောက်တစ်ခုကိုသွားဖို့ညွှန်ပြထားတာပါ။ဒါအဆင့်ပြီးရင်ဘယ်ကိုသွားမလဲဆိုတာကိုညွှန်ပြတာပါ။
![arrow](/image-note/arrow.png)

#### Rectangle
Flowchart မှာစတုဂံတွေကို process, task, action, operation စသည့်အတွက်အသုံးပြုပါတယ်။ စတုဂံပုံဟာ action တခုခုလုပ်ဖို့တခုခုပြီးမြောက်ဖို့အတွက်ညွှန်ပြထားပါတယ်။
![Rectangle](/image-note/rectangle.png)

#### Decision
![Decision](/image-note/decision.png)
user ကိုမေးခွန်းမေးပြီးတော့အဖြေအပေါ်မူတည်ပြီးအလုပ်လုပ်စေချင်တဲ့အခါမှာ decision ကိုအသုံးပြုရပါတယ်။ input တစ်ခုဝင်ပြီးတော့ output မှာ Yes, No ဖြစ်ပါတယ်။ဒါဖြစ်ခဲ့ရင်ဒါလုပ် မဟုတ်ခဲ့ရင်ဘာလုပ်စသည်အတွက်အသုံးပြုနိုင်ပါတယ်။
![decision yesno](/image-note/yesno.png)

#### Circle
Flowchart ကအရမ်းရှည်သွားရင်သီးသန့်ဆွဲဖို့အတွက် circle ကိုအသုံးပြုပါတယ်။ flowchart တစ်ခုနဲ့တစ်ခုကို connect လုပ်ထားတယ်ဆိုတာကိုဖော်ပြထားသည့်သဘောပါ။ Circle အတွင်းမှာနာမည်ပါဝင်ပါတယ်။
![Circle](/image-note/circle.png)

#### Input/Output
User ဆီကနေ Data တွေကိုလက်ခံတော့မယ်ဆိုရင်တော့အနားပြိုင်စတုဂံကိုအသုံးပြုပါတယ်။
![Input/output](/image-note/input.png)

### Flowchart with codes
Programming ရဲ့အစ Hello World

#### Pseudo code နဲ့ဆိုရင်
print("Hello World")

#### Flow chart နဲ့ဆိုရင်
![Hello World](/image-note/helloworld.png)

#### Python နဲ့ဆိုရင်
print("Hello World")