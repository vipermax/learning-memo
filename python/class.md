# Constructor
```python
class Point:
    def __init__(self, x, y):
        self.x, self.y = x, y
```

# Class method - インスタンス化することなく使えるメソッド（クラス変数にアクセス可）
```python
class Point:
    @classmethod
    def polar(cls, r, theta):
        return cls(r * cos(theta),
                   r * sin(theta))
```
