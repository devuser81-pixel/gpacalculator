# Single-Semester C# GPA Calculator

A modular C# console application designed to calculate cumulative single-semester GPAs using explicit 5.0 scale grade boundaries and embedded mathematical assertions.

## Grading Thresholds (5.0 Scale)
- **A**: 70.0 - 100.0 (5 Points)
- **B**: 60.0 - 69.9 (4 Points)
- **C**: 50.0 - 59.9 (3 Points)
- **D**: 45.0 - 49.9 (2 Points)
- **E**: 40.0 - 44.9 (1 Point)
- **F**: < 40.0 (0 Points)

## Features
- **Modular Domain Design**: Decoupled domain models (`Course.cs`), core calculations (`GpaCalculator.cs`), and formatted presentation (`Program.cs`).
- **Programmatic Self-Checks**: Embedded unit assertions (`RunSelfChecks()`) verify mathematical accuracy before rendering outputs.
- **Auditable Tabular Formatting**: Structured ASCII console rendering for line-item inspection.

## Build and Run Instructions
1. Ensure .NET 8 SDK or later is installed.
2. Execute the application from terminal:
   ```zsh
   dotnet run
