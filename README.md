```
📂 project/                          # 프로젝트 폴
    └── 📂 Front-end           # 프론트엔드 폴더
        └── Chatbot.tsx       # 챗봇 페이지
    └── 📂 Back-end           # 백엔드 폴더
        └── 📂 route       # 사용자 flask 폴더
            └── user.py       # 사용자 flask 코드(user Blueprint)
        ├── init.py       # create_app()(user Blueprint, api Blueprint)
        └── app.py       # app.run
    └── 📂 RAG           # RAG 폴더
        └── api.py      # 챗봇 flask 코드(api Blueprint)
        └── app.py      # 챗봇 구현 코드(app.run)
```
