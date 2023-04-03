# ezTransWeb-omni
이지트랜스를 웹 API 형태로 쓰기 위해 만들어진 Python 스크립트입니다. [원본 ezTransWeb](https://github.com/HelloKS/ezTransWeb)은 [AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator)등의 사용자 정의 Endpoint 지정 가능한 번역 플러그인에 사용할 용도로 만들어졌으며 여기에 [ehnd-kor](https://github.com/stypr/ehnd-kor)에 의한 한->일 번역을 추가했습니다.

# 필수 환경
* 이지트랜스 (최소 한번 실행 필수)
* [꿀도르님 개조 Ehnd](https://blog.naver.com/waltherp38/221062272423)
* [ehnd-kor](https://github.com/stypr/ehnd-kor)
* Python 3.x (<=3.7) **32비트** 
* Flask
* Gevent
# 사용 방법
필수 환경이 다 갖춰진 상태라면, 명령 프롬프트에서 `python eztrans.py`로 실행할 수 있습니다.

기본값은 127.0.0.1을 호스트로 5000번 포트에서 동작합니다.
# 자세한 사용 방법
HOWTO.md 파일을 참고해 주세요.
# Special Thanks to
* [Ehnd](https://github.com/sokcuri/ehnd)
* [Anemone](https://github.com/sokcuri/anemone)
* [ehnd-kor](https://github.com/stypr/ehnd-kor)
