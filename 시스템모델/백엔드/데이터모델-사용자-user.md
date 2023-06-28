# column

id: user 테이블 유니크 아이디, 사용자 
name: 사용자 이름
email: 이메일
position: 직책
department: 부서
role: 권한
enter_date: 입사일
is_leave: 퇴사여부

# relation

하나의 User는 다수의 Vacation을 가진다.
- User.hasMany(Vacation)