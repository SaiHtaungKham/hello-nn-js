# Hello World of Neural Network

အခုနောက်ပိုင်း Machine Learning, Deep Learning, Artificial Neural Network (ANN), Convolutional Neural Network (CNN) စသဖြင့် AI ပိုင်းဆိုင်ရာ နည်းပညာများ ခေတ်စားလှသည်။ စာရေးသူအနေနှင့် ဤကဏ္ဍတွင် တစ်စိုက်မတ်မတ် လေ့လာနေသော ကွန်ပျူတာသိပ္ပံသမား မဟုတ်ခြင်းကြောင့် လည်ကောင်း၊ ခေတ်စားခါစ နည်းပညာများကို ချက်ခြင်း လေ့လာအသုံးချခြင်း မပြုပဲ တည်ငြိမ်ခိုင်မာမှုကို ရရှိလာသည့် အချိန်ထိ စောင့်လေ့ရှိသော အလေ့အထကြောင့် လည်ကောင်း ယခုအချိန်ထိ ထိုနည်းပညာများကို ကောင်းမွန်နှံ့စပ်စွာ သိရှိခြင်း မရှိသေးချေ။

အဘယ်ကြောင့် ခေတ်စားစ နည်းပညာသစ်များကို ချက်ခြင်း မလေ့လာသနည်းဟူမူ၊ ခေတ်စားစ အချို့သော နည်းပညာများသည် လူ့ဘောင် လောကကြီး တစ်ခုလုံး တစ်ခေတ်ဆန်း သွားစေလောက်အောင် ဆက်လက်ထွန်းပေါက် အောင်မြင်သွားကြသော်လည်း အချို့ကမူ နေ့မြင်၍ညပျောက် မနက်ဖြန် ဘယ်ရောက်သွားမှန်းမသိ ဖြစ်တတ်ကြပေသည်။ ထို့ကြောင့် ကိုယ်ရေးကိုယ်တာ များလှသည့်အပြင် အပျင်းထူလှသော စာရေးသူသည် ခေတ်စားတိုင်း မလေ့လာပဲ နေ့မြင်ညပျောက် မဟုတ်တာ သေချာပြီဆိုမှ စလေ့လာသည့် အလေ့အကျင့် ရှိပေသည်။

ယခုအခါတွင် ML/DL အစရှိသော AI နှင့် ဆက်စပ်နည်းပညာများသည် ခေတ်စားစ အဆင့်ကို ကျော်လွန်၍ တစ်ခေတ်ဆန်းစေသည့် အဆင့်ကို ရောက်ရှိလာကြလေပြီ။ ထို့ကြောင့် စတင်လေ့လာရန် သင့်ပြီဟုယူဆ၍ အနည်းငယ် စတင်လေ့လာကြည့်မိသည်။ ထို့သို့ လေ့လာကြည့်ရာတွင် "Hello World" အဆင့် အလွန်ရိုးရှင်း၍ အခြေခံကျလှသော Neural Network သော Machine Learning ပရိုဂရမ်ငယ်တစ်ခုကို Python အသုံးပြု ရေးသားပြထားသည့် နမူနာတစ်ခုအား လေ့လာမိလေသည်။

ထိုသို့လေ့လာမိရာတွင်.. စိတ်ကူးပေါက်ပေါက်နှင့် အဆိုပါ Python ပရိုဂရမ်ကို နမူနာယူ၍ မိမိ ရင်းနှီးကျွမ်းကျင်ရာ JavaScript ဖြင့် အလားတူ ပရိုဂရမ်ငယ်တစ်ခု စမ်းသပ်ရေးသား ကြည့်မိသည်။ ထိုသို့ ရေးသားထားသည့် ပရိုဂရမ်ကို စိတ်ဝင်စားသူများ လေ့လာစမ်းသပ်နိုင်ရန် ပြန်လည် မျှဝေလိုစိတ် ဖြစ်မိသည်။ ဤနေရာတွင် Machine Learning နှင့် Neural Network တို့အကြောင့် အကျယ် ချဲ့နိုင်မည် မဟုတ်ပေ။ ချဲ့နိုင်လောက်သည့် ဗဟုသုတ စာရေးသူကိုယ်တိုင်တွင် ပြည့်စုံခြင်း မရှိသေး။ ဤနေရာတွင် ရေးသားထားသည့် ပရိုဂရမ် အကြောင်းကိုသာ အနည်းငယ် ရှင်းပြလိုခြင်း ဖြစ်ပေသည်။

အောက်ပါ Array ကို လေ့လာကြည့်ပါ။

```javascript
var inputs = [
    [0, 0, 1],  // -> 0
    [1, 1, 1],  // -> 1
    [1, 0, 1],  // -> 1
    [0, 1, 1]   // -> 0
];
```

ဤ Array ကို Matrix တစ်ခုဟု ရှုမြင်သင့်သည်။ သို့မဟုတ် ရိုးရိုး Array တစ်ခုလိုသာ သဘောထားလိုကလည်း ထားနိုင်သည်။ ပထမ Row တွင် ပါဝင်သော `0, 0, 1` ၏ ရလဒ်သည် `0` ဖြစ်သည်။ ဒုတိယ `1, 1, 1` ၏ ရလဒ်သည် `1` ဖြစ်သည်။ `1, 0, 1` အတွက် ရလဒ် `1` ဖြစ်ပြီး `0, 1, 1` အတွက် ရလဒ် `0` ဖြစ်သည်။ သို့ဆိုလျှင် ဤစာရင်းထဲတွင် မပါဝင်သေးသော `1, 0, 0` (သို့) `0, 1, 0` ၏ရလဒ် မည်သို့ ဖြစ်မည်နည်း? ဤသည်ကို ရှာဖွေ အဖြေထုတ်ပေးနိုင်သော Neural Network သုံး ပရိုဂရမ်ငယ်တစ်ခုကို ရေးသားထားခြင်း ဖြစ်သည်။

ပထမဦးစွာ - အဖြေစာရင်းကို ဤသို့ ကြိုတင်ပြင်ဆင်ထားရှိသည်။

```javascript
var test_result = [0, 1, 1, 0];
```

ထိုကြောင့် ယခုအခါ နမူနာဒေတာဖြစ်သော `inputs` နှင့် ၄င်း၏အဖြေဖြစ်သော `test_result` တို့ကို ရရှိပေပြီ။ ဆက်လက်၍ Synaptic Weights ခေါ် စမှတ်တန်ဖိုးတစ်ခု လိုအပ်သည်။ မူသဘောအမှန်ကို နောက်မှလေ့လာပါ၊ ဤနေရာတွင်တော့ အဆိုပါ Weights ကို "အစမ်းအဖြေ" ဟု သဘောထားပါလေ။

```javascript
var weights = [ rand(), rand(), rand() ];
```

ဤအစမ်းအဖြေစာရင်းသည် Random တန်ဖိုးများ ဖြစ်သဖြင့် မှားမှာ သေချာပေသည်။ သို့သော် ထိုအဖြေမှားကို နီးစပ်သော အဖြေမှန်ဖြစ်အောင် တစ်ဖြည်းဖြည်း သင်ယူနိုင်အောင်  ဆက်လက် ရေးသားထားပေသည်။ **မှတ်ချက်** - `rand()` သည် `-1` နှင့် `1` ကြား Random ကိန်းကဏန်းတစ်ခုကို ထုတ်ပေးအောင် ကြိုတင်ရေးသားထားသော Function ဖြစ်သည်။ ဤနေရာတွင် မလိုအပ်ပဲ မရှုပ်စေလို၍ ထို Function ကို မဖော်ပြလိုသေးပေ။ `rand()` Function က `-1` နှင့် `1` ကြား ကျပန်းကိန်းကဏန်းကို ပြန်ပေးသည်ဟုသာ မှတ်ပါလေ။

```javascript
function train(inputs, test_result, iterations) {
    for(var i = 0; i < iterations; i++) {
        var output = sigmoid( dot( inputs, weights ) );
        var error = array_sub(test_result, output);

        var adjustment = dot(
            T(inputs),
            array_multi(
                error,
                sigmoid_derivative(output)
            )
        );

        weights = array_add(weights, adjustment);
    }
}
```

ဖော်ပြထားသော `train()` Function သည်၊ နမူနာဒေတာဖြစ်သော `inputs`, အဖြေစာရင်းဖြစ်သော `test_result` နှင့် လေ့ကျင့်ရမည့် အကြိမ်ရေ `iterations` တို့ကို လက်ခံသည်။ ထို့နောက် `iterations` သတ်မှတ်ချက်အတိုင်း အကြိမ်ကြိမ် လေ့ကျင့်သည်။ ထိုသို့လေ့ကျင့်ရာတွင် သုံးသော `sigmoid()` Function သည် ပေးလိုက်သော တန်းဖိုးအား `1` နှင့် `0` ကြားတန်ဖိုးဖြစ်အောင် ပြောင်းပေးသော Function ဖြစ်သည်ဟု အလွယ်မှတ်ပါ။

**ဥပမာ** - `sigmoid(5)` ဟုဆိုလျှင် `0.9933071490757153` ကိုရရှိပေမည်။ `1` နှင့် `0` ကြား တန်ဖိုးတစ်ခုဖြစ်သည်။

`dot()` Function သည် Array Matrix နှစ်ခုကို မြှောက်ပေးနိုင်သော Matrix Multiplication လုပ်ငန်းကို ဆောင်ရွက်ပေးသည်။

![Dot Product](https://www.mathsisfun.com/algebra/images/matrix-multiply-a.svg)

ကျွန်ုပ်တို့ အထက်တန်းအဆင့် သင်္ချာတွင် သင်ခဲ့ကြဖူးသည်။ သို့သော်.. စာဖတ်သူတော့မသိ.. စာရေးသူတော့ မေ့နေလေပြီ။ လောလောဆယ် ပြန်မလေ့လာ လိုသေးလျှင်၊ ပထမ Array ဖြစ်သော `inputs` ပါ တန်ဖိုးများနှင့် ဒုတိယ Random Array ဖြစ်သော `weights` ပါတန်းဖိုးတို့ကို မြှောက်ပေးသည်ဟု ခေတ္တ အလွယ်မှတ်နိုင်သည်။

ဤသို့မြှောက်၍ရလာသော တန်ဖိုးကို `sigmoid()` အကူအညီဖြင့် `1` နှင့် `0` ကြားတန်ဖိုးဖြစ်အောင် ပြောင်းပြီး ရလာသော တန်ဖိုး မှန်မမှန် နောက်တစ်ဆင့်တွင် စစ်ဆေးထားခြင်း ဖြစ်သည်။ လိုရင်းမှာ.. မမှန်လျှင် `weights` တန်ဖိုးပြောင်း၍ နောက်တစ်ကြိမ် စမ်းမည်။ အကြိမ်ကြိမ် စမ်းမည်။ မမှန်မချင်းစမ်းမည်။ နောက်ဆုံးတွင် ကြိုပေးထားသည့် အဖြေမှန်နှင့် အနီးစပ်ဆုံးသော `weights` ကိုရရှိမည် ဖြစ်ပေတော့သည်။

`weights` တန်းဖိုးပြောင်းရာတွင် ရှိရှိသမျှ ဖြစ်တန်ခြေရှိသော တန်ဖိုးအားလုံး တစ်ခုပြီးတစ်ခု လိုက်ပြောင်းခြင်း မဟုတ်ပေ။ Sigmoid Curve ခေါ် S ပုံသဏ္ဍာန် မျဉ်းကွေးထွက်အောင် တွက်၍ တန်ဖိုးသည် ထိုမျဉ်းကွေးဘောင်ထဲတွင် ဝင်နေအောင် ပြောင်းခြင်းဖြစ်သည်။ `sigmoid_derivative()` Function က တွက်ချက်ရရှိသော `weights` အသစ်သည် Curve ဘောင်ကို မကျော်အောင် ထိမ်းပေးသည့် Function ဖြစ်သည်။ 

![Sigmoid Curve](https://cdn-images-1.medium.com/max/800/1*sK6hjHszCwTE8GqtKNe1Yg.png)

ကျန် Function တစ်ခုဖြစ်သော `T()` သည် Array Matrix ၏ Row များကို Column ဖြစ်အောင် Transpose လုပ်ပေးသော Function ဖြစ်သည်။

![Transpose](https://chortle.ccsu.edu/VectorLessons/vmch13/mtrxTrans1.gif)

အသေးစိတ် သိရှိလိုပါက ဆက်လက် လေ့လာရပေမည်။ ဤနေရာတွင်တော့ မူလအစ Random weight ဖြင့်စ၍ နမူနာဒေတာအတွက် ကြိုပေးထားသော အဖြေမှန်နှင့် မနီးစပ်မချင်း ထို Random တန်ဖိုးကို ထပ်ခါထပ်ခါ ပြင်ကြည့်သည်ဟုသာ အလွယ်မှတ်နိုင်သည်။ နောက်ဆုံး ရရှိလာသော အဖြေမှန်နှင့် နီးစပ်သည့် `weights` ကို အသုံးပြုခြင်းအားဖြင့် မူလဒေတာတွင် မပါဝင်သော အလားတူ ဒေတာများကို စီစစ်နိုင်ပေတော့မည်။

```javascript
function think(inputs) {
    return sigmoid(dot(inputs, weights));
}
```

အထက်တွင် ဖော်ပြခဲ့သော `train()` Function ကိုသုံး၍ လိုအပ်သော `weights` ကို ရရှိပြီး ဖြစ်ပါက ဤ `think()` Function ကို သုံး၍ မူလဒေတာတွင် မပါဝင်သော အချက်အလက်များကို စမ်းသပ်လိုက စတင်စမ်းသပ် ကြည့်နိုင်ပြီဖြစ်သည်။ ဥပမာ -

```javascript
console.log("Initial Weights: " + weights + "\n");
// Output Example => Initial Weights: -0.30,-0.73,0.37

train(inputs, test_result, 10000);

console.log("Trained Weights: " + weights + "\n");
// Output Example => Trained Weights: 9.67,-0.20,-4.62
```

နမူနာအရ မူလ `wights` သည် Random ဖြစ်သော်လည်း အကြိမ် `10,000` Train ပြီးသော နောက်တွင် ရရှိလာသော `weights` အရ Array Matrix တွင် ရှေ့ဆုံးတန်ဖိုးက ကျန်နှစ်ခုထက် သိသိသာသာ ကြီးနေသည်ကို တွေ့နိုင်ပေသည်။ ဤကဲ့သို့ ရရှိလာသော `weights` ကို သုံး၍ ဒေတာသစ်များကို စမ်းသပ်ကြည့်နိုင်သည်။

```javascript
console.log( think( [[1, 0, 0], [0, 1, 0]] ) );
// Output Example => [ 0.99, 0.44 ]
```

နမူနာအရ `1, 0, 0` အတွက် အဖြေသည် `0.99` ဖြစ်၍ `0, 1, 0` အတွက် အဖြေကမူ `0.44` ဖြစ်နေသည်ကို တွေ့ရပေမည်။ အနီးဆုံးယူလိုက်လျှင် `1, 0, 0` အတွက် အဖြေ `1` ဖြစ်၍ `0, 1, 0` အတွက် အဖြေ `0` ဖြစ်သည်။ ယခုအခါ မူလနမူနာ ဒေတာတွင် မပါသော ဒေတာသစ်များကိုပင် အဖြေမှန် ထုတ်ပေးနိုင်သော ပရိုဂရမ်ငယ်တစ်ခုကို ရရှိသွားပေတော့သည်။ အံ့ဖွယ် ကောင်းလေစွတကား...

* မူရင်း Python နမူနာကို [ဤနေရာတွင်](https://medium.com/technology-invention-and-more/how-to-build-a-simple-neural-network-in-9-lines-of-python-code-cc8f23647ca1) လေ့လာနိုင်သည်
* ကျွန်ုပ်၏ JavaScript ကုဒ်အပြည့်အစုံကို [ဤနေရာတွင်](https://github.com/eimg/hello-nn-js/blob/master/hello.nn.js) လေ့လာနိုင်သည်

မူရင်း Python နမူနာတွင် သင်္ချာဆိုင်ရာ တွက်ချက်မှုများအတွက် Numpy ခေါ် Math library ကို အသုံးပြု၍ ဖော်ပြထားသဖြင့် စမ်းသပ် ကြည့်နိုင်ရန် Numpy လိုအပ်ပေလိမ့်မည်။ စာရေးသူ၏ JavaScript တွင်မူ ဤကဲ့သို့ Library မျိုးကို အသုံးမပြုပဲ Matrix Multiplication, Transpose စသည့် လိုအပ်သည့် လုပ်ဆောင်ချက်များကို ဆောင်ရွက်ပေးနိုင်သော Helper Function များကို တစ်ပါတည်း ထည့်သွင်း ရေးသားထားသဖြင့် Dependency မရှိပဲ တိုက်ရိုက်စမ်းနိုင်သည်။

ကျေးဇူးတင်ပါသည်။
