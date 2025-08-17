# ansible_test

## 1. 서비스 구성도
<img width="391" height="215" alt="image" src="https://github.com/user-attachments/assets/68abb2dd-a268-47ad-89e7-8d7e03471e05" />

## 2. 설치
```
dnf install ansible

ansible --version
```

## 3. 조건 (when) 연산자

- ansible_fact['machine'] == 'x86_64'
- max_memory == 512
- min_memory < 128
- min_memory <= 128
- min_memory > 512
- min_memory != 512
- min_memory is defined or min_memory is not defined
- memory_avaiable
- not memory_avaiable
