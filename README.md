# mermaidtest

## カップ麺の作り方

```mermaid
stateDiagram-v2
  direction TB
  s1 : 初期状態
  s2 : フタが開いた状態 
  s3 : お湯が入った状態
  s4 : フタが閉まった状態
  s5 : 食べられる状態
  
  s1 --> s2
  s2 --> s3
  s3 --> s4
  s4 --> s5
```
