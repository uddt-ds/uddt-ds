
</div>

<div align=right>
  
[![Tech Blog Badge](https://img.shields.io/badge/tech%20blog-255F38?style=flat-square&color=255F38)](https://uddt.tistory.com/)

</div>

# Focus Me 👋  

아직 소개할 것이 없는 자기소개입니다

---

## About me
```swift
import Foundation

struct Member {
    let name: String
    let developmentFields: [String]
    let languages: [String]
    let collaborationTools: [String]
    let interests: [String]
    let history: [String]
}

let daseong = Member(
    name: "다성",
    developmentFields: ["iOS"],
    languages: ["Swift"],
    collaborationTools: ["Slack", "Notion"],
    interests: ["사진", "음악", "AI"]
    history: ["스파르타 코딩클럽(25. 02. 03 ~ 25. 07. 10)"]
)

print("안녕하세요! 저는 \(daseong.name)입니다.")
