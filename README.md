# Problem Solving Platform (LeetCode Clone)

A modern, full-featured problem solving platform built with ASP.NET Core. This application allows users to solve coding challenges, run tests against their solutions, and compete on leaderboards along with a feature-rich admin panel to manage challenges.

## ?? Features

### Core Functionality
- **Multi-Language Support**: Supports Python, JavaScript, Java, C++, C#, Go, Rust, PHP, Ruby, and TypeScript.
- **Modern Compiler UI**: A beautiful dark-themed code editor with syntax highlighting, tab support, and professional styling.
- **Test Case System**: Automated testing system that validates user solutions against defined test cases.
- **Real-time Feedback**: Visual success/failure indicators for test runs.
- **Function Templates**: Smart code templates generated for each problem to help users get started.

### User Experience
- **User Profiles**: customizable profiles with image upload.
- **Leaderboard**: Compete with other users.
- **Discussion Forums**: Discuss problems and share solutions.
- **Responsive Design**: Clean and modern interface.

### Admin Tools
- **Challenge Management**: Create and edit coding problems.
- **Test Case Management**: Define inputs and expected outputs using JSON.
- **Template Management**: Configure starting code for different languages.

## ?? Tech Stack

- **Backend**: C# / ASP.NET Core
- **Database**: SQL Server
- **Frontend**: Razor Pages, JavaScript, CSS (Modern Styling)
- **External APIs**: Integration with Piston API for code execution (implied by feature list).

## ?? Screenshots

### Application Overview
| Home Page | Problem Page |
|:---:|:---:|
| ![Home Page](projet%20dot%20net%20screens/home%20page%201.PNG) | ![Problem Page](projet%20dot%20net%20screens/page%20probleme%201.PNG) |

### Solving Experience
| Code Editor | Test Results |
|:---:|:---:|
| ![Code Editor](projet%20dot%20net%20screens/test%20compilateur.PNG) | ![Test Results](projet%20dot%20net%20screens/test%20probleme%20reponse.PNG) |

### User Features
| Login | Profile |
|:---:|:---:|
| ![Login](projet%20dot%20net%20screens/login.PNG) | ![Profile](projet%20dot%20net%20screens/profile.PNG) |

### Leaderboard & Community
| Leaderboard | Discussion |
|:---:|:---:|
| ![Leaderboard](projet%20dot%20net%20screens/leaderboard.PNG) | ![Discussion](projet%20dot%20net%20screens/discussion.PNG) |

### Admin Interface
| Create Problem | Edit Problem |
|:---:|:---:|
| ![Create Problem](projet%20dot%20net%20screens/create%20problem%201.PNG) | ![Edit Problem](projet%20dot%20net%20screens/edit%20probleme.PNG) |

## ?? Documentation

For more detailed information, check out the documentation in the `ProblemSolvingPlatform` directory:

- [Feature Overview](ProblemSolvingPlatform/LEETCODE_CLONE_FEATURES.md)
- [Quick Start Guide](ProblemSolvingPlatform/QUICK_START.md)
- [Admin Setup Guide](ProblemSolvingPlatform/ADMIN_SETUP_GUIDE.md)
- [Function Templates Guide](ProblemSolvingPlatform/FUNCTION_TEMPLATES_GUIDE.md)

## ?? Getting Started

1.  Clone the repository.
2.  Navigate to `ProblemSolvingPlatform`.
3.  Update the database connection string in `appsettings.json`.
4.  Run the database migrations or scripts found in `Scripts/`.
5.  Launch the application using Visual Studio or `dotnet run`.

---
*Happy Coding!*
