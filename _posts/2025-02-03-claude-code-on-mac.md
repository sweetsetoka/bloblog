---
layout: default
title: "Claude Code 맥북에서 사용하기"
date: 2025-02-03
---

# {{ page.title }}
<small>{{ page.date | date: "%Y-%m-%d" }}</small>


Claude Code는 Anthropic에서 만든 AI 코딩 어시스턴트입니다. 터미널에서 직접 사용할 수 있어 개발 워크플로우에 자연스럽게 녹아듭니다.

## 설치하기

Node.js가 설치되어 있다면 npm으로 간단히 설치할 수 있습니다.

```
npm install -g @anthropic-ai/claude-code
```

설치 후 `claude` 명령어로 실행하면 됩니다. 처음 실행 시 Anthropic 계정 인증이 필요합니다.

## GitHub 연동

Claude Code는 Git과 자연스럽게 연동됩니다. 프로젝트 폴더에서 실행하면 자동으로 Git 상태를 인식합니다. 커밋 메시지 작성, PR 생성, 코드 리뷰까지 터미널에서 바로 처리할 수 있습니다.

```
cd your-project
claude
```

## 유용한 팁

코드 수정을 요청하면 변경 사항을 미리 보여주고 승인을 받습니다. 파일 탐색, 버그 수정, 리팩토링 등 다양한 작업을 자연어로 요청해 보세요.

## 참고
https://code.claude.com/docs
