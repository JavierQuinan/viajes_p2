# Viajes API — historical NestJS learning project

> **Repository status:** historical / academic evidence. This repository is preserved for learning history and is **not presented as a current production-ready portfolio project**.

## Scope

NestJS / TypeScript backend practice around a travel-oriented API. The repository contains application code, tests and development configuration from an earlier learning stage.

## Security remediation

A development environment file had been versioned in this public repository. It has been removed from the current branch, `.gitignore` now blocks environment files by default, and a sanitized `.env.example` is provided instead.

Because Git history can preserve previously committed content, any credential that was ever committed must be treated as compromised and must not be reused. The current repository contains no credential value in the working tree by design.

## Local configuration

Copy the sanitized example and replace values locally:

```bash
cp .env.example .env.development
```

Never commit the resulting environment file.

## Portfolio classification

**Category:** NestJS / TypeScript academic evidence  
**Visibility:** Public  
**Portfolio priority:** Low  
**Recommended use:** Historical learning evidence only; not a pinned repository.

For current engineering work and selected repositories, see the main [GitHub profile](https://github.com/JavierQuinan).
