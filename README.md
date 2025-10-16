## 🚀 42 Project Template Repository

This template is designed for 42 projects development. It integrates a pre-defined GitHub Actions workflow.

The workflow includes:
- Testing sequence (with Francinette and Norminette)
- Personal testing you can configure yourself
- Automatic sync of the code to the **Vogsphere**

### ⚙️ 1. Project Setup
Fork this repository.

Configure 2 repo private variables:
- **SSH_PRIVATE_KEY** > Your 42 ssh private key
- **VOG_REPO_LINK** > The link of the 42 project repo

Work on the project

### 🧪 2. Workflow
This repository includes a GitHub Actions workflow (.github/workflows/libft_test.yml) that runs Francinette on every push to any branch.

Every push on **vogsphere** branch will push the code to your 42 vogsphere session.