
# test3

HI it's new branch
## subtitle
My wives:
- Fubuki
- Hood
- Ayanami
- Uchan
My waifu:
```cpp
#include<iostream>
#include<algorithm>
using namespace std;
int main(){
	int n;

	cin>>n;
	int array[n];
	for(int i = 0;i < n;i++){
		cin>>array[i];	
	}
	for(int i = 1;i < n;i++){
		for(int j = 1;j < n-i;j++){
			if(array[j] < array[j+1]){
				swap(array[j],array[j+1]);
			}
		}
	}
	for(int i =1;i< n;i++){
		cout<<array[i-1]<<" ";
	}
	cout<<array[n-1]<<endl;
}
```
[Google](https://Google.com)
