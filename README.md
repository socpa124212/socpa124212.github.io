# socpa124212.github.io

이 프로젝트는 github blog를 html로 구현하는것입니다

see [DEMO] (https://socpa124212.github.io/)

github flavored markdown은 수식 표현을 제공합니다.

예를 들면,

### binet formula

$$F_n=\dfrac{\left(\dfrac{1+\sqrt{5}}{2}\right)^n-\left(\dfrac{1-\sqrt{5}}{2}\right)^n}{\sqrt{5}}$$

or

```math
F_n=\dfrac{\left(\dfrac{1+\sqrt{5}}{2}\right)^n-\left(\dfrac{1-\sqrt{5}}{2}\right)^n}{\sqrt{5}}
```
## 설치하는 법

```shell
$ git clone {addr}
$ cd {repo name}
# pip install -r requirements.txt
```

# 시작하는 법

```shell
$ python main.py
```

# 기능 설명
```python
def checker(answer, guess): -> bool
	if guess == answer:
		print("correct")
		return True
	else :
		print('Wrong')
		return False
```


