# ***Artiom Domkin***

![Artiom Domkin Ava](https://i.imgur.com/93SHhZx.jpg)



## **Contact information:**

|    |    |
|----|----|
|**Phone:**|Samsung A32|
|**Email:**|artem.domkin@mail.ru|
|**GitHub:**|NeGomik|
|**Telegram:**|@NeGomik|
|**Discord:**|NeGomik#1187|

---

## **Briefly About Myself:**

I am 21 years old.

Very informative story about my achievements and goals for my future life.


I quickly learn new information, I like to understand a topic that I don’t understand, well, a little bit of the rest.

---

## **Skills and Proficiency:**

1. Python:
   + PyQt;
   + Django;
   + Flask;
   + Tornado.
2. JavaScript (only start);
3. HTML, CSS;
4. Photoshop;
5. VS Code, Atom, Sublime Text.

## **Code example:**

``` python
def initUI(self): 
#Перемещение окна 
    x1=0
    x=0
    a=0
    a1=0
    while a != x or a1 != x1:
 
    if a != x or a1 != x1:
    if a != x:
    a = a + 1
    if a1 != x1:
    a1 = a1 + 1
#___________________________
 
#Прорисовка окна
    self.setAttribute(Qt.WA_TranslucentBackground, True) #Удаление заднего фона
    self.move(a, a1)
    hbox = QHBoxLayout(self)
    pixmap = QPixmap("icon/img_rima.png")
    lbl = QLabel(self)
    lbl.setPixmap(pixmap)
    hbox.addWidget(lbl)
#__________________________
 
#Кнопка
    self.btn = QPushButton(self)
    self.btn.move(10, 190)
    self.btn.clicked.connect(self.showdialog)
#__________________________
 
#Отображение окна
    self.show()
    sleep(0.001)
#__________________________
 
#Дублируется в случае если цикл не сработал
    hbox = QHBoxLayout(self)
    self.setAttribute(Qt.WA_TranslucentBackground, True)
    pixmap = QPixmap("icon/img_rima.png")
    lbl = QLabel(self)
    lbl.setPixmap(pixmap)
    hbox.addWidget(lbl)
    self.btn = QPushButton(self)
    self.btn.move(10, 190)
    self.btn.clicked.connect(self.showdialog)
    self.move(a, a1)
    self.show() 
```

---
## **Courses:**

Before that, I took courses on website layout in HTML, CSS, JavaScript, and I also learned a lot of lessons on YouTube. 

---
## **Work experience:**

I have freelancing experience. Wrote about simple sites.

---

## **Languages:**

+ English - A1
+ Russian - Nativ
+ Belorussian - Nativ
