<div align=right>
  
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fuddt-ds%2Fuddt-ds&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

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
}

let daseong = Member(
    name: "다성",
    developmentFields: ["iOS"],
    languages: ["Swift"],
    collaborationTools: ["Slack", "Notion"],
    interests: ["사진", "음악", "AI"]
)

print("안녕하세요! 저는 \(daseong.name)입니다.")
