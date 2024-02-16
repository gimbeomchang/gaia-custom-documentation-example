# 01\_세일즈홈 > 03\_상품상세

## 변수 데이터

| 변수명    | 타입    | 연결한 appName/ServiceName | 설명  |
| --------- | ------- | -------------------------- | ----- |
| variable1 | ObjName | -                          | desc1 |
| variable2 | string  | -                          | desc2 |
| variable3 | string  | appName/serviceName        | desc3 |

<!--
- UX Studio 에서 variable1 의 이름은 f4_01_03_variable1 으로 지정한다.
- 원시 타입이 아닌 경우 Gaia Studio 에서 정의한 오브젝트 타입명을 기록한다.
- 변수 데이터가 BX 서비스에 매핑된 경우 appName/serviceName 을 기록한다.
-->

## 커스텀 컴포넌트

| 커스텀 컴포넌트 명 | 변수 데이터          | 설명  |
| ------------------ | -------------------- | ----- |
| comp1              | -                    | desc1 |
| comp2              | variable1            | desc2 |
| comp3              | variable2, variable3 | desc3 |
| comp4              | f4_07_01_variable1   | desc4 |

<!-- 외부 페이지에서 정의한 변수 데이터를 기입하는 경우, prefix 까지 붙여서 표기한다. (예) f4_07_01_variable1
 -->

## 커스텀 코드

| 커스텀 코드 명 | 이벤트 타입 | 변수 데이터          | 설명  |
| -------------- | ----------- | -------------------- | ----- |
| code1          | Focus       | -                    | desc1 |
| code2          | Click       | variable1            | desc2 |
| code3          | Mount       | variable2, variable3 | desc3 |
| code4          | UnMount     | f4_07_01_variable1   | desc4 |

<!--
- UX Studio 에서 code1 의 이름은 f4_01_01_code1 으로 지정한다.
- 외부 페이지에서 정의한 변수 데이터를 기입하는 경우, prefix 까지 붙여서 표기한다. (예) f4_07_01_variable1
 -->
