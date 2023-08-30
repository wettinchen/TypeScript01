## TypeScript 01
## Chapter 01: Starter Lesson
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 TypeScript 資源
https://github.com/gitdagray/typescript-course

### Dave Gray 的 TypeScript 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6NS8GXt5nPrcYpust89zq_b&si=8IJALfXOcur2OO_K

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept offline
###  1. Intro
        教學影片開頭和介紹

###  2. Welcome

###  3. What is TypeScript?
        https://www.typescriptlang.org/
    
###  4. Who Created TypeScript?
        Anders Hejlsberg

###  5. Stackoverflow Developer Survey Results
        https://survey.stackoverflow.co/2023/#most-popular-technologies-language

###  6. Course Prerequisites
        JavaScript
    
###  7. Developer Tools You Need
        (1)下載安裝 Visual Studio Code
        (2)下載安裝 node.js
    
###  8. Install TypeScript
        在 terminal 輸入 npm i typescript -g

###  9. Compile Your First TS File
        (1)新增 index.html
        (2)新增資料夾 css
        (3)新增 main.css，修改 background-color 為黑色
        (4)匯入 main.css
        (5)新增 main.ts
        (6)宣告 username，在控制台載入結果
        (7)在 terminal 輸入 tsc main.ts
        (8)匯入 main.js

### 10. The watch flag
        (1)修改 username
        (2)在 terminal 輸入 tsc main.ts -w

### 11. tsconfig settings
        (1)新增資料夾 src
        (2)新增資料夾 build
        (3)移動 index.html, css 資料夾至 build 資料夾
        (4)移動 main.ts 至 src 資料夾
        (5)在 terminal 輸入 tsc --init
        (6)修改 "rootDir" 路徑為 "./src"
        (7)修改 "outDir" 路徑為 "./build/js"
        (8)在 terminal 輸入 tsc -w
        (9)新增 test.ts
        (10)宣告 test

### 12. tsconfig target
        "target" 可以設定 JavaScript 版本為 "es2016" 或其他版本

### 13. Deleting files
        刪除 test.ts 不會同時刪除 test.js

### 14. tsconfig include
        在最外圍資料夾新增 root.ts 會同時新增 root.js
        "include": ["src"]

### 15. Statics Types vs Dynamic Types
        (1)修改 main.js 匯入路徑
        (2)宣告 a, b, c
        (3)在控制台載入 a / b
        (4)在控制台載入 c * b
        (5)宣告 a:number, b:string, c:number
        (6)宣告 a:number, b:number, c:number

### 16. noEmitOnError flag
        (1)設定 "noEmitOnError": true
        (2)在 terminal 輸入 tsc --noEmitOnError -w