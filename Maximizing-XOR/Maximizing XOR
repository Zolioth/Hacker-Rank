#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>
#include <assert.h>

int maxXor(int l, int r) {
	int ret = 0;
    for (int a = l; a <= r; a++) {
       for (int b = a; b <= r; b++) {
           ret = max(ret, a ^ b);
       }
    }
    return ret;
}

int max(int a, int b){
    if (a>b){
        return a;
    }
    else{
        return b;
    }
}


int main() {
    int res;
    int _l;
    scanf("%d", &_l);
    
    int _r;
    scanf("%d", &_r);
    
    res = maxXor(_l, _r);
    printf("%d", res);
    
    return 0;
}
