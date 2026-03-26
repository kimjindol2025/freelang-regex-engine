# 🔍 FreeLang Regex Engine

[![Language](https://img.shields.io/badge/language-Rust-orange.svg)](#)
[![Status](https://img.shields.io/badge/status-Production%20Ready-brightgreen.svg)](#)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-kimjindol2025%2Ffreelang--regex--engine-blue?logo=github)](https://github.com/kimjindol2025/freelang-regex-engine)

**고성능 정규표현식 엔진**

## 🎯 기능

- ✅ PCRE 호환
- ✅ NFA 최적화
- ✅ 백트래킹 회피
- ✅ Named Captures

## 📊 성능

- 컴파일: <1ms
- 매칭: <10μs (평균)
- 메모리: O(n) where n = pattern length

## 🚀 예제

```freeLang
let pattern = regex("^[a-z]+@[a-z]+\\.[a-z]+$")
let is_email = pattern.matches("test@example.com")
```

## 라이선스

MIT License © 2026

---

**버전**: 1.3.0 | **업데이트**: 2026-03-16
