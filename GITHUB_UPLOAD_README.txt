기공자원 GitHub Pages 최종 업로드 패키지

1) 이 ZIP을 PC에서 압축 해제합니다.
2) GitHub의 gigong-resource 저장소에서 Add file > Upload files를 누릅니다.
3) '기공자원_GitHub_Pages_최종' 폴더 자체가 아니라,
   폴더 안의 파일/폴더 전체를 저장소 최상단(root)에 업로드합니다.
4) 업로드 후 Commit changes.
5) Settings > Pages:
   Source = Deploy from a branch
   Branch = main
   Folder = /(root)
6) 처음에는 GitHub Pages 임시 주소에서 홈페이지가 정상 표시되는지 확인합니다.

포함:
- index.html : 기공자원 랜딩페이지
- CNAME : 기공자원.kr 커스텀 도메인용
- .nojekyll : 정적 파일 그대로 배포
- robots.txt / sitemap.xml : 검색엔진용
- admin/ : 관리자 CMS 화면 기반
- content/ : 관리자용 콘텐츠 데이터
- assets/uploads/ : 관리자 이미지 업로드 폴더

주의:
- CNAME이 포함되어 있으므로 GitHub Pages 설정 후 Custom domain에
  xn--ob0b9wn45c6va.kr 가 표시될 수 있습니다.
- 아직 DNS를 GitHub로 바꾸기 전이라면 기공자원.kr은 바로 GitHub로 연결되지 않습니다.
- 관리자 CMS는 GitHub OAuth 설정이 끝나야 로그인/저장이 실제 작동합니다.
