# ROI 기반 MSA 선택적 전환 결정 기법
# ROI Based MSA Selective Transition Decision Technique

<img width="979" height="730" alt="실험 구성도" src="https://github.com/user-attachments/assets/dbc15836-5f8d-4cc3-8b96-15529e6236d4" />

[논문 초록]
모놀리식 시스템을 마이크로 서비스 아키텍처(Microservice Architecture, MSA)로 전환할 때 발생하는 성능 저하와 개발 비용 증가 문제는 실무에서 중요하다. 기존 경험이나 일괄적 분리 방식은 구체적인 성능·비용 평가가 부족하므로 API별로 정량적 우선 판단 기준이 필요하다. 본 논문은 응답시간 개선과 코드라인 비용을 통합 평가하는 ROI 기반 API 선택적 분리 기법을 제안한다. 수식은 ‘(DDD 응답시간 - MSA 응답시간) / (MSA 코드라인 - DDD 코드라인)'으로 정의하여, 수식의 결괏값으로 API별 분리 권고·금지를 판정한다. 본 논문은 대표 5개 API를 대상으로 부하 테스트를 수행하여 제안한 기법의 타당성을 검증하였다. 선택적 전환은 일괄 전환 대비 성능 저하와 개발 비용 위험을 효과적으로 감소시킬 수 있으며, API별 성능 및 비용의 정량적 비교를 통해 제안 기법이 실질적 소프트웨어 아키텍처 설계 의사결정에 이바지함을 실험으로 입증했다.

[DDD, MSA 개발 환경 및 세부 설정]
- Java 17, IntelliJ IDEA
- MySQL Workbench
- Docker Desktop
- Spring Boot / Maven
* AI 활용하여 코드 작성
