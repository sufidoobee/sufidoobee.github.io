# 🕹️ Python Game Making with Pygame Zero

🚀 **A beginner-friendly website for learning Pygame Zero, experimenting with code, and copying game examples!**

### 🔗 **Live Website:** [sufidoobee.github.io](https://sufidoobee.github.io/)

---

### **📌 Features**
- ✅ **Learn Pygame Zero** step by step  
- ✅ **Copy Game Code** – Copy the code to your clipboard  
- ✅ **Cool Animations & Tech-Styled Cursor**  
- ✅ **Simple & Responsive UI**  

---

### **💡 Game Examples**

#### **Moving Ball Game**
```python
import pgzrun

WIDTH = 500
HEIGHT = 400
ball = Actor("ball", (250, 200))

def draw():
    screen.clear()
    ball.draw()

def update():
    ball.x += 2
    if ball.x > WIDTH:
        ball.x = 0

pgzrun.go()
