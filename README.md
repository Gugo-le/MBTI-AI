# 인공지능이 판단한 당신의 mbti는?

<img src="./cover.png">


## About this

[https://mbtiai.netlify.app/](https://mbtiai.netlify.app/) 

개발 일지: [https://m.blog.naver.com/PostView.naver?blogId=rngustmd0719&logNo=222831236029&navType=by](https://m.blog.naver.com/PostView.naver?blogId=rngustmd0719&logNo=222831236029&navType=by) 

**제작동기**

지난 여름 방학... 지금은 모르겠지만 한 떄 mbti검사가 한창 유행이었다. 문답 형식이 아닌 사진 형식으로 만들어보고 싶었다.

**제작기간**
2022.07.21 ~ 2022.07.26

**제작인원**
1명

**실행순서**
1. 성별을 선택한다.

2. 자신의 얼굴 사진을 업로드하거나 찍는다.

3. 인공지능이 당신의 얼굴을 보고 예상하는 mbti를 출력한다.




	



<br />

## 참고자료

1. 조코딩 유튜브

2. teachable machine
<br>

## Dependencies & Tools 
<br>

# **tools**

**tools**

IDE : VScode
Framework : HTML, CSS, JS



## How to develop

```python
from icrawler.builtin import GoogleImageCrawler

google_crawler = GoogleImageCrawler(storage={'root_dir':'name'})
google_crawler.crawl(keyword = 'searching word',max_num=150)
```
크롤링 코드

[https://teachablemachine.withgoogle.com/](https://teachablemachine.withgoogle.com//) 

teachable machine으로 이미지 학습
<br>

# 웹 엔진 최적화 하는 법


```bash
<meta name="naver-site-verification" content="Arbitrary value" />
<meta name="google-site-verification" content="Arbitrary value" />
```
각각의 사이트에 들어가서 인증을 받는다.

<h2>sitemap.xml</h2>

```bash
<?xml version="1.0" encoding="UTF-8"?>
<urlset
      xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"
      xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
      xsi:schemaLocation="http://www.sitemaps.org/schemas/sitemap/0.9
            http://www.sitemaps.org/schemas/sitemap/0.9/sitemap.xsd">
<!-- created with Free Online Sitemap Generator www.xml-sitemaps.com -->


<url>
  <loc>"your web address"</loc>
  <lastmod>2022-07-26T09:32:23+00:00</lastmod>
</url>


</urlset>
```


<h2>robots.txt</h2>

```bash
User-agent: *Allow:/
Sitemap: "your web address"/sitemap.xml

```

이런 식으로 웹사이트 코드 폴더 추가 후 네이버 [서치어드바이저](https://searchadvisor.naver.com/),
구글 [서치콘솔](https://search.google.com/search-console/welcome)에서 웹 엔진 최적화를 해주면 된다.



