#include <bits/stdc++.h> 
int findMajorityElement(int arr[], int n) {
	int num = -1;
    int cnt = 0;
    for(int i = 0; i<n; i++){
        if(arr[i] == num){
            cnt++;
        }
        else if(cnt == 0){
            num = arr[i];
            cnt = 1;
        }
        else {
            cnt --;
        }
    }
    cnt = 0;
    for(int i = 0; i<n; i++){
        if(arr[i] == num){
            cnt ++;
        }
    }
    
    if(cnt > n/2){
        return num;
    }
    return -1;

}
