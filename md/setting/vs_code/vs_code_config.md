---
layout: default
---
- 기본설정 > 설정
```
{
    // js 파일 만들 때 javascriptreact 로 되게 하기
    "files.associations": {
        // "*.js": "javascriptreact"
     },
     // Explorer 에서 안 보일 파일
     "files.exclude": {
        "**/.git": true,
        "**/.svn": true,
        "**/.DS_Store": true,
        // "**/node_modules": true,
        "**/.idea": true,
        "**/.vscode": false,
        "**/yarn.lock": true,
        "**/tmp": true
    },
    // 검색대상 제외
    "search.exclude": {
        "**/node_modules": true,
        "**/bower_components": true,
        "**/.git": true,
        "**/.DS_Store": true,
        "**/tmp": true,
        "**/coverage": true,
        "**/build": true,
        "**/Pods": true,
        "**/*.xcodeproj": true,
        "**/*.xcworkspace": true
    }
}
```
