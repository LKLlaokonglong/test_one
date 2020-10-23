#                                                   第一次作业！

## 							写个冒泡循环吧(芜湖)

​                           					<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20201023082919802.png" alt="image-20201023082919802" style="zoom: 50%;" />  

***

public class BubbleSort{

public static void main(String[] args){

int [] a = {20,35,59,88,14};<!--没有排序前的数组-->
for(int x : a){

System.out.print(" " + x);<!--打印排序前的数组-->
}

for(int j = 0;j < a.length - 1;j++){

for(int k =0;k < a.length - 1 - j;k++){
if(a[k] >a [k+1]){

int temp = a[k];
a[k] = a[k+1];
a[k+1] = temp;


}

}
}

System.out.println("排序后的结果：" );
for(int x : a){
System.out.print(" " + x)

}



}




}



#                                                       

​													