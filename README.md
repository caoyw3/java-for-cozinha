# java-for-cozinha
java for cozihna
package com.example.android.cozinha;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.Display;
import android.view.View;
import android.widget.TextView;

public class COZINHA extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_cozinh);
    }

    public void submit营养(View v ) {
        String A="enjoy cooking!";
        display(A);

    }
    private void display(String message){
        TextView yingyangtextview=(TextView)findViewById(R.id.yingyang_text_view);
        yingyangtextview.setText("1、番茄含有丰富的胡萝卜素，维生素B和C，特别是维生素B的含量居蔬菜之冠。其中含有的维生素C，具有抗坏血病、润肤、保护血管、降压、助消化、生津止渴，凉血平肝，清热解毒之功能和效果，对高血压、肾脏病人有特不错得辅助治疗做用。多吃番茄具有抗衰老作用，使皮肤保持白皙。\n" +
                "\n" +
                "2、番茄中富含的番茄红素含有对心血管具有保护做用的维生素和矿物质元素，能减少心脏病得发作。番茄红素还具有特别的抗氧化能力，能清除自由基，保护细胞，使脱氧核糖核酸及基因免遭破坏，能阻止癌变进程。西红柿除了对前列腺癌有预防做用外，还能有效减少胰腺癌、直肠癌、喉癌、口腔癌、乳腺癌等癌症的发病危险。\n" +
                "\n" +
                "3、番茄中得尼克酸能维持胃液得正常分泌，保进红血球得形成，有利于保持血管壁得弹性和保护皮肤。食用西红柿对防治动脉硬化、高血压和冠心病也有帮助。西红柿多汁，可以利尿，肾炎病人也宜食用。\n" +
                "\n" +
                "4、鸡蛋是自然界的一个奇迹，一个受过精的鸡蛋，在温度可以的机会下，没必要从外界补充任何养料，就能孵出一只小鸡，这就足以说明鸡蛋的营养。鸡蛋含有蛋白质、脂肪、卵黄素、卵磷脂、维生素和铁、钙、钾等人体所需要的矿物质。鸡蛋中含有丰富的DHA和卵磷脂等，对神经系统和身体发育有非常大的做用，能健脑益智，避免老年人智力衰退，并可改变各个年龄组的记忆力。\n    "
                + message);
    }
    public void submit选材(View v ) {
        String B="enjoy cooking!";
        displayprice(B);

    }
    private void displayprice(String message){
        TextView yingyangtextview=(TextView)findViewById(R.id.xuancai_text_view);
        yingyangtextview.setText( "1.\t决定番茄炒蛋好吃与否的，其实最重要的就是选番茄。番茄要选肉质新鲜细嫩的，太软烂的吃起来口感可疑，太硬的容易酸涩并且久煮不烂，都不太适合。总的来说，要挑那些表面光滑饱满，颜色鲜红，软硬度适中的。\n" +
                "\n" +
                "2.\t（当然，不是完美的，比如蒂头应该更青翠一些，白色部分也稍嫌多了，但总体是个很不错的同志）为了口感的好吃，建议对番茄进行预处理。在锅里烧开水，把洗干净的番茄丢进去滚一会儿，然后马上过凉水。拿刀轻轻地在番茄的表皮划两刀，你会发现番茄的皮变得非常好剥。这样的处理是为了在吃的时候口感不会被打断，我挺讨厌吃到皮的感觉 = =其次，蛋要选择新鲜的鸡蛋。一个小技巧，在打蛋的时候可以放一点凉水进去，不要太多，炒出来的蛋会更加柔软鲜嫩。如果要调味，也可以选择在打蛋的时候放盐。\n"
                +message);
    }
    public void submit制作(View v ) {
        String C="enjoy cooking!";
        displayquantity(C);

    }
    private void displayquantity(String message){
        TextView yingyangtextview=(TextView)findViewById(R.id.zhizuo_text_view);
        yingyangtextview.setText( "①先炒鸡蛋。多放油，油热后下鸡蛋，成型后差不多五六成熟即可起锅。\n" +
                "②盛出鸡蛋。如果有多余的油，就让它留在锅底\n" +
                "③炒西红柿。 我喜欢尽量切碎一些，在炒制中容易变得柔软的番茄沙，喜欢吃大块的就不要炒太久。但总体来说，炒太久都会破坏维生素。\n" +
                "④放入之前炒好的鸡蛋，翻炒，直到水乳交融。\n" +
                "⑤放葱花。（可选步骤） 有的人爱吃葱有的人不爱吃葱，如果爱吃葱的同志，我觉得葱花最后放香气更浓郁，也有爱用葱花炝锅的，也可以。我认为做饭没有定论，毕竟每个人口味不同。\n" + message
                );
    }
    public void submit火候(View v ) {
        String D="enjoy cooking!";
        displaysingle(D);

    }
    private void displaysingle(String message){
        TextView yingyangtextview=(TextView)findViewById(R.id.huohou_text_view);
        yingyangtextview.setText( "炒制此菜时，要旺火速成。虽然这道菜是最普通的家常菜，但炒的好坏一眼可知。这才叫烹饪技法。鸡蛋中加水淀粉可以使鸡蛋口感更爽滑。"
                +   message  );
    }
    public void submit摆放(View v ) {
        String E="enjoy cooking!";
        displaymarried(E);

    }
    private void displaymarried(String message){
        TextView yingyangtextview=(TextView)findViewById(R.id.baifang_text_view);
        yingyangtextview.setText(   "先将炒好的鸡蛋摆放在盘内居中并聚拢成一团，再将番茄摆放到鸡蛋的周围。"
                +   message  );
    }
}
