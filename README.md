# tugas-cari-kata
#include<stdio.h>
main(){
int R[2][3]={1,9,7,3,4,6},m, flag=0, r, t ;
printf("Masukan nilai yang akan dicari:\n\n");
scanf("%i", &m);

for(r=0; r<2; r++){
for(t=0; t<3; t++){
if(m==R[r][t]){
flag=1;
}
}
}
if(flag==1){
printf("ADA");
}else{
printf("Tidak Ada");
}
}
