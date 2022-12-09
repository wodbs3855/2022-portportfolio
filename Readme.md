# 2022-portportfolio
<br>

**Android 사용한 기술**

<br>
<br>

**Blue Tooth**

<br>

* 안드로이드는 블루투스를 지원하여 스마트폰이 다른 블루투스 기기와 무선으로 통신할 수 있습니다.<br>
  통신은 Android Bluetooth API를 통해서 이루어지는데, 이를 사용해서 다음과 같은 작업을 수행할 수 있습니다.<br>

1. 다른 블루투스 기기 스캔(기기 검색, 페어링된 기기확인)
블루투스 기기 연결
연결된 기기간 데이터 전송 및 수신
블루투스 프로필
2.
3.
4.

<div align=center>

![1](https://user-images.githubusercontent.com/73435598/206702608-a79e0cd0-1e9d-4cc0-bcb1-c81ae77b74fa.png)

</div>

<br>
<br>

**2. API JSon**

<br>

* OpenWeater API는 Json형식으로 불러와진다

<br>

<div align=center>

![2](https://user-images.githubusercontent.com/73435598/206702756-5f68614b-d0e5-478e-9387-5422cadaae72.png)

</div>

<br>
<br>

각 데이터들의 세부사항은 [Json referance](https://openweathermap.org/weather-data) 참조

**3. 이미지 불러오기**

* OpenWeater API는 해당 하는 날씨의 이미지기능도 지원한다

<br>
<br>

**example**

<br>

```
this.img_url='http://openweathermap.org/img/wn/'+this.W_state.icon+'@2x.png';
this.W_state.icon : get으로 가져온 데이터에서 아이콘 정보(weather.icon from response)를 가져와야한다
```

<div align=center>

![3](https://user-images.githubusercontent.com/73435598/206703196-96a1bc01-9872-4283-9918-9c2d91ac85df.png)

</div>

<br>
<br>

## referance

[OpenWater API 이미지](https://openweathermap.org/weather-conditions)<br>

[OpenWater API Json](https://openweathermap.org/weather-data)<br>
