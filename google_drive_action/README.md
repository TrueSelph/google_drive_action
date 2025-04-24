# Google Drive Action

![GitHub release (latest by date)](https://img.shields.io/github/v/release/TrueSelph/google_drive_action)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/TrueSelph/google_drive_action/test-google_drive_action.yaml)
![GitHub issues](https://img.shields.io/github/issues/TrueSelph/google_drive_action)
![GitHub pull requests](https://img.shields.io/github/issues-pr/TrueSelph/google_drive_action)
![GitHub](https://img.shields.io/github/license/TrueSelph/google_drive_action)

This action provides seamless integration with Google Drive using the Google API Python client for managing and automating file and folder tasks. It enables efficient operations such as uploading, moving and sharing files in Google Drive. As a singleton in the action group, it ensures centralized management for Google Drive integrations. This package requires the Jivas library version 2.0.0, along with the `google-api-python-client` and `google-auth` Python packages.

## Package Information

- **Name:** `jivas/google_drive_action`
- **Author:** [V75 Inc.](https://v75inc.com/)
- **Architype:** `GoogleDriveAction`
- **Version:** 0.0.1

## Meta Information

- **Title:** Google Drive Action
- **Description:** Provides seamless integration with Google Drive for managing and automating file storage.
- **Group:** core
- **Type:** action

## Configuration
- **Singleton:** true

## Dependencies
- **Jivas:** ^2.0.0
- **Pip:**
  - **google-api-python-client:** 2.97.0
  - **google-auth:** 2.32.0

---

### Best Practices
- Always store your Google Service Account credentials securely.
- Regularly update and rotate access tokens to maintain security.
- Test configurations in a staging environment before going live.

---

## 🚀 Google Drive API Setup Guide

### Step 1: Create a Service Account

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or select an existing one.
3. Navigate to **APIs & Services > Credentials**.
4. Click **Create Credentials > Service Account**.
5. Fill in the required details and click **Done**.

### Step 2: Enable Google Drive API

1. In the **APIs & Services > Library**, search for **Google Drive API**.
2. Click **Enable** to activate the API for your project.

### Step 3: Download Service Account Key

1. In the **Credentials** section, locate your service account and click it.
2. Click **keys > add key > Create new key**.
3. Select **JSON** and create.

### Step 4: Share Folder or File with Service Account email
1. Open your Google Drive.
2. Create a folder and copy the **folder_id**

---

## 🔰 Contributing

- **🐛 [Report Issues](https://github.com/TrueSelph/google_drive_action/issues)**: Found a bug or want to request a feature? Submit it here.
- **💡 [Submit Pull Requests](https://github.com/TrueSelph/google_drive_action/blob/main/CONTRIBUTING.md)**: Check out open PRs or submit your own improvements.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/TrueSelph/google_drive_action
   ```
</details>