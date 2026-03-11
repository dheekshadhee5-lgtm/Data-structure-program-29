# Data-structure-program-29
#include <stdio.h>
Int main() {
 Int plane[3] = {11,12,13};
 Int priority[3] = {2,3,1};
 Int I,j,temp;
 For(i=0;i<3;i++){
 For(j=i+1;j<3;j++){
 If(priority[i] > 
priority[j]){
 Temp = plane[i];
 Plane[i] = plane[j];
 Plane[j] = temp;
 }
 }
 }
 Printf(“Plane landing 
order:\n”);
 For(i=0;i<3;i++){
 Printf(“Plane 
%d\n”,plane[i]);
 }
 Return 0;
 Plane landing order:
Plane 13
Plane 11
Plane 12
