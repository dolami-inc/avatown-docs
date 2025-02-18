# Avatown Docs
***
Welcome to the Avatown Docs repository! This repository contains documentation related to Avatown's technology and products. It serves as the official source for guides, API references, and usage instructions for various Avatown components.
***

## 🚀 Getting Started

To contribute or modify the documentation, follow the steps below:

### 1️⃣ Install Mintlify CLI
The documentation is built using Mintlify. To preview changes locally, install the Mintlify CLI:

```shell
npm i -g mintlify
```

### 2️⃣ Run Development Server
Navigate to the root of your documentation (where docs.json is located) and start the Mintlify development server:

```shell
mintlify dev
```
This will allow you to preview your changes before publishing.
***

## 📢 Publishing Changes
To automatically deploy updates to production:

Install the Mintlify GitHub App to sync changes from the repository to your deployment.
Push changes to the default branch, and they will be published automatically.
Find the installation link on your Avatown Mintlify dashboard.

***

## 🛠 Troubleshooting
- Mintlify dev isn't running? <br>
Run the following command to reinstall dependencies:

```shell
mintlify install
```

- Page loads as a 404? <br>
Ensure you are working in a folder containing `docs.json`.

***

## 🤝 Contribution Guidelines
We welcome contributions to improve Avatown Docs! Follow these steps to contribute:

### 📝 1. Fork & Clone
Fork this repository and clone it to your local machine:

```shell
git clone https://github.com/avatown/avatown-docs.git
cd avatown-docs
```

### 🛠 2. Create a New Branch
Create a feature or fix branch:

```shell
git checkout -b feature/update-docs
```

### 🔍 3. Make Changes & Test
- Edit the necessary .mdx or .json files.
- Run mintlify dev to preview your changes locally.

### ✅ 4. Commit & Push
Commit your changes with a meaningful message:

```shell
git add .
git commit -m "Updated API reference for Unity Client"
git push origin feature/update-docs
```
### 🔄 5. Submit a Pull Request
Create a pull request (PR) to merge your changes into the main branch. A reviewer will review and approve your contribution.

***

### 📬 Need Help?
If you have any questions or run into issues, reach out via:

- GitHub Issues: Open an issue here

- Thank you for contributing to Avatown Docs! 🚀🎉