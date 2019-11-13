# VueJS_AzureAppService_App - hello-world

## VueJS Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Azure App Services Deploy using FTP

### 1. Create An App Service Plan

### 2. Create an Azure Web App

### 3. Do to "Deployment Center"

### 4. Select FTP

### 4. Click dashboard to obtain FTP credentials

### 5. Run the following cURL command to send files in 'dist' folder to target ftps
```

$ find dist -type f -exec curl -v --user testvueey$testvueey:KakFjG3q6kJ7CcSptJCxeSeANHyEekgmla6xxxgfuRSokmEwlqWwJar0sY4M --ftp-create-dirs -T {} ftps://waws-prod-sy3-021.ftp.azurewebsites.windows.net/site/wwwroot/ \;
```
### 6. Alternatively use WinSCP to manually upload files
