# 버그가 발생한 부분을 지적받기

## 설명
프로그래밍 초보자부터 경험자까지, 버그가 발생한 부분을 지적받기 위한 프롬프트입니다.

이번에는 배열의 범위를 벗어나 접근하는 경우, 프로그래밍에서 자주 발생하는 오류에 대해 실제 코드를 예로 들어 설명하고 있습니다.

```plaintext
아래의 C++ 코드에서 어디에서 오류가 발생할 가능성이 있을까요?

#include <iostream>

int main()
{
    int arr[3];
    
    for(int i=0; i<4; i++) {
        arr[i] = i+1;
    }
    
    for(auto x : arr) {
        std::cout << x << std::endl;
    }
    
    return 0;
}
```

```plaintext
아래의 C++ 코드에서 어디에서 오류가 발생할 가능성이 있을까요?

#include <iostream>

int main()
{
    int arr[3];
    
    for(int i=0; i<4; i++) {
        arr[i] = i+1;
    }
    
    for(auto x : arr) {
        std::cout << x << std::endl;
    }
    
    return 0;
}
```