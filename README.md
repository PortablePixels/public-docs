# public-docs
Place for Github public pages

## SBOM (Software Bill of Materials)

This repository contains a public GitHub Pages site that displays our Software Bill of Materials (SBOM).

### Viewing the SBOM

The SBOM page is available at: `https://[your-org].github.io/public-docs/`

The page displays all packages and dependencies organized by repository, with the following features:

- **Repository Grouping**: Packages are organized by repository for easy navigation
- **Search**: Search across package names, licenses, languages, and organizations
- **Filtering**: Filter by repository or risk level
- **Statistics**: View total packages, repositories, and unique licenses
- **Expandable Sections**: Click on repository headers to expand/collapse package lists

### Files

- `index.html` - The main SBOM display page
- `license_report.csv` - The source CSV file containing all SBOM data

### Updating the SBOM

To update the SBOM data:

1. Generate SBOM license report on Aikido > Reports and download it as a csv
1. Replace `license_report.csv` with the new CSV file
2. The page will automatically reflect the changes (no rebuild needed)

### GitHub Pages Setup

To enable GitHub Pages:

1. Go to repository Settings → Pages
2. Select the branch (typically `main` or `master`)
3. Select the root directory as the source
4. Save the settings

The page will be available at `https://[your-org].github.io/public-docs/` after a few minutes.
