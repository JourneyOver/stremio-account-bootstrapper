![Stremio Account Bootstrapper Logo](https://github.com/DryKillLogic/stremio-account-bootstrapper/blob/main/public/logo.png?raw=true)

# Stremio Account Bootstrapper

**Stremio Account Bootstrapper** simplifies the setup of your Stremio account, allowing you to configure everything in just a few clicks. Perfect for newcomers, users who want a reliable foundation for their setup, or anyone needing to quickly set up new accounts for friends or family.

> **Warning:** This tool will erase your existing setup, and there's no option to revert changes. Use it at your own risk—no support is provided.

---

## Key Features

- **Fast Account Setup:** Configure your Stremio account in minutes.
- **TMDB as Default Resolver:** Uses TMDB as the primary metadata source, removing Cinemeta catalogs without affecting core functionality.
- **RealDebrid and AllDebrid Support:** Integrate with popular services for seamless streaming.
- **RPDB Support:** Add support for RPDB.
- **Reset to Default:** Quickly restore the account to a clean state.
- **Optimized Addon Configuration:** Preconfigured addons for an improved experience.
- **Addon Management:** Sort addons, rename catalogs, and delete catalogs (from Addon Manager).

---

## Recommended Development Environment

For the best experience, use:
- **[Visual Studio Code](https://code.visualstudio.com/)** with **[Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)** (disable Vetur for compatibility).

---

## Project Setup

Clone the repository and install dependencies with:

```bash
npm install
```

### Development

To compile and run the app in development mode with hot-reloading:

```bash
npm run dev
```

### Production Build

To compile and minify the app for production:

```bash
npm run build
```

### Code Formatting

To format code consistently with Prettier:

```bash
npm run format
```

---

## Docker Deployment

You can also deploy the app using Docker. Build and run the Docker container with:

```bash
docker build -t stremio-account-bootstrapper .
docker run -p 8080:80 stremio-account-bootstrapper
```

The app will be available at `http://localhost:8080`.

---

## Acknowledgments

Special thanks to **pancake3000**, **redd-ravenn**, **Sleeyax**, and **&#60;Code/&#62;** for their foundational work on this tool and their dedication to the Stremio community 🙏. This project wouldn’t be possible without their efforts.
