# Django

<font color="#ffff00">**Django란** Python 으로 작성된 고수준 웹 프레임워크다.</font> 신속한 개발과 깔끔한 코드 스타일을 장려하며, 재사용 가능한 모듈로 구성되어있는 것이 특징이다. 보안 기능이 내장되어 많은 시간과 노력을 절약할 수 있고, <font color="#92d050">DRY 원칙 (Don't Repeat Yourself)</font> 을 준수하는 것이 특징이다.


Django는 기본적으로 MVC 패턴을 채택하고 있다. 하지만 완벽한 MVC가 아닌, 이를 약간의 변형을 가미해 MTV 라는 패턴 ( Model - Template - View ) 사용한다.

- Model : 데이터베이스 구조를 정의, 데이터베이스와 상호작용
- Template : 사용자에게 표시되는 HTML을 생성 
- View : 비즈니스 로직과 모델, 템플릿을 연결하는 역할.

# 가상 환경 설치 및 활성화 
```
python -m venv myenv // 가상 환경 생성
source myenv/bin/activate //활성화 
```
