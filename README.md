import java.util.Scanner;
public class tema2 {
    public static void main (String[] args) {

        //pr1
/*
        Scanner marioara = new Scanner(System.in);
        System.out.println("Tasteaza un numar ");
        int n1 = marioara.nextInt();
        Scanner marioara1 = new Scanner(System.in);
        System.out.println("Tasteaza un numar ");
        int  n2= marioara1.nextInt();

        long n= (n1+n2)/2;
        System.out.println("MA= " + n);
}}
*/


// pr2
     /*
        Scanner marioara2 = new Scanner(System.in);
        System.out.println("introduceti lungimea sirului ");
        int n = marioara2.nextInt();
        int v[]=new int[n];
        int s=0;

        for (int i=0;i<n;) {
            Scanner marioara3 = new Scanner(System.in);
            System.out.println("Tasteaza un numar ");
            v[i] = marioara3.nextInt();
            s += v[i];
            i++;
        }
           int med=s/n;
            System.out.println("suma=" + s);
            System.out.println("media=" + med);
    }}
*/


     // PR3
     /*
        Scanner marioara2 = new Scanner(System.in);
        System.out.println("introduceti lungimea sirului ");
        int n = marioara2.nextInt();
        int v[] = new int[n];
        int s = 0;
          int med=0;
        for (int i=0;i<n;) {
                Scanner marioara3 = new Scanner(System.in);
                System.out.println("Tasteaza un numar ");
                v[i] = marioara3.nextInt();
                if (v[i] == 0) {
                    i = n;
                    System.out.println("suma=" + s);
                    System.out.println("media=" + med);
                }
                s += v[i];
                i++;
                med = s / n;
            }
            System.out.println("suma=" + s);
            System.out.println("media=" + med);
            }}
            */


     // pt4/5 citesc vector in celsius si il calculez in farenhein
        /*
        Scanner marioara2 = new Scanner(System.in);
        System.out.println("introduceti lungimea sirului ");
        int n = marioara2.nextInt();
        int c[] = new int[n];
        int f[] = new int[n];
            for (int i=0;i<n;) {
                Scanner marioara3 = new Scanner(System.in);
                System.out.println("Tasteaza un numar ");
                c[i] = marioara3.nextInt();
                f[i] = c[i] * 9 / 5 + 32;
                i++;
        }
        for (int i=0;i<n;) {
            System.out.println("pentru  " + c[i] + " grade celsius =" + f[i] + "grade farenhein");
            i++;
        }
        }}
       */


        //pr 6
        /*
        Scanner marioara2 = new Scanner(System.in);
        System.out.println("introduceti lungimea sirului ");
        int n = marioara2.nextInt();
        int v[] = new int[n];
        int v1[] = new int[n];
        int max=0;
        int min=1;
        int s=0;
        for (int i=0;i<n;) {
            Scanner marioara3 = new Scanner(System.in);
            System.out.println("Tasteaza un numar ");
            v[i] = marioara3.nextInt();
            if(v[i]>max) {
                max=v[i];
            }
            else if(v[i]<min){
                min=v[i];
            }
            s+=v[i];
            v1[i]=v[i]*2;
            i++;
        }
        System.out.println("max= " + max);
        System.out.println("min= " + min);
        System.out.println("Sirul dublat");
        for (int i=0;i<n;) {
            System.out.println(v1[i]);
            i++;
        }
    }}
/*
