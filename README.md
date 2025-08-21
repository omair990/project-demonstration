# 🚀 Launches History – .NET MAUI 8  

A cross-platform mobile app built with **.NET MAUI 8** that displays Launches history using the official.

This project is a **personal demonstration** of mobile development best practices — clean architecture (MVVM), dependency injection, testing, and modern tooling.  

🔗 **Repository:** [github.com/omair990/project-demonstration](https://github.com/omair990/project-demonstration)

---

## ✨ Features  
- Browse full launch history  
- View mission details, status, and external links  
- Search and basic filtering  
- Offline-friendly UI states (loading, empty, error)  
- MVVM architecture with testable layers  
- Unit tests with mocks  

---

## 🛠 Tech Stack  

| Tool / Framework                                                                                       | Purpose                                                                                                      |
|--------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| [.NET MAUI 8](https://learn.microsoft.com/dotnet/maui)                                                 | Cross-platform UI framework                                                                                  |
| [MVVM](https://learn.microsoft.com/dotnet/maui/xaml/fundamentals/mvvm)                                 | Clean separation of Views and ViewModels                                                                     |
| [Refit](https://github.com/reactiveui/refit)                                                           | Typed REST client for API integration                                                                        |
| [Fody.PropertyChanged](https://github.com/Fody/PropertyChanged)                                        | Auto-implements `INotifyPropertyChanged`                                                                     |
| [xUnit](https://xunit.net)                                                                             | Unit testing framework                                                                                       |
| [Moq](https://github.com/moq/moq)                                                                      | Mocking dependencies in tests                                                                                |

---

## 🏗 Architecture  


- **ViewModels** → Expose observable state and commands  
- **Services (Refit)** → Wrap launch API endpoints  
- **Dependency Injection** → Registered in `MauiProgram.cs`  

---

## ⚙️ Getting Started  

### Requirements  
- Visual Studio (latest)  
- .NET 8 SDK  

### Run the App  
```bash
dotnet restore
dotnet build
