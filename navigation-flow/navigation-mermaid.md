```mermaid
flowchart TD
    A[Splash Screen] --> B[Login]
    B --> C[Home / Dashboard]
    C --> D[Courses]
    C --> E[Fees]
    C --> F[More]
    D --> G[My Courses]
    G --> H[Course Details]
    C --> I[Course Registration]
    I --> J[Select Courses]
    J --> K[Review]
    K --> L[Confirm]
    L --> M[Registration Confirmation]
    M --> G
    E --> N[Fee Statement]
    F --> O[Profile]
    F --> P[Notifications]
    F --> Q[Settings]