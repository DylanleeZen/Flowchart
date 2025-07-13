flowchart TD
    A[Wake Up] --> B[Brush Teeth]
    B --> C[Eat Breakfast]
    C --> D[Pack Bag]
    D --> E[Wear Uniform]
    E --> F[Leave House]
    F --> G{Mode of Transport?}
    G -- Walk --> H[Walk to School]
    G -- Bus --> I[Wait for and Board Bus]
    G -- Car --> J[Get in Car]
    H --> K[Arrive at School]
    I --> K
    J --> K
    K --> L[Go to Class]
    L --> M[Start Learning]
