# RoomFit 장례치르고 WebRTC 연습

## Mac OS 방화벽 설정
```
sudo nano /etc/pf.conf
pass in proto tcp from any to any port 7777
pass in proto udp from any to any port 7777
```

## 확인
```
sudo pfctl -vnf /etc/pf.conf
```

## 실행
```
python3 app.py
```

## https: 관련 브라우저 보안 설정
설정에 도메인 추가

```
chrome://flags/#unsafely-treat-insecure-origin-as-secure
```

