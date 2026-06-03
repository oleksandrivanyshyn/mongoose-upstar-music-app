# 🎵 Mongoose Upstar Music App

A desktop music catalog application built with Electron, React, and Redux, utilizing Mongoose for advanced MongoDB query processing, multi-criteria filtering, and automatic data seeding.

## ✨ Features

* **Desktop Application Wrapper**: Runs as a cross-platform desktop application powered by Electron.
* **Automated Data Seeding**: Automatically validates the database state and seeds random artist profiles using `lodash` and `faker` directly upon application startup.
* **Advanced Query Mechanics**: Implements complex search queries supporting simultaneous sorting, text search, and strict range filtering (like age and years active).
* **Relational Embedding**: Integrates and validates parent-child relationships by nesting an array of album subdocuments directly inside the parent Artist schema.
* **Legacy Asset Compilation**: Bundled using Webpack 1 with Babel compilation to support structural legacy components.

## 🛠️ Tech Stack

* **Desktop Shell**: Electron (`v27.0.3`)
* **Backend Framework**: Node.js, Mongoose (`v5.13.21`), MongoDB Native Driver (`v3.6.12`)
* **Frontend Workflow**: React (`v0.14.3`), Redux (`v3.6.0`), React Router (`v3.0.0`), Redux Form, Redux Thunk
* **Bundler & Styles**: Webpack 1, Sass, Prettier

## ⚙️ Quick Start

### 1. Install Dependencies

```bash
npm install

```

### 2. Run Database

Ensure your local MongoDB instance is running on your machine at `mongodb://localhost:27017`.

### 3. Start Application

Launch the application. The system will automatically build the client assets, open the Electron window, and seed the test data if the database is empty:

```bash
npm start

```
