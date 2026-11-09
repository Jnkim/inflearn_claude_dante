# AGENTS.md

This file provides guidance to Codex (claude.ai/code) when working with code in this repository.

## 개요

인프런 "Codex" 강의 실습 예제 모음 폴더다. git 저장소가 아니며, 빌드·린트·테스트 도구나 패키지 설정(package.json 등)이 없다.

## 구조

- 실습 하나당 폴더 하나이며, 이름은 `번호.주제` 형식이다 (예: `12.FirstWebPage`).
- 새 실습을 만들 때는 이 형식으로 폴더를 새로 만들고, 다른 실습 폴더는 건드리지 않는다.

## 실습별 메모

- `12.FirstWebPage`: 외부 라이브러리 없이 HTML·CSS만으로 만든 자기소개 페이지(`index.html`). 브라우저에서 파일을 바로 열어 확인한다. 프로필 사진은 같은 폴더의 `ChatGPTDog.png`, 밝게/어둡게 전환은 `<html data-theme>` 값을 버튼으로 바꾸는 방식이다. 이메일은 fireflower@smtcube.net이고, 이름 등 나머지는 아직 예시 값(홍길동)이다.
