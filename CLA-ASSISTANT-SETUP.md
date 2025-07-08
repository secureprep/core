# Setting up CLA Assistant for SecurePrep

## 1. Visit CLA Assistant
Go to https://cla-assistant.io and sign in with your GitHub account.

## 2. Add Repository  
Click "Configure CLA" and add your repository:
- Repository: `secureprep/core`
- CLA URL: https://gist.github.com/tuannguyenvku/935c0b214d95d5ad5344e083032c1456

## 3. Configure Settings
- **Enable CLA Assistant**: Check the box
- **CLA Version**: 1.0
- **Custom Fields**: Leave empty for now
- **Whitelist**: Add collaborators who don't need to sign (optional)

## 4. Test Setup
1. Create a test pull request from a different account
2. CLA Assistant should automatically comment
3. The PR should be blocked until CLA is signed

## 5. Update Repository Settings
Add the CLA Assistant webhook manually if needed:
- Go to repository Settings > Webhooks
- Add webhook: https://cla-assistant.io/webhooks
- Content type: application/json
- Events: Pull requests

## 6. Badge Setup
The CLA badge is already in README.md:
```
[![CLA status](https://cla-assistant.io/repos/secureprep/core/badge.svg)]()
```

## Important Notes
- Contributors will see the CLA in PR comments
- Once signed, they won't need to sign again for future PRs
- You can view signatures at https://cla-assistant.io/secureprep/core
- Make sure the gist is public and accessible

## Manual Steps Required
1. Visit https://cla-assistant.io
2. Sign in with your GitHub account (must be repo owner/admin)
3. Click "Configure CLA"
4. Add repository: secureprep/core
5. Enter CLA URL: https://gist.github.com/tuannguyenvku/935c0b214d95d5ad5344e083032c1456
6. Save configuration
