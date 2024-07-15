# ❓🧠 React Quiz 
## Canlı versiyon : <a href="https://react-quiz-challange.netlify.app/">React Quiz</a>
- React js create app ile oluşturduğum bu uygulama,  kullanıcıların kendilerini test ederken öğreneceği, öğrenirken eğlenebileceği mini bir react quiz uygulamasıdır.

## 📝Proje Özellikleri:

- Quize başlandığında kullanıcıları 15 adet soru karşılayacaktır.
- Sorular 7.30 dakika içerisinde cevaplanmalıdır (Her soru başına ortalama 30 sn. ).
- Her doğru cevaplanan sorudan puan kazanılacaktır.
- Puanlar soru zorluğuna göre değişmektedir.
- Yanlış cevaplanan sorular puanı etkilememektedir.
- Maximum alabileceği puan 280 puandır.
- Quiz tamamlandığında toplam kazanılan puan gösterilmektedir.
- Sayfa yenilenmediği takdirde daha önce yapılan yüksek score gösterilir ve üzerine yazılır.

# 🛠Kullanılan React Özellikleri:

- Kondisyonel renderlama kullandım.
- useState yerine, birden fazla durumu aynı anda kontrol etmek için useReducer kullandım.
- Reducer fonksiyonu için switch/case yapısını kullandım.
- Başlangıç ​​durumlarından türetilmiş durumlar kullandım (Derived state).
- Api dan soruları getirmek  (fetch) için useEffect kancası kullandım.
- Prop Drilling, children prop ve component composition kullandım
- JS methodları ve özellikleri olan short circuiting, destructuring, map, reduce ve sort kullandım.
- Liste renderlamada key propu kullandım (map).
- setInterval ın yan etkilerini (side effects) temizlemek için cleanup fonksiyonu kullandım.

![React-use-Pop-Corn](public/react-quiz.gif)
