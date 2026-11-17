# Contributing

Thanks for helping improve the Rental Car System.

## Workflow

1. Create a branch from `main` (for example `feature/booking-filters` or `fix/login-redirect`).
2. Keep each pull request focused on a single change.
3. Run the test suite before opening a PR: `php artisan test`.
4. Open a pull request against `main` with a short description of what changed and why.

## Code style

- Follow PSR-12 for PHP. Laravel Pint can format the code: `./vendor/bin/pint`.
- Follow the settings in `.editorconfig`.
- Keep controllers thin and put reusable logic in models or dedicated classes.

## Commit messages

Use a short, imperative summary line (for example `Add booking date validation`),
followed by a blank line and a longer explanation when needed. When you pair on a
change, credit your co-author with a trailer:

```
Co-authored-by: Name <email@example.com>
```
