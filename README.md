[Uploading README.md…]()
# 배포 방법 (GitHub Pages)

이 폴더 구조 그대로 레포에 업로드해야 함 (이미지 경로가 상대경로 `img/...`라서 폴더째로 유지 필요):

```
(레포 루트)
├── index.html
└── img/
    ├── finda-list.png
    └── finda-compare.png
```

1. GitHub에서 새 레포 생성
2. "Add file → Upload files"로 index.html과 img 폴더(안의 두 이미지 포함) 함께 업로드
   - 드래그 앤 드롭 시 폴더째로 끌어놓으면 img/ 구조가 유지됨
3. 레포 Settings → Pages → Source를 "Deploy from a branch" → `main` / `/(root)` 로 설정
4. 1~5분 후 https://<username>.github.io/<레포명>/ 에서 접속 가능
