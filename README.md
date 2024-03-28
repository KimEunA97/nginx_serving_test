# nginx_serving_test
nginx test

## nginx download
https://nginx.org/en/download.html

## 명령어

### nginx 시작
start nginx

### 프로세스 확인
tasklist /fi "imagename eq nginx.exe"

### 프로세스 종료
taskkill /IM nginx.exe /F

### (경로 이동 후) 중지, 새로고침
.\nginx -s stop
  
  .\nginx -s reload
