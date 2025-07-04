# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.3.0 (Unreleased)

- Rename traefik routers, services, middlewares [fosten]
- Remove duplicate gzip middleware references [fosten]
- Add Keycloak [fosten]
- Fixed [Issue #3511488: Refreshed access_token is missing scope with league/oauth2-server ^9](https://www.drupal.org/project/simple_oauth_password_grant/issues/3511488) [fosten]
- Bump production from 3.3.1 to 3.4.5 [fosten]
- Remove farm_equipment_asset_extended [fosten]
- Add CORS_ALLOW_ORIGIN env var [fosten]
- Upgrade to PHPStan level 5 [fosten]
- Change traefik.docker to traefik.swarm [fosten]

## 1.2.0 (2024-12-16)

- Remove minor GHA releases from dependabot [fosten]
- Add httpswww [fosten]
- Remove ports [fosten]
- Add hashed pw vars [fosten]
- Change ipwhitelist to ipallowlist [fosten]
- Add nrcs, map_custom_layers, grazing_plan modules [fosten]
- Add smtp, farm_maple, farm_project_plan, farm_template modules [fosten]
- Bump production version from 3.1.2 to 3.3.1 [fosten]

## 1.1.0 (2024-08-28)

- Persistent volume private file path [fosten]
- Add dependabot [fosten]
- Add farmos_asset_link [fosten]
- Add drupal/flood_control [fosten]
- Add drupal/dashboards [fosten]

## 1.0.0 (2024-04-09)

- Bind-mount keys volume [fosten]
- Add second traefik router for API and OAuth [fosten]
- Chain auth/whitelist middlewares [fosten]
- Add ipwhitelist [fosten]
- Add farm_structure_asset_extended [fosten]
- Add farm_equipment_asset_extended [fosten]
- Add farm_land_asset_extended [fosten]
- Add farm_eggs [fosten]
- Add farm_ledger [fosten]
- Add farm_calendar_events [fosten]
- Add farm_seed_asset_extended [fosten]
- Add farm_crop_plan [fosten]
- Bump farmOS production version to 3.1.2 [fosten]

## 0.1.0 (2023-12-06)

- Initial commit [fosten]