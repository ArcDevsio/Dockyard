# Dockyard

> A modern, offline-first mod manager for Spaceflight Simulator.

<p align="center">
  <a href="https://github.com/ArcDevsio/Dockyard/releases">
    <img src="https://img.shields.io/github/v/release/ArcDevsio/Dockyard?style=flat-square" alt="Latest Release">
  </a>
  <a href="https://github.com/ArcDevsio/Dockyard/releases">
    <img src="https://img.shields.io/github/downloads/ArcDevsio/Dockyard/total?style=flat-square" alt="Downloads">
  </a>
  <a href="https://github.com/ArcDevsio/Dockyard/stargazers">
    <img src="https://img.shields.io/github/stars/ArcDevsio/Dockyard?style=flat-square" alt="Stars">
  </a>
  <a href="https://github.com/ArcDevsio/Dockyard/network/members">
    <img src="https://img.shields.io/github/forks/ArcDevsio/Dockyard?style=flat-square" alt="Forks">
  </a>
  <a href="https://github.com/ArcDevsio/Dockyard/commits/main">
    <img src="https://img.shields.io/github/last-commit/ArcDevsio/Dockyard?style=flat-square" alt="Last Commit">
  </a>
</p>

---

## About

Dockyard is a mod manager for **Spaceflight Simulator** designed to make discovering, downloading, installing, and managing community content simple.

It provides a centralized experience for:

* Mods
* Parts
* Textures
* Blueprints
* Other compatible community content

Content distributed through Dockyard is reviewed and published by ArcDevs.

---

## Repository

| Property     | Value                             |
| ------------ | --------------------------------- |
| Organization | `ArcDevsio`                       |
| Repository   | `Dockyard`                        |
| Platform     | Android                           |
| Game         | Spaceflight Simulator             |
| Framework    | Expo / React Native               |
| Language     | TypeScript                        |
| Distribution | Expo / APK                        |
| Content      | Mods, Parts, Textures, Blueprints |
| Architecture | Offline-first                     |
| Accounts     | Not required                      |

---

## Repository Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ArcDevsio&repo=Dockyard&hide_border=true&theme=transparent" alt="Dockyard repository statistics">
</p>

<p align="center">
  <a href="https://github.com/ArcDevsio/Dockyard/issues">
    <img src="https://img.shields.io/github/issues/ArcDevsio/Dockyard?style=flat-square" alt="Issues">
  </a>
  <a href="https://github.com/ArcDevsio/Dockyard/pulls">
    <img src="https://img.shields.io/github/issues-pr/ArcDevsio/Dockyard?style=flat-square" alt="Pull Requests">
  </a>
  <a href="https://github.com/ArcDevsio/Dockyard/commits/main">
    <img src="https://img.shields.io/github/commit-activity/m/ArcDevsio/Dockyard?style=flat-square" alt="Commit Activity">
  </a>
  <a href="https://github.com/ArcDevsio/Dockyard">
    <img src="https://img.shields.io/github/repo-size/ArcDevsio/Dockyard?style=flat-square" alt="Repository Size">
  </a>
</p>

---

## How It Works

Creators can submit their work to ArcDevs for review.

Once approved, content can be published through the Dockyard distribution system and made available to users through the app.

```text
Creator
   |
   v
Submission
   |
   v
ArcDevs Review
   |
   v
Approved Content
   |
   v
Dockyard Catalog
   |
   v
Dockyard App
   |
   v
Download & Install
```

Dockyard handles the user-facing experience so players do not have to manually search for files, download archives, or manage installations themselves.

---

## For Creators

Creators can request to have their work distributed through Dockyard.

A submission should include:

* Content files
* Content name
* Creator name
* Version
* Supported game version
* Description
* Required dependencies
* License or redistribution permission
* Preview image, where applicable

Approved content is attributed to its original creator.

**Creators retain ownership of their work.**

Submitting content to Dockyard does not transfer ownership to ArcDevs.

---

## Content

### Mods

Gameplay modifications, systems, utilities, and other modifications.

### Parts

Custom spacecraft parts, engines, structural components, and related content.

### Textures

Visual modifications and texture packs.

### Blueprints

Community-created spacecraft, rockets, vehicles, and other saved designs.

---

## Distribution

Dockyard uses release-based distribution for downloadable content.

A content release can contain the files required for installation.

```text
Content
└── Version
    ├── Mod files
    ├── Assets
    └── Metadata
```

The Dockyard service can use release and metadata information to determine:

* Available versions
* Latest versions
* Download assets
* Release notes
* Update availability
* Compatibility information

---

## Offline First

Dockyard is designed around an offline-first architecture.

Downloaded content is stored locally on the device, allowing previously installed content to remain available without an internet connection.

Internet access is only required for functionality that depends on remote services.

### Online

* Browse newly published content
* Download content
* Check for updates
* Synchronize metadata

### Offline

* Access installed content
* Access downloaded files
* View locally cached information
* Manage locally installed content

The app itself does not require a constant internet connection.

---

## No Accounts

Dockyard does not require users to create an account.

There are no mandatory:

* User profiles
* Passwords
* Social logins
* User accounts

The intended experience is simple:

**Open Dockyard. Find content. Download it. Use it.**

---

## Local Storage

Downloaded content is stored locally on the user's device.

Dockyard separates application data from downloaded content so that the app can maintain information about installed content while keeping the actual mod files on local storage.

Conceptually:

```text
Dockyard
|
+-- Local Database
|   +-- Mod metadata
|   +-- Installed versions
|   +-- Favorites
|   +-- Settings
|
+-- Local Files
    +-- Mods
    +-- Textures
    +-- Parts
    +-- Blueprints
```

---

## Content Review

Content distributed through Dockyard may be reviewed by ArcDevs before publication.

Content may be rejected or removed if it:

* Contains malicious software
* Misrepresents another creator's work
* Violates stated licensing or redistribution permissions
* Is incompatible with Dockyard
* Presents a security or safety concern
* Violates Dockyard distribution guidelines
* Violates applicable laws

---

## Licensing

Community content may be provided under different licenses.

A license applying to the Dockyard source code does not automatically apply to community-created mods, textures, parts, or blueprints.

Always check the individual content's license or redistribution terms.

Unless explicitly stated otherwise:

> Community-created content remains the property of its respective creator.

ArcDevs only distributes community content with appropriate permission from its creator or rights holder.

---

## Development

Dockyard is built using:

* **Expo**
* **React Native**
* **TypeScript**
* **Expo Router**

The project is currently focused on Android development.

Development and testing can be performed through Expo Go during active development, while standalone builds can be produced for release and distribution.

---

## Project Status

Dockyard is currently under active development.

Features, architecture, and distribution systems may change as the project evolves.

The repository currently serves as the central source for the Dockyard application and its development history.

---

## Maintained By

**ArcDevs**

Dockyard is developed and maintained by ArcDevs as an independent community project.

---

## Disclaimer

Dockyard and ArcDevs are independent community projects and are not affiliated with, endorsed by, or officially associated with the developers or publishers of **Spaceflight Simulator**, unless explicitly stated.

All trademarks and third-party content remain the property of their respective owners.

---

<p align="center">
  <strong>Dockyard</strong><br>
  Discover. Download. Build.
</p>

<p align="center">
  <a href="https://github.com/ArcDevsio/Dockyard/releases">Releases</a>
  ·
  <a href="https://github.com/ArcDevsio/Dockyard/issues">Issues</a>
  ·
  <a href="https://github.com/ArcDevsio/Dockyard">Repository</a>
</p>
