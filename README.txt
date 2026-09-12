AI재능나눔 LAB v7 — Supabase Auth 연결 버전

연결된 Supabase 프로젝트
- URL: https://fycfeqzqovnipyeiaewv.supabase.co
- Browser key: Publishable key 사용

이번 단계에서 실제로 연결된 것
- Supabase 회원가입
- Supabase 이메일/비밀번호 로그인
- Supabase 세션 유지
- 로그아웃
- 회원 이름은 auth user_metadata에 저장

아직 localStorage인 것
- 문제 게시글
- 참여자
- 프로젝트 내부 게시글
- 파일 이름
- 관리자 페이지

다음 단계
1) profiles 테이블 생성
2) problems 테이블 생성
3) participants 테이블 생성
4) project_posts 테이블 생성
5) RLS 정책
6) 관리자 role
7) Storage 파일 업로드

주의
- sb_secret_ 로 시작하는 Secret key는 절대로 브라우저 코드에 넣지 마세요.
- 현재 포함된 sb_publishable_ 키는 브라우저용 공개 키입니다.
