# Back-end-roadmap λ°λΌκ°κΈ°πͺ΄
## μ°Έκ³ μ© λ‘λλ§΅
[2023 μ λ‘λ² μ΄μ€ λ‘λλ§΅](https://zero-base.co.kr/event/media_BE_school_roadmap)   
[2023 μ λ‘μ΄λ λ°±μλ λ‘λλ§΅](https://drive.google.com/file/d/1_9zjALIVisho4xIZzmU9W6NIam14UHrX/view)   

---
π½ μΆμ² : https://imsoncod.tistory.com/24   
π½ μλ³Έ : https://roadmap.sh/backend
<br>

![λ°±μλ λ‘λλ§΅](https://blog.kakaocdn.net/dn/bq03dY/btrnCzNDlUE/EQPcSTH1TGR50KCBsnC5K1/img.png)

---

## Internet

### [μΈν°λ·μ΄λ?](https://namu.wiki/w/%EC%9D%B8%ED%84%B0%EB%84%B7)
- Internetional Networkμ ν©μ±μ΄λ‘, μΈν°λ· νλ‘ν μ½ μ€μνΈ( [TCP](https://ko.wikipedia.org/wiki/%EC%A0%84%EC%86%A1_%EC%A0%9C%EC%96%B4_%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C) / [IP](https://ko.wikipedia.org/wiki/%EC%9D%B8%ED%84%B0%EB%84%B7_%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C) )λ₯Ό κΈ°λ°μΌλ‘ νμ¬ μ  μΈκ³μ μΌλ‘ μ°κ²°λμ΄μλ μ»΄ν¨ν° λ€νΈμν¬ ν΅μ λ§μ μΌμ»«λ λ§μ΄λ€.<br>
- [νλ‘ν μ½ (Protocol)](https://ko.dict.naver.com/#/entry/koko/066279eccf464602bd4e87f2d9c6bc81) : μ»΄ν¨ν°μ μ»΄ν¨ν°κ°μ μ νΈ μ‘μ μ μμ, λ°μ΄ν°μ ννλ², μ€λ₯ κ²μΆλ² λ±μ λ°μ΄ν°λ₯Ό μνν μ£Όκ³  λ°κΈ° μν κ·μ½μ΄λ€.
  - TCP (Transmission Control Protocol) : μ μ‘ μ μ΄ νλ‘ν μ½. ν΄λΌμ΄μΈνΈμ μλ² κ°μ μ λ’°μκ² μμ μ μΌλ‘ μμλλ‘ μλ¬μμ΄ μ£Όκ³  λ°μ μ μλ€. μ§μ­λ€νΈμν¬(LAN) νΉμ κ΄μ­λ€νΈμν¬(WAN)μμ μνν ν΅μ μ κ°λ₯νλλ‘ νκΈ° μν ν΅μ κ·μ½(Protocol) μΌλ‘ μ μνλ€.
  - IP (Internet Protocol)) : μΈν°λ· νλ‘ν μ½. λ€νΈμν¬ μμ μ»΄ν¨ν° κ³ μ  μ£Όμμ΄λ©°, μ΄ 4λ°μ΄νΈλ‘ λμ΄ μλ€.
### [μΈν°λ·μ μλμλ¦¬](https://developer.mozilla.org/ko/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work)
![λ¨μΌλ€νΈμν¬](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-1.png)   
<br>
μμ μ λ κ°μ μ»΄ν¨ν°κ° ν΅μ μ΄ νμν  λ, μ μ  μΌμ΄λΈμ μ΄μ©ν΄ λ κ°μ μ»΄ν¨ν°λ₯Ό μ°κ²°ν΄ ν΅μ νμλ€.<br>
νμ§λ§ μ¬λ¬ μ»΄ν¨ν°λ₯Ό μ μ μΌμ΄λΈλ‘ νλνλ μ°κ²°νλλ°μ λΆνΈνκ³  νκ³κ° μκΈΈ μ λ°μ μλ€.<br><br>
![μ¬λ¬μ»΄ν¨ν°λΌλ©΄](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-2.png)   
<br>
μ΄λ¬ν λ¬Έμ λ₯Ό ν΄κ²°νκΈ° μν΄ λΌμ°ν°λΌκ³ νλ νΉμν μν μ»΄ν¨ν°μ μ°κ²°νκ² λλ€.<br><br>
![κ·Έλ λ€λ©΄μ΄λ κ²](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-3.png)
<br>
Aμ»΄ν¨ν°μ Bμ»΄ν¨ν°μ ν΅μ ν  λ Cμ»΄ν¨ν°μ κ°μ§ μκ² νλ©΄ λ¨μΌ νλ¬κ·Έμ 10κ° νλ¬κ·Έκ° μλ νλμ λΌμ°ν°κ° νμνλ€.<br><br>
![νμ₯ κ°λ₯](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-5.png)
<br>
νμ§λ§ λ¨Ό κ³³κΉμ§λ ν΅μ μ΄ λΆκ°λ₯ ν΄, μ ν(μ μΈκ³μ μ°κ²°λμ΄μκΈ° λλ¬Έμ)λ₯Ό μ΄μ©ν μ νμμ€λ‘ μ²λ¦¬ν  μ μλ μ λ³΄λ‘ λ°κΏμ£Όλ λͺ¨λμ΄λΌλ νΉμμ₯λΉκ° νμνλ€.<br>
λ€νΈμν¬λ₯Ό μ νμμ€μ μ°κ²°νκ² λλλ° κ·Έκ²μ μΈν°λ· μλΉμ€ μ κ³΅ μμ²΄ (Internet Service Provider, ISP)μ μ°κ²°νλ€.<br>
![ISP](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-7.png)<br>
μ°λ¦¬κ° μκ³  μλ SKT, KT, LG U+μμ κ΄λ¦¬νκ² λλ€.
### [HTTPλ?](https://ko.wikipedia.org/wiki/HTTP)
- HyperText Transfer Protocol, μΈν°λ·μμ λ°μ΄ν°λ₯Ό μ£Όκ³  λ°μ μ μλ νλ‘ν μ½μ΄λ€.
- νμ΄νΌνμ€νΈλ₯Ό λΉ λ₯΄κ² μ£Όκ³ λ°κΈ° μν΄ νλ‘ν μ½μ μΌμ’μΌλ‘ μλ²μ ν΄λΌμ΄μΈνΈ μ¬μ΄μμ μ΄λ»κ² λ©μΈμ§λ₯Ό κ΅νν μ§ μ ν΄λμ κ·μΉμ΄λ€.
- μμ²­(Request)κ³Ό μλ΅(Response)μΌλ‘ κ΅¬μ±λμ΄μλ€. μ£Όμμ http://κ° HTTPνλ‘ν μ½μ μ΄μ©ν΄ μ λ³΄λ₯Ό κ΅ννκ² λ€λ νμμ΄λ€.
- HTTP νλ‘ν μ½ κΈ°λ°μΌλ‘ HTMLλ‘ μμ±λ νμ΄νΌνμ€νΈλ₯Ό [μΉλΈλΌμ°μ ](https://ko.wikipedia.org/wiki/%EC%9B%B9_%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80)λΌλ μμ©νλ‘κ·Έλ¨μΌλ‘ μ½μ μ μκ² νλ κ΅¬μ±μΌλ‘ λμ΄μλ€.
- [www(World Wide Web μλμμ΄λμΉ)](https://ko.wikipedia.org/wiki/%EC%9B%94%EB%93%9C_%EC%99%80%EC%9D%B4%EB%93%9C_%EC%9B%B9) : μΈν°λ·μ μ°κ²°λ μ»΄ν¨ν°λ₯Ό ν΅ν΄ μ¬λλ€μ΄ μ λ³΄λ₯Ό κ³΅μ ν  μ μλ μ  μΈκ³μ μΈ μ λ³΄κ³΅κ°μ΄λ€. webμ κ±°λ―Έμ€μ²λΌ μ?μΈ μ λ³΄κ³΅κ°μ λ»νλ€κ³  νλ€.
### λΈλΌμ°μ μ κ·Έ μλμλ¦¬
