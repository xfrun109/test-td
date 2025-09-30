# Changelog and Architectural Decisions

## 2025/9/05

## Remove unused DSB Tokens

We identified and resolved issues caused by duplicated credentials between the DSB Token and Microsoft Auth. The DSB Token variables were removed from the codebase and KeyVault, as they are no longer used. All references to DSB Token variables have been cleaned up, including updates to `.env.example`, Playwright tests `.env.example`, `playwright.yml`, `ARCH.md` and `app-config.test.yaml`. GitHub Action secrets were also updated accordingly.

## 2025/09/03

[[IM-1401](https://jira.dsb.dk/browse/IN-1401)]: Integrate Google Analytics (v4) Backstage Plugin into our app by using a community Backstage plugin which is documented [here](https://github.com/backstage/community-plugins/blob/main/workspaces/analytics/plugins/analytics-module-ga4/README.md).
