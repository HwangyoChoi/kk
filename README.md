#package day01;

/*
    private : 클래스내에서만 접근 
    default
    protected
    public  :전체 공개

*/
class Student
{
	 private  String name;
	 private int age=20; //인스턴스변수or 멤버변수 
     //setter:바꾸는  getter :얻어오는

	 public void setAge(int age)  // 매개변수 
	 {
		 this.age+=age;  // this.age=this.age+age;  
	      //System.out.print
		 ln(this.age);
		 // age: 매개변수 age를 의미, this.age=>인스턴스 변수 age를 의미
	 }
	  
}

public class AccTest {
	public static void main(String[] args) {

     Student s=new Student();
	 s.setAge(2);
	 
	}
}
