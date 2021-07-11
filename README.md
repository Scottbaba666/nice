//
//  main.c
//  nice
//
//  Created by Scott on 2021/4/28.
//

#include <stdio.h>
#include <string.h>

int main() {
    char ch1[] = "nihao";
    char ch2[] = "hh";
    char ch3[20];
    
    strcpy(ch1, ch2);
    strcpy(ch3, "666a");
    
    printf("ch1 = %s\n",ch1);
    printf("ch2 = %s\n",ch2);
    printf("ch3 = %s\n",ch3);
    return 0;
}
