# Yunhao Hou · 侯云浩

Personal academic homepage for **roboherald**, based on [Haochen Yu's homepage](https://github.com/yuyuyu223/howsenfisher.github.io) and [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io).

Target URL: **https://roboherald.github.io/**

The existing [Embodied AI Chronicle](https://roboherald.github.io/embodied-ai-chronicle/) is maintained in its own repository and linked from the Projects section.

## Edit the homepage

| File | Content |
| --- | --- |
| `_config.yml` | Name, email, GitHub account, avatar, site URL |
| `_pages/about.md` | Biography, publications, projects, internships, education, awards |
| `_data/navigation.yml` | Navigation labels and section anchors |
| `images/avatar.png` | Profile picture (initially the public GitHub avatar) |
| `images/agc-drive.png` | Figure 1 extracted from the AGC-Drive paper |
| `assets/file/agc-drive-neurips-2025.pdf` | Published paper |
| `assets/css/main.scss` | Layout and styling |

## Preview locally

With Ruby and Bundler installed:

```bash
bundle install
bash run_server.sh
```

Open **http://127.0.0.1:4000**. Restart the server after changing `_config.yml`.

On the workstation where this draft was prepared, `bash run_server_local.sh` uses a separately installed local Ruby/Jekyll runtime without administrator privileges. That launcher is intentionally ignored by Git.

## Publish

See [部署说明](docs/DEPLOYMENT-zh.md). The repository includes a GitHub Actions workflow that builds and deploys on pushes to `main`; select **GitHub Actions** as the source in **Settings → Pages**.

Google Scholar links are blank until a personal profile is supplied. The inherited citation crawler is manual-only and disabled unless the repository variable `ENABLE_GOOGLE_SCHOLAR` is set to `true` and the secret `GOOGLE_SCHOLAR_ID` is configured.

## Attribution

The template is distributed under the MIT License; see [LICENSE](LICENSE). AcadHomepage builds on Minimal Mistakes and Academic Pages and includes Font Awesome. Personal content was adapted from the local résumé. Published paper metadata and its illustration were checked against the supplied NeurIPS 2025 paper. See [编辑说明](docs/CONTENT-NOTES-zh.md) for draft choices.
