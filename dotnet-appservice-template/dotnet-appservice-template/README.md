# .NET 8 Razor Pages → Azure App Service (GitHub Actions)

## Prereqs
- Secrets in this repo (Settings → Secrets → Actions):
  - `AZURE_CLIENT_ID`
  - `AZURE_TENANT_ID`
  - `AZURE_SUBSCRIPTION_ID`
  - `AZURE_CLIENT_SECRET`

## Local run
```bash
dotnet restore
dotnet run
```

## Deploy (CI/CD)
Push to `main`. The GitHub Action will publish and deploy to Azure App Service.
