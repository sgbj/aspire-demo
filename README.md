# .NET Aspire Demo

Playground repo for [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire/get-started/aspire-overview) using the starter app template with separate API and frontend projects, and Redis cache.

* 📊 Dashboard
* 🗒️ Logs
* ⏱️ Traces
* 📈 Metrics
* 📦 Containers

<img src="https://github.com/sgbj/aspire-demo/assets/5178445/d5ad5a3b-2c5b-46a8-ae11-3be740c601a1" alt="Frontend weather" width="600">
<img src="https://github.com/sgbj/aspire-demo/assets/5178445/368ddd4f-f0e1-4f0b-b64d-1436cfdbcea6" alt="Dashboard logs" width="600">
<img src="https://github.com/sgbj/aspire-demo/assets/5178445/787efd60-af0b-421c-90ca-ec062499725b" alt="Dashboard traces" width="600">

## Getting started

Install .NET Aspire workload for Visual Studio (optional):
```bash
dotnet workload install aspire
```

Clone and run the app:
```bash
git clone https://github.com/sgbj/aspire-demo.git
cd aspire-demo
dotnet run --project AspireDemo.AppHost
```
