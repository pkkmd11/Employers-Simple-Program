# Employers-Simple-Program
Java Program Myanmar Version;




public class PayrollwithTax {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
int hp,hw,gp,wt,np;
double tax;
Scanner input = new Scanner (System.in);
System.out.print("တစ်နာရီအလုပ်လုပ်ခ ");
hp=input.nextInt();
System.out.print("အလုပ်လုပ်ရသည့်ကြာ ချိန် ");
hw=input.nextInt();
gp=hp*hw;
System.out.println("စုစုပေါင်းရရှိသည့်ငွေ  ="+gp+"$");
if(gp<=300){
	tax = 0.1;
	tax=gp*tax;
	gp= (int) (gp-tax);
	System.out.println("ဆောင်ရသည့်အခွန်  ="+tax+"$");
	System.out.println("အခွန်ဆောင် ပြီးနောက် စုစုပေါင်းကျန်‌‌‌ငွေ ="+gp+"$");
}
else if(gp>=300.01 && gp<=400){
	tax = 0.12;
	tax=gp*tax;
	gp= (int) (gp-tax);
	System.out.println("ဆောင်ရသည့်အခွန်  ="+tax+"$");
	System.out.println("အခွန်ဆောင် ပြီးနောက် စုစုပေါင်းကျန်‌‌‌ငွေ ="+gp+"$");
}
else if(gp>=400.01 && gp<=500){
	tax = 0.15;
	tax=gp*tax;
	gp= (int) (gp-tax);
	System.out.println("ဆောင်ရသည့်အခွန်  ="+tax+"$");
	System.out.println("အခွန်ဆောင် ပြီးနောက် စုစုပေါင်းကျန်‌‌‌ငွေ ="+gp+"$");
}
else if(gp>=500.01){
	tax = 0.20;
	tax=gp*tax;
	gp= (int) (gp-tax);
	System.out.println("ဆောင်ရသည့်အခွန်  ="+tax+"$");
	System.out.println("အခွန်ဆောင် ပြီးနောက် စုစုပေါင်းကျန်‌‌‌ငွေ ="+gp+"$");
}

	}

}
