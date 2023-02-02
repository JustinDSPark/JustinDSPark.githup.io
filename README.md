# JustinDSPark.githup.io

This project is all about converting github into html

See [Demo](https://JustinDSPark.github.io)

## 설명

github flavored markdown은 수식 표현을 제공한다.

예를 들면,

## Binet's formula

$F_n=\dfrac{\left(\dfrac{1+\sqrt{5}}{2}\right)^n-\left(\dfrac{1-\sqrt{5}}{2}\right)^n}{\sqrt{5}}



## 설치하는 법

'''shell
$ git colne {addr}
$ cd {repo name}
$ pip install -r requirements.txt
'''

## 시작하는 법

'''shell
$ python main.py
'''

## 기능 설명

### 정답 확인하는 함수
'''python
def checker(anser : int, guess: int) -> bool:
    if guess == answer:
	print('Correct!')
	return True
    else:
	print('Wrong!')
	return False
'''


'''


## 더 많은 정보

