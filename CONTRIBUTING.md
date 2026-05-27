# Contributing to Tessera.io

First off, thank you for considering contributing to Tessera.io! It's people like you that make this tool such a great collaborative sandbox.

## How to Contribute

To ensure a smooth workflow and high code quality, we ask all contributors to follow these steps:

### 1. Star & Fork the Repository
- **Star the repo:** Show your support by starring the main Tessera.io repository!
- **Fork it:** Click the "Fork" button at the top right of the repository page to create your own copy.
- **Clone your fork:**
  ```bash
  git clone git@github.com:<your-username>/Tessera.io.git
  cd Tessera.io
  ```

### 2. Branching
Create a new branch for your feature or bug fix:
```bash
git checkout -b feature/your-feature-name
```

### 3. Making Changes
Make your changes in the relevant workspace(s) as described in the `README.md`. Ensure that your code follows the strict TypeScript guidelines of this repository.

Test your changes locally by running:
```bash
npm run typecheck
npm run build
npm run dev
```

### 4. Committing Your Changes (Sign-offs Required)
**IMPORTANT:** We require all commits to be signed off. The sign-off is a simple line at the end of the commit message which certifies that you wrote it or otherwise have the right to pass it on as an open-source patch. 

Use the `-s` or `--signoff` flag when you commit your changes:
```bash
git commit -s -m "feat: your descriptive commit message"
```
This will automatically append `Signed-off-by: Your Name <your.email@example.com>` to your commit message. If you do not sign off your commits, our CI pipeline will reject the pull request.

### 5. Submit a Pull Request
Once you've pushed your signed-off commits to your fork, head over to the main repository and open a Pull Request. Provide a clear description of the problem you're solving and the changes you've made.

---

## Need Help?
Look for issues tagged with `good first issue` if you're not sure where to start. We look forward to your contributions!
