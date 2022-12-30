```swift
// AboutKevinController.swift

import Kevin

class About: Me{
    @objc func getLanguages(){
          return [
                "Swift",
                "Python",
                "Javascript",
                "C++"
          ]
    }
    @objc func getExperiences(){
          return [
                "Software Engineer",
                "iOS Developer",
                "Data Scientist"
          ]
    }
    let interest = ["Hackathons", "Competitive Programming", "AI/Robotics Competitions", "Any Tech Stuff lol"]
}
```
