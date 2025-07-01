# 🔺 Higher or Lower Game (Followers Edition)

A fun console-based game where you compare celebrities and guess who has more followers on social media.

---

## 🎮 How to Play

- You're shown two famous people (or brands).  
- Each round, choose who you think has more followers:  
  Type **'A'** or **'B'**  
- If you're correct, your score increases — and the game continues.  
- A wrong guess ends the game with your final score.

---

## 📦 Features

- Uses real-like sample data (`game_data`)  
- Dynamic ASCII logo and VS art  

<p align="center">
  <img src="https://github.com/user-attachments/assets/e87b2bbe-f562-4f8c-a086-d26db6e09e45" width="250" alt="Game Logo" />  
  <img src="https://github.com/user-attachments/assets/eccabf36-0c10-4c2f-8e8c-add81729dec4" width="250" alt="VS Art" />
</p>

- Randomized comparisons every round  
- Score tracking & feedback  

---

## 🧰 Requirements

- Python 3.x  
- Two local files:  
  - `art.py` – contains logo and VS ASCII art  
  - `game_data.py` – contains a list named `data` with dictionary entries like:

```python
data = [
    {
        'name': 'Cristiano Ronaldo',
        'follower_count': 215,
        'description': 'footballer',
        'country': 'Portugal'
    },
    # ... more entries ...
]
```
## 🧠 Sample Output

Compare A: Cristiano Ronaldo, a footballer, from Portugal.

vs

Against B: Ariana Grande, a pop singer, from the United States.

Who has more followers? Type 'A' or 'B': a

You're right! Current score: 1
