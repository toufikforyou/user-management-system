# User Management System

Two takes on the same idea, registering, signing in and managing user accounts, built in two languages.
Each lives in its own folder with its own README and runs on its own.

| Folder | What it is | Stack |
|---|---|---|
| [`csharp/`](csharp) | A console application: register, log in, list users and delete a user from a menu, with custom error handling | C# · .NET 9 |
| [`php/`](php) | The backend for a web service: authentication, account CRUD, OTP and token verification, organised into controllers, includes and services | PHP 7.4+ · Composer |

## Get it

```bash
git clone https://github.com/toufikforyou/user-management-system.git
cd user-management-system
```

### C# console application

```bash
cd csharp
dotnet run
```

Requires the [.NET 9 SDK](https://dotnet.microsoft.com/download). A [video walkthrough](https://youtu.be/tsB039U27-g) and every menu option are in [`csharp/readme.md`](csharp/readme.md).

### PHP web application

```bash
cd php
composer install
```

Then point your web server at `php/index.php`. Details are in [`php/README.md`](php/README.md).

## History

This repository was `user-management-console-application` (the C# app, from Nov 2024). The PHP app was
`user-account-management-system-php` (from Aug 2025) and was merged in with its full history, so `git log`
covers both from their first commits.

## License

[MIT](LICENSE) © MH TOUFIK
