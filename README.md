## Starter Kit Android Project with Kotlin
Pada project Android starter kit ini kita akan menjadikan struktur dasar pada project adalah sebagai berikut kerangkanya

```.sh
app/
└── src/
    └── main/
        ├── java/com/yourapp/
        │   ├── data/
        │   │   ├── model/           # Data classes, DTOs
        │   │   ├── network/         # Retrofit APIs, networking code
        │   │   └── repository/      # Repository pattern
        │   ├── di/                  # Dependency Injection modules (e.g., Hilt)
        │   ├── ui/                  # UI-related components
        │   │   ├── features/        # Tiap fitur modular
        │   │   │   └── feature_name/
        │   │   │       ├── view/       # Activity/Fragment
        │   │   │       ├── viewmodel/  # ViewModel
        │   │   │       └── state/      # UI State/Effect (optional)
        │   │   └── components/      # Reusable UI components
        │   └── utils/              # Helper classes, extensions
        └── res/
            ├── layout/
            ├── values/
            └── drawable/
```
