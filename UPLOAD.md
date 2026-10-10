# 깃허브 업로드 안내

압축을 푼 뒤 **`github-gugak-curation` 폴더 안의 파일과 하위 폴더를 함께** 저장소에 올리세요. `README.md`에서 소개 글과 일러스트, 상세 문서 링크를 볼 수 있습니다.

```text
github-gugak-curation/
├── README.md
├── UPLOAD.md
├── assets/
│   ├── illustrations/          # AI 일러스트 6장
│   └── photos/                 # 공연 사진 2장
└── docs/
    ├── unit-plan.md            # 상세 수업설계안
    ├── worksheet.md            # 학생 활동지
    ├── matrix-template.md      # 빈 시대 비교표
    ├── photos.md               # 사진·공식 감상 자료
    ├── sources.md              # 출처·편집 기록
    └── illustration-prompts.md # 최종 생성 프롬프트
```

1. 새 저장소라면 폴더 안의 내용을 최상위에 올립니다.
2. 기존 음악 산업 탐구 자료와 함께 보관한다면 `gugak-curation/` 하위 폴더에 내용 전체를 넣습니다. 기존 README 위에 덮어쓰지 않습니다.
3. 업로드 후 해당 `README.md`를 열어 사진·그림·상세 문서 링크를 확인합니다.

ZIP 하나만 올리면 내용이 자동으로 펼쳐지지 않으므로 압축을 푼 파일을 올립니다. 별도 설치나 사이트 빌드가 필요 없는 Markdown 문서 묶음입니다.

이미지 파일명을 바꾸면 문서 안의 상대경로도 함께 고칩니다. 사진을 사용할 때는 `docs/photos.md`의 저작자·출처·라이선스 표시를 함께 유지합니다. 학생 답안이나 외부 서비스 실행 기능은 포함하지 않았습니다.
