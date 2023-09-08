# V-tam-gi-c-u-trong-C-
Chúng ta sử dụng ba vòng lặp lồng nhau. Một vòng lặp bên ngoài để điều khiển số hàng. Hai vòng lặp bên trong: một vòng lặp để in các khoảng trống, một vòng lặp để in các dấu sao.  Dưới đây là chương trình để giải bài tập vẽ tam giác sao đều trong C++:
#include <iostream> 
#include <iomanip>
using namespace std; 
 
int main() {
   int n,i,j;
 
   n = 6;   // khai bao so hang.
 
   printf("Ve tam giac sao deu:\n");
   for(i = 1; i <= n; i++) {
      for(j = 1; j <= n-i; j++)
         printf(" ");
 
      for(j = 1; j <= i; j++)
         printf("* ");
 
      printf("\n");
   }
   return 1;
}
