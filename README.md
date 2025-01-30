# 🕹️ Python Game Making with Pygame Zero

🚀 **A beginner-friendly website for learning Python game devlopment with Pygame Zero, experimenting with code, and learning to make games and more!**

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
