# Examples

Copy any file to `.github/workflows/` in your repo.

| File | Description |
|------|-------------|
| `01-quick-start.yml` | Plain Caddy, no modules |
| `02-build-with-modules.yml` | Add Cloudflare DNS + NTLM modules |
| `03-build-and-upload.yml` | Build and upload artifact |
| `04-matrix-all-platforms.yml` | Build on Linux, Windows, macOS (native) |
| `05-cross-compile.yml` | Cross-compile from single runner |
| `06-custom-output-dir.yml` | Output to ./dist |
| `07-advanced-replaces-embeds.yml` | Use --replace and --embed |
| `08-build-and-release.yml` | Build and attach to release (push tag v*) |
| `09-specific-version-platform.yml` | Specific Caddy version + OS/arch |
| `10-build-run-caddyfile.yml` | Build and run with Caddyfile |
| `11-build-validate-config.yml` | Build, validate config, list modules |
| `12-build-upload-use-next-job.yml` | Build → upload → use in next job |
| `13-build-single-platform.yml` | Linux only |
| `13b-build-windows-only.yml` | Windows only |
| `13c-build-macos-only.yml` | macOS only |
| `14-build-caddy-v28.yml` | Caddy v2.8.x (go-version 1.22) |
| `15-build-and-docker.yml` | Build and create Docker image |
| `16-pipeline-multiple-tasks.yml` | Build, use binary in multiple steps |
| `17-modules-comma-separated.yml` | Modules as comma-separated |
| `18-build-and-release-full-matrix.yml` | Full matrix + release |
