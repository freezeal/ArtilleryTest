Artillery를 이용한 부하테스트
---------------------------------
- 파이썬 활용
- YAML 구문으로 스크립트 설계(Json 형태도 가능)
- 예제 웹 서비스를 이용
- 링크 : https://github.com/freezeal/PerformanceTestAPI
- 대시보드 실행 : artillery run {실행 파일명}.yml --record --key {Artillery API Key}
- 로컬 실행 : artillery run -o {리포트 이름}.json {실행 파일명}.yml