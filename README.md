Exercise 1

int main(void) {

  float C;
  
  float F = C * 9/5 + 32;
  
  printf("Introduce the temperature in Celsius to Farenheit: ");
  
  scanf("%f", &C );
  
  F = C * 9/5 + 32;
  
  printf("%f° Celsius are %f° Farenheit", C , F);
  
  return 0;
  
}

Exercise 2

#include<stdio.h>

 int main(void){
 
 float r;
 
 float pi = 3.141516;
 
 printf("Please insert the radius: \n");
 
 scanf("%f",&r);
 
 float volume = ((pi* 4/3)* (pow(r, 3)));
 
 printf("The volume of the sphere is %f", volume);
 
 return 0;
 
}

Exercise 3
   
#include <stdio.h>

int main(void) {

  int perimeter, height, width;
  
  printf("Lets find the area a rectangle.\n");
  
  printf("Introduce the height: ");
  
  scanf("%d", &height);
  
  printf("Introduce the width: ");
  
  scanf("%d", &width);

  perimeter = (2 * height) + (2 * width);
  
  printf("The perimeter of the rectangle is: %d", perimeter);
  
  return 0;
}

Exercise  4 

#include <stdio.h>

int main(void) {

  float kmh, mph;
  
  printf("Introduce the velocity in kilometers per hour (Km/h): ");
  
  scanf("%f",  &kmh);
  
  mph = kmh * 0.6213712;
  
  printf("The velocity is %f miles per hour", mph);
  
  return 0;
  
  }

Exercise 5

int main(void) {

  int h, m, total_time;
  
  printf("Introduce the time in hours (no fractions): ");
  
  scanf("%d", &h);
  
  printf("Introduce the time in minutes: ");
  
  canf("%d", &m);
  
  total_time = (h * 60) + m;
  
  printf("The total time in minutes is: %d", total_time);
  
  return 0;
  
}
 
 Exercise 6
 
#include <stdio.h>

int main(void) {

  int h, m, fm;
  
  printf("Introduce the time in minutes (no fractions): ");
  
  scanf("%d", &m);
  
  h = m / 60;
  
  fm = m % 60;
  
  printf("In %d minutes there are %d hours and %d minutes", m, h, fm);
  
  return 0;
  
}
