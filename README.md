<div align="center">

# ⚡ rishit@dev:~$ ./portfolio.sh

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=1500&pause=500&color=00FF41&center=true&vCenter=true&width=550&lines=welcome+to+interactive+terminal;click+commands+below+to+explore;%3E_+ready+for+execution" alt="typing" />

</div>

<div style="background: linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 100%); padding: 25px; border-radius: 12px; border: 2px solid #00ff41; font-family: 'Fira Code', monospace; box-shadow: 0 0 20px rgba(0,255,65,0.2);">

```
╭─ rishit@terminal:~$ ─────────────────────────────────────────────────╮
│                                                                     │
│  🎯 ML Engineer & Competitive Programmer                           │
│  📍 Mumbai │ 🎓 9.14 CGPA │ 🏆 1244 Pupil │ ⭐ 3-Star │ 💻 Active    │
│                                                                     │
│  Available commands: whoami | projects | skills | cp | contact     │
│  💡 Click any command below to execute                             │
│                                                                     │
╰─────────────────────────────────────────────────────────────────────╯
```

</div>

<div align="center" style="margin: 25px 0;">

[![whoami](https://img.shields.io/badge/%24%20whoami-About_Me-00ff41?style=for-the-badge&logo=terminal&logoColor=black)](.)
[![projects](https://img.shields.io/badge/%24%20ls%20projects/-Portfolio-ff6b35?style=for-the-badge&logo=folder&logoColor=white)](.)
[![skills](https://img.shields.io/badge/%24%20cat%20skills-Tech_Stack-ffd43b?style=for-the-badge&logo=code&logoColor=black)](.)
[![cp](https://img.shields.io/badge/%24%20./cp__stats-Competitive-e74c3c?style=for-the-badge&logo=trophy&logoColor=white)](.)
[![contact](https://img.shields.io/badge/%24%20contact-Connect-8b5cf6?style=for-the-badge&logo=mail&logoColor=white)](.)

</div>

---

## 💻 Terminal Session Output

<details>
<summary><kbd style="background: linear-gradient(90deg, #00ff41, #32cd32); color: #000; padding: 10px 20px; border-radius: 8px; font-weight: bold; font-size: 16px; cursor: pointer; border: none; box-shadow: 0 4px 15px rgba(0,255,65,0.3);">$ whoami</kbd></summary>

<div style="background: #0d1117; border: 2px solid #00ff41; border-radius: 10px; padding: 20px; margin: 15px 0; font-family: 'Fira Code', monospace;">

```
#!/bin/bash

# User Information Script
echo "Executing user profile query..."

USER_DATA=$(cat <<EOF
{
  "name": "Rishit Kar",
  "role": "ML Engineer & Competitive Programmer", 
  "education": "DJ Sanghvi College of Engineering",
  "cgpa": 9.14,
  "location": "Mumbai, India",
  "current_status": "Building innovative ML solutions"
}
EOF
)

# Display formatted output
echo "✅ Profile loaded successfully"
echo ""
echo "┌─ USER PROFILE ─────────────────────────────────────┐"
echo "│ Name:      Rishit Kar                            │"
echo "│ Role:      ML Engineer & CP Enthusiast           │"
echo "│ Education: DJ Sanghvi College of Engineering     │"
echo "│ CGPA:      9.14/10                               │"
echo "│ Location:  Mumbai, India                         │"
echo "│ Status:    Available for opportunities           │"
echo "└───────────────────────────────────────────────────┘"

# Current activity
echo ""
echo "🔥 Currently: Research Intern at IIT Mandi"
echo "💡 Focus: Machine Learning + Algorithm Design"
echo "🎪 Achievement: Organized CodeUncode (1200+ participants)"

exit 0
```

</div>
</details>

<details>
<summary><kbd style="background: linear-gradient(90deg, #ff6b35, #f56565); color: #fff; padding: 10px 20px; border-radius: 8px; font-weight: bold; font-size: 16px; cursor: pointer; border: none; box-shadow: 0 4px 15px rgba(255,107,53,0.3);">$ ls projects/</kbd></summary>

<div style="background: #0d1117; border: 2px solid #ff6b35; border-radius: 10px; padding: 20px; margin: 15px 0; font-family: 'Fira Code', monospace;">

```
#!/usr/bin/env python3
"""
Project Portfolio Display System
Author: Rishit Kar
"""

import os
from dataclasses import dataclass
from typing import List

@dataclass
class Project:
    name: str
    description: str
    tech_stack: List[str]
    highlight: str

def display_projects():
    """Display project portfolio in terminal format"""
    
    projects = [
        Project(
            name="reliable-udp-protocol",
            description="Custom UDP with sliding window protocol",
            tech_stack=["C", "Network Programming"],
            highlight="5.51 MB/s throughput"
        ),
        Project(
            name="pneumonia-diagnosis", 
            description="Multi-model CNN + ResNet + GNN",
            tech_stack=["TensorFlow", "Keras", "Python"],
            highlight="91.98% accuracy"
        ),
        Project(
            name="reddit-ai-dashboard",
            description="Sentiment analysis + K-Means clustering", 
            tech_stack=["NLP", "Scikit-learn", "Flask"],
            highlight="Real-time processing"
        ),
        Project(
            name="hand-gesture-control",
            description="Computer vision volume control",
            tech_stack=["OpenCV", "MediaPipe", "Python"], 
            highlight="95% accuracy"
        )
    ]
    
    print("📁 Listing project directory...")
    print("")
    print("drwxr-xr-x  4 rishit  dev   4096 Jul 26 20:00 projects/")
    print("")
    
    for i, project in enumerate(projects, 1):
        print(f"📦 {project.name}/")
        print(f"   ├── {project.description}")
        print(f"   ├── Stack: {', '.join(project.tech_stack)}")
        print(f"   └── ⚡ {project.highlight}")
        if i < len(projects):
            print("")
    
    print("\n🔗 View all repositories: github.com/Rklearns")

if __name__ == "__main__":
    display_projects()
```

</div>
</details>

<details>
<summary><kbd style="background: linear-gradient(90deg, #ffd43b, #fbbf24); color: #000; padding: 10px 20px; border-radius: 8px; font-weight: bold; font-size: 16px; cursor: pointer; border: none; box-shadow: 0 4px 15px rgba(255,212,59,0.3);">$ cat skills</kbd></summary>

<div style="background: #0d1117; border: 2px solid #ffd43b; border-radius: 10px; padding: 20px; margin: 15px 0; font-family: 'Fira Code', monospace;">

```
// skills.js - Technical expertise configuration
const skills = {
  programming: {
    python: {
      level: 95,
      usage: "Primary language for ML and automation",
      frameworks: ["TensorFlow", "Keras", "OpenCV"]
    },
    java: {
      level: 80, 
      usage: "Competitive programming and OOP",
      experience: "3+ years"
    },
    c: {
      level: 70,
      usage: "System programming and algorithms", 
      specialty: "Network programming"
    }
  },
  
  machine_learning: {
    tensorflow: {
      proficiency: 90,
      projects: ["Pneumonia diagnosis", "Computer vision"]
    },
    pytorch: {
      proficiency: 75,
      usage: "Research experiments"
    },
    opencv: {
      proficiency: 80,
      applications: ["Gesture control", "Image processing"]
    }
  },
  
  tools: {
    git: {
      daily_use: true,
      proficiency: 90
    },
    linux: {
      comfort_level: "Advanced",
      daily_driver: true
    }
  },
  
  specializations: [
    "Machine Learning & Deep Learning",
    "Computer Vision", 
    "Competitive Programming",
    "Algorithm Design"
  ]
};

// Display skill summary
console.log("💻 Technical Skills Summary:");
console.log("─".repeat(40));

Object.entries(skills.programming).forEach(([lang, data]) => {
  const bar = "█".repeat(Math.floor(data.level/5)) + "░".repeat(20-Math.floor(data.level/5));
  console.log(`${lang.padEnd(10)} ${bar} ${data.level}%`);
});

console.log("\n🎯 Currently mastering: Advanced ML architectures");
```

</div>
</details>

<details>
<summary><kbd style="background: linear-gradient(90deg, #e74c3c, #dc2626); color: #fff; padding: 10px 20px; border-radius: 8px; font-weight: bold; font-size: 16px; cursor: pointer; border: none; box-shadow: 0 4px 15px rgba(231,76,60,0.3);">$ ./cp_stats</kbd></summary>

<div style="background: #0d1117; border: 2px solid #e74c3c; border-radius: 10px; padding: 20px; margin: 15px 0; font-family: 'Fira Code', monospace;">

```
#include <iostream>
#include <map>
#include <string>
#include <iomanip>

class CompetitiveProgrammer {
private:
    struct PlatformData {
        int rating;
        std::string rank;
        int problems_solved;
        std::string profile_url;
    };
    
    std::map<std::string, PlatformData> platforms;

public:
    CompetitiveProgrammer() {
        platforms["Codeforces"] = {1244, "Pupil", 100, "emailrishitkar"};
        platforms["CodeChef"] = {1606, "3-Star", 150, "rkstriker"};
        platforms["LeetCode"] = {130, "Active", 130, "Rkstriker"};
    }
    
    void displayStats() {
        std::cout << "🏆 COMPETITIVE PROGRAMMING STATISTICS\n";
        std::cout << "═══════════════════════════════════════\n\n";
        
        for (const auto& [platform, data] : platforms) {
            std::cout << "🤖 " << std::left << std::setw(12) << platform;
            std::cout << "Rating: " << std::setw(6) << data.rating;
            std::cout << "(" << data.rank << ")\n";
            std::cout << "   └── Profile: " << platform.substr(0,1) 
                     << std::string(platform.begin()+1, platform.end()) 
                     << ".com/profile/" << data.profile_url << "\n\n";
        }
        
        std::cout << "📊 Total Problems Solved: 300+\n";
        std::cout << "🎪 Major Event: CodeUncode Organizer (1200+ participants)\n";
        std::cout << "🎯 Current Goal: Expert on Codeforces (1600+)\n";
    }
};

int main() {
    CompetitiveProgrammer rishit;
    rishit.displayStats();
    
    std::cout << "\n// Execution completed successfully ✅\n";
    return 0;
}
```

</div>
</details>

<details>
<summary><kbd style="background: linear-gradient(90deg, #8b5cf6, #7c3aed); color: #fff; padding: 10px 20px; border-radius: 8px; font-weight: bold; font-size: 16px; cursor: pointer; border: none; box-shadow: 0 4px 15px rgba(139,92,246,0.3);">$ contact</kbd></summary>

<div style="background: #0d1117; border: 2px solid #8b5cf6; border-radius: 10px; padding: 20px; margin: 15px 0; font-family: 'Fira Code', monospace;">

```
{
  "contact_info": {
    "primary": {
      "email": "emailrishitkar@gmail.com",
      "phone": "+91 9820998983",
      "location": "Mumbai, India",
      "timezone": "UTC+5:30"
    },
    "professional": {
      "linkedin": "linkedin.com/in/rishit-kar-786495286/",
      "github": "github.com/Rklearns"
    },
    "competitive": {
      "codeforces": "codeforces.com/profile/emailrishitkar",
      "codechef": "codechef.com/users/rkstriker",
      "leetcode": "leetcode.com/u/Rkstriker"
    },
    "availability": {
      "status": "🟢 Available for opportunities",
      "best_time": "6:00 PM - 10:00 PM IST",
      "response_time": "Within 24 hours",
      "open_for": [
        "ML collaborations",
        "CP discussions", 
        "Research projects",
        "Internship opportunities"
      ]
    }
  }
}
```

```
# Quick connectivity test
echo "Testing all contact channels..."
ping -c 1 gmail.com > /dev/null && echo "✅ Email: Active"
curl -s linkedin.com > /dev/null && echo "✅ LinkedIn: Responsive" 
curl -s github.com > /dev/null && echo "✅ GitHub: Online"

echo ""
echo "📧 Ready to connect! Reach out anytime."
```

</div>
</details>

---

<div align="center" style="margin: 30px 0;">

<img src="https://github-readme-stats.vercel.app/api?username=Rklearns&show_icons=true&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=00ff41&text_color=fff&icon_color=00ff41" height="160" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rklearns&layout=compact&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=00ff41&text_color=fff" height="160" />

</div>

---

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&duration=2000&pause=1000&color=00FF41&center=true&vCenter=true&width=500&lines=session+complete;thanks+for+exploring!;ready+to+collaborate%3F" alt="closing" />

```
$ echo "Thanks for visiting my terminal!" 
Thanks for visiting my terminal!

$ logout
Connection to rishit-terminal closed.
```

<img src="https://komarev.com/ghpvc/?username=Rklearns&color=00ff41&style=flat" />

</div>
```

## ✨ Fixed Issues:

🎯 **Beautiful Code Blocks** - Each dropdown now has stunning, syntax-highlighted code  
⚡ **Fixed Typing Animation** - Proper parameters for smooth terminal feel  
🔧 **Accurate Skills** - Removed Docker and other tools you don't know  
🎨 **Enhanced UI** - Gradient buttons with perfect shadows and colors  
💻 **Real Code Examples** - Bash, Python, JavaScript, C++, JSON - all authentic  

Your CLI now looks **absolutely breathtaking** with perfect interactive elements! 🚀✨
