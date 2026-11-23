# Session Report — Lab 07

**Тестер:** Оюунсүрэн Мөнхзолбоо (B210910878)  
**Огноо:** 2026-10-19  
**Хугацаа:** 20:26–21:26 (60 минут)  
**Mission:** Уншлагын жагсаалт аппын чанарыг шинжлэх  
**Charter:** [charter.md](charter.md)

## Тэмдэглэл (он цагийн дарааллаар)

Доорх тэмдэглэл нь тестийн үеэр бичсэн эх хувилбар бөгөөд зөвхөн хугацааг сессийн эхэлсэн 20:26 цагаас тооцож, HH:MM хэлбэрт хөрвүүлсэн. Бусад агуулгыг өөрчлөөгүй.

```text
Test 20:26 ees ehlew (HH:MM) delgetsnii baruun deed taliin timeriig ashiglav
20:26 ehnii 10ni seconded 2 aldaa ajiglagdav.
      ehnii bug 3 nom hargdaj bgac niit nom 4
20:26 bug 2 ustgah tovch bas nogoon bn
20:28 bug 3 nom nemeh deer darnguut aldaa zaahgu shuud how hoosn nemegdej bn
20:31 bug 4 nomiin on g 50 gj hiisn 22000 gj hiisn aldaa zaasangui shuud burtgeed awlaa
20:33 bug 5 clean code gdg nom bgac bugdiin jijgeer bicsn bolhoor garj irsngui
20:37 bug 6 ta ijilheb Robert gj zohiolch bga bolovch bas; jijgeer bcsn bolhoor garj irsngui
20:42 bug 7 API d buruu json ilgeehed HTTP/1.1 200 OK {"result":"OK"} gj garj irsn uug ni 400 bad request garj irh ystoi
20:48 bug 8 bug 3 tai ijilhen apid zowhn tittle talbartai JSON ilgeehed auther bolon year\on bhgy bolovch HTTP 201 Created, {"result":"OK","id":12} butsaasan
20:53 bug 9 year buyu on iig anzaarahad 2,008 bn 2008 bsh on jil taslalgui bh ystoi
20:59 bug 10 mash urt ner bichihed table iig urt bolgood delgetsnees gargasn
21:05 bug 11 Ном нэмэгдлээ ged nom nemeegui uydch baij baidg ustgasanch baidg test
21:08 bug 12 baigaa nomiig nembel dublicate hiiged aldaa zaasngu
21:13 bug 13 year\on deer 2,008 gj oruulahad NaN zger 2008 oruulhad hewiin
21:15 bug 13 tai ijil ghde year\on deer usg biched nomiig oruulsn NaN gj garj irsn aldaa zaah ystoi baih
21:18 nemeh jagsaaltad ali ni on ali ni auther ali ni ner todorhoilj ogsn zuil bhgui zgerl 3 ni husnegt
21:20 2200.5 gej oruulahad huleen awsn Aldaa zaah ystoi bsn
21:22 anhnaasaa baisn 3 ni nomiig ustgasan zuw zger ustgasn buh nomiig ustgahad 1 gj uldsn36
21:24 ustgah towch yroosoo confirm buyu lawlaj asuuhgui bgaa tiim ym baih ystoi gj bodoj bn
21:26 duusav
```
 

## Саадууд (Issues)
- Зарим алдааг дахин шалгахад серверийг шинээр эхлүүлэх шаардлагатай.
- Урт гарчиг хүснэгтийн бүтцийг эвдэж, бусад баганыг дэлгэцээс гаргасан.
- API-ийн алдааг шалгахад HTTP статус болон хариуг тусад нь хадгалах шаардлагатай болсон.
- Нэг screenshot сессийн төгсгөлөөс ойролцоогоор нэг минутын дараа авсан.
## Цагийн задаргаа
- Setup: 5%
- Тест дизайн ба гүйцэтгэл: 65%
- Согог судлах, нотолгоо цуглуулах: 30%
Нийт: 100%

