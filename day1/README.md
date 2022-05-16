# 안내

[DB손보_DA.png](DB손보_DA.png)


# 1. 파이썬 개발환경

[교안1-03Python_Jupyter개발환경.pdf](교안1-03Python_Jupyter개발환경.pdf)

## 개발환경

1. Python 배포본
2. Proxy 환경
3. venv, pyenv 모듈
4. Jupyter-Notebook
 

### Proxy

윈도우즈 : C:\Users\사용자명\AppData\Roaming\pip 폴더

```ini
[install]
trusted-host = pypi.org
               files.pythonhosted.org
```

- [pip proxy 사용하기](https://velog.io/@chacha/pip-proxy-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)


### `venv`

1. https://docs.python.org/3/library/venv.html
2. 파워쉘과 venv 활성화 : https://dreamlog.tistory.com/603


### pyenv 와 anaconda

pyenv 를 기반을 파이썬 환경:

 - https://github.com/pyenv-win/pyenv-win
 - https://codingcoding.tistory.com/1077


#### conda 일반명령

 - https://copycoding.tistory.com/62
 

---

# 2. Python

1. 파이썬 : [파이썬,wikipedia](https://ko.wikipedia.org/wiki/파이썬)
2. 파이썬 버전표: [파이썬 버전표,wikipedia ](https://ko.wikipedia.org/wiki/파이썬의_역사#버전_표)

#### The zen of Python


```cmd
$ python
Python 3.8.2 (default, Jul 16 2020, 14:00:26) 
[GCC 9.3.0] on linux

>>> import this
The Zen of Python, by Tim Peters
```

- 아름다운 것이 추한 것보다 낫다. (Beautiful is better than ugly.)
- 명시적인 것이 암시적인 것보다 낫다. (Explicit is better than implicit.)
- 간결한 것이 복합적인 것보다 낫다. (Simple is better than complex.)
- 복합적인 것이 복잡한 것보다 낫다. (Complex is better than complicated.)
- 수평적인 것이 내포된 것보다 낫다. (Flat is better than nested.)
- 여유로운 것이 밀집한 것보다 낫다. (Sparse is better than dense.)
- 가독성은 중요하다. (Readability counts.)
- 특별한 경우들은 규칙을 어길정도로 특별하지 않다. (Special cases aren't special enough to break the rules.)
- 허나 실용성은 순수성을 이긴다. (Although practicality beats purity.)
- 오류는 절대로 조용히 지나가지 않는다. (Errors should never pass silently.)
- 명시적으로 오류를 감추려는 의도가 아니라면. (Unless explicitly silenced.)
- 모호함을 대할때, 이를 추측하려는 유혹을 거부하라. (In the face of ambiguity, refuse the temptation to guess.)
- 명확한-- 그리고 가급적이면 유일한 -- 하나의 방법은 항상 존재한다. (There should be one-- and preferably only one --obvious way to do it.)
- 비록 그 방법이 처음에는 명확해 보이지 않을지라도[2]. (Although that way may not be obvious at first unless you're Dutch.)
- 지금 행동에 옮기는 것이 아예 안하는 것보다는 낫다. (Now is better than never.)
- 비록 아예 안하는 것이 지금 *당장* 하는 것보다 나을때도 많지만. (Although never is often better than *right* now.)
- 구현 결과를 설명하기 쉽지 않다면, 그것은 나쁜 아이디어이다. (If the implementation is hard to explain, it's a bad idea.)
- 구현 결과를 설명하기 쉽다면, 그것은 좋은 아이디어일지도 모른다. (If the implementation is easy to explain, it may be a good idea.)
- 네임스페이스를 사용하는 것은 완전 좋은 생각이다! (Namespaces are one honking great idea -- let's do more of those!)



## Jupyter Notebook

### iPython 동작

<img src='https://ipython.org/ipython-doc/3/_images/notebook_components.png' width='500'>
- https://ipython.org/ipython-doc/3/development/how_ipython_works.html


---

# 데이터 처리 프레임워크

파이썬 기반 데이터 처리 프레임워크

### 파이썬
* Python - http://python.org
* Anaconda - https://anaconda.com/

### 파이썬 개발도구

Jupyter Notebook
* Jupyter Notebook - http://jupyter.org
* Google Colab - http://colab.research.google.com

Desktop 개발환경
* PyCharm - https://www.jetbrains.com/ko-kr/pycharm
* VisualStudio Code - https://code.visualstudio.com/

### 과학계산 데이터
* NumPy - http://numpy.org
* Pandas - http://pandas.pydata.org/

### 데이터 수집
* BeautifulSoup - http://crummy.com/software/BeautifulSoup/bs4/doc/
* Requests - http://docs.python-requests.org
* 크롬 브라우저 개발자 도구
* Selenium - https://www.selenium.dev/ 

### 시각화 도구
* Matplotlib - https://matplotlib.org
* Bokeh - https://docs.bokeh.org



# Notebook 파일

- [01-00개발환경.ipynb](notebook/01-00개발환경.ipynb)
- [01-01JupyterNotebook.ipynb](notebook/01-01JupyterNotebook.ipynb)
- [01-03Basic_A.ipynb](notebook/01-03Basic_A.ipynb)
- [01-04Function_Class_A.ipynb](notebook/01-04Function_Class_A.ipynb)
- [01-05Sequence.ipynb](notebook/01-05Sequence.ipynb)
- [2-02NumPy-Tutorial_A.ipynb](notebook/2-02NumPy-Tutorial_A.ipynb)
- [2-03NumPy-Op.ipynb](notebook/2-03NumPy-Op.ipynb)


---

# 참고
 - 파이썬을 사용한 모든 곳?: https://github.com/vinta/awesome-python
 - [초보 프로그래머가 꼭 알아야 할 컴퓨터 동작 원리](https://www.hanbit.co.kr/store/books/look.php?p_code=B8337787087)
