[update-readmes]   Mode: rewrite — migrating to template structure...
# omi

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/omi)

<!-- AI:start:what-it-does -->
This project provides an AI system that observes user activity on a screen, listens to conversations, and offers actionable recommendations. It is designed for users seeking contextual assistance and automation in their workflows, integrating capabilities like file system access, Redis-based data handling, and cloud-based processing.
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
The architecture consists of several key components:

1. **App**: Contains the main application logic and user interface, implemented in Dart.
2. **Backend**: Handles server-side processing, including AI model inference and data storage. It integrates with Redis via the `ioredis` library.
3. **Desktop**: Manages desktop-specific functionality, such as screen capture and audio input.
4. **Plugins**: Extends functionality with modular components.
5. **Scripts**: Includes utility scripts for automation and deployment.
6. **Docs**: Contains documentation and guides for contributors and users.
7. **Workflows**: GitHub Actions workflows for CI/CD, testing, and deployment.

The project uses `expo-file-system` for file management and `dotenv-cli` for environment variable handling. The directory structure is as follows:

```plaintext
.
├── .github/               # GitHub workflows and issue templates
├── app/                   # Main application code
├── backend/               # Backend services and APIs
├── desktop/               # Desktop-specific functionality
├── docs/                  # Documentation
├── plugins/               # Plugin modules
├── scripts/               # Automation and utility scripts
├── sdks/                  # SDKs for external integrations
├── web/                   # Web-related components
├── package.json           # Project dependencies and scripts
├── README.md              # Project overview and instructions
└── LICENSE                # License information
```
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/omi.git
cd omi
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
The repository uses GitHub Actions for continuous integration and deployment. Below are the workflows and their purposes:

- **deploy_docs.yml**: Deploys project documentation. Requires no secrets.
- **desktop_auto_release.yml**: Automates desktop application releases. Requires `DESKTOP_RELEASE_TOKEN`.
- **desktop_backend_auto_dev.yml**: Builds and tests the desktop backend in development. No secrets required.
- **entellegence_issues.yml**: Manages issue triage for the Entelligence component. No secrets required.
- **entelligence-pr-reviewer.yml**: Assigns reviewers to pull requests for Entelligence. No secrets required.
- **gcp_* workflows**: Handle various Google Cloud Platform (GCP) tasks, including deployment, backend services, notifications, and plugins. Most require `GCP_SERVICE_ACCOUNT_KEY`.
- **lint.yml**: Runs linting checks on the codebase. No secrets required.
- **main.yml**: Executes the main CI pipeline, including build and test steps. No secrets required.
- **onboarding_figma_sync.yml**: Syncs onboarding assets with Figma. Requires `FIGMA_API_KEY`.
- **pr-declined-comment.yml**: Adds comments to declined pull requests. No secrets required.
- **sync-docs.yml**: Synchronizes documentation updates. No secrets required.

Refer to individual workflow files in `.github/workflows/` for detailed configurations and additional requirements.
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/omi`](https://github.com/Interested-Deving-1896/omi) and mirrored through:

```
Interested-Deving-1896/omi  ──►  OpenOS-Project-OSP/omi  ──►  OpenOS-Project-Ecosystem-OOC/omi
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
[@beastoin](https://github.com/beastoin) - 5057 commits  
[@mdmohsin7](https://github.com/mdmohsin7) - 3756 commits  
[@josancamon19](https://github.com/josancamon19) - 1949 commits  
[@kodjima33](https://github.com/kodjima33) - 1768 commits  
[@github-actions[bot]](https://github.com/github-actions[bot]) - 1476 commits  
[@aaravgarg](https://github.com/aaravgarg) - 1372 commits  
[@krushnarout](https://github.com/krushnarout) - 415 commits  
[@smian1](https://github.com/smian1) - 268 commits  
[@m13v](https://github.com/m13v) - 262 commits  
[@akshaynarisetti](https://github.com/akshaynarisetti) - 226 commits  
[@80asv](https://github.com/80asv) - 166 commits  
[@thainguyensunya](https://github.com/thainguyensunya) - 166 commits  
[@adamcohenhillel](https://github.com/adamcohenhillel) - 153 commits  
[@francip](https://github.com/francip) - 142 commits  
[@kevvz](https://github.com/kevvz) - 128 commits  
[@TuEmb](https://github.com/TuEmb) - 124 commits  
[@neooriginal](https://github.com/neooriginal) - 108 commits  
[@Becca-Saka](https://github.com/Becca-Saka) - 66 commits  
[@vincentkoc](https://github.com/vincentkoc) - 64 commits  
[@skywinder](https://github.com/skywinder) - 52 commits  
[@syou6162](https://github.com/syou6162) - 49 commits  
[@thinhx](https://github.com/thinhx) - 47 commits  
[@TristanLaR](https://github.com/TristanLaR) - 38 commits  
[@eng1n88r](https://github.com/eng1n88r) - 36 commits  
[@ashbhat](https://github.com/ashbhat) - 34 commits  
[@findirfin](https://github.com/findirfin) - 26 commits  
[@nquang29](https://github.com/nquang29) - 21 commits  
[@jfbg98](https://github.com/jfbg98) - 18 commits  
[@Bentlybro](https://github.com/Bentlybro) - 17 commits  
[@ebariaux](https://github.com/ebariaux) - 16 commits  
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
<!-- License not detected — add a LICENSE file to this repo. -->
<!-- AI:end:license -->
