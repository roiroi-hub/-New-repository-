```mermaid
flowchart LR
    A([Start]) --> B[SWIFTメッセージ受信]
    B --> C[スクリーニング<br>(制裁・PEPs・Adverse Media)]
    C --> D[顧客確認<br>(KYC情報照合)]
    D --> E[疑わしい取引検知<br>(モニタリング)]
    E --> F[入金処理<br>(二重承認)]
    F --> G[STR判断・報告]
    G --> H([End])
```
