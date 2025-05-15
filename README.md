#### 주요 기능:
* 학생(도서) 등록 
    - (이름, 학번, 주소, 전화번호, 이메일, 생년월일)
* 학생(도서) 목록 조회
* 학생(도서) 정보 수정
* 학생(도서) 삭제
* 입력 데이터 유효성 검사
* Ajax 통신을 통한 REST API 호출

#### 사용된 기술:
* HTML5: 구조적인 마크업
* CSS3: 반응형 레이아웃과 스타일링
* JavaScript (ES6+): 동적 기능과 Ajax API 통신

#### 주요 특징:
* 점진적 개발 방식으로 단계별 완성
* 에러 처리 및 사용자 피드백
* 로딩 상태 표시
* 수정 모드와 등록 모드 전환
* 입력 필드별 실시간 유효성 검사(js)

### 각 Step 별 기능:
step1 - html page 작성 
step2 - form 내부의 input 과 table 에 CSS 추가
step3
    - form .css 파일로 분리하기
    - form 내부의 input에 form-group, form-gird css추가가
    - form.css 에 form 내부의 input에 form-froup, from-grid 클래스 추가하기
step4
    - javascript 코드 작성하기 시작
    - From Load Event 핸들링 하기
    - Form Submit Event 핸들링 하기기
    - 사용자가 입력한 데이터를 Form Data에 저장하기

step5
    - 입력한 데이터를 검증하는 validata

step6
    - GET /api/students 서버와 통신하는 loadStudents() 구현 fetch 함수사용
    - renderStudentTalble() 구현 table에 목록을 동적으로 출력하기
step7
    - studentData 객체 구조 변경하기 및 validate() 함수 수정
    - POST API/STUDENT 서버와 통신하는 CREAT