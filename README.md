# -Zadanie11
№11
Задание номер 1
public class Main {
public static void main(String[] args) {
int[][] mas = new int[8][8];
for(int i = 0; i < mas.length; i++) {
for(int j=0; j < mas.length; j++) {
if((i+j)%2 == 0) mas[i][j] +=1;
System.out.print(" " + mas[i][j]);
}
}
}
}

Задание номер 2

public class Main
{
	public static void main(String[] args) {
	
	int[][] a=new int[10][10];
  for (int i=0;i < a.length;i++){
    for (int j=0;j < a[i].length;j++){
      a[i][j]=(int)(Math.random()*10);
      }
     }
for (int i=0;i < a.length;i++,System.out.println("Ответик")){
for (int j=0;j < a[i].length;j++){
System.out.print(a[i][j]+" ");

           }
		}
		}
		}


Задание номер 3
public class Main {
 
   
 
    public static void main(String[] args) {
        
       
    int array[][] = new int[3][3];
        int sum = 0;
        //Заполняем массив данными
        for (int i = 0; i < array.length; i++) {
            for (int j = 0; j < array[i].length; j++) {
                array[i][j] = (int) ((Math.random() * 10)+1);   
                System.out.println(array[i][j] + "    ");
            }
        }
        //Считаем все элементы двумерного массива
        for (int i = 0; i < array.length; i++) {
            for (int j = 0; j < array[i].length; j++) {
                sum += array[i][j];
            }
        }
        System.out.println("Сумма всех элементов двумерного массива = "+sum);


    }
}   
Задание номер 4

public class Main {
public static void main (String[] args){
int[] arr = new int[]{2,3,4,5,6,7,8,9,10,11};
for (int i = 0; i< arr.length; i++){
if (Number(arr[i]) == 1){
System.out.print(arr[i]+" ");
}
}
}

private static int Number(int number)
{
for (int i=2; i<number; i++)
{
if (number%i == 0)
{
return 0;
}

if ((i==number) || (i>Math.sqrt(number)))
{
return 1;
}
}

return 0;
}
}
