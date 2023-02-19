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