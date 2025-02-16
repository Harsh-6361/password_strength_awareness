# Password Strength Checker 🔐

[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](LICENSE)

A Python tool to evaluate password strength and promote security awareness.

## Features
- Score passwords based on length, character diversity, and common patterns
- Strength classification: **Weak**, **Medium**, **Strong**, **Very Strong**
- Special character validation (`!@#$%^&*(),.?":{}|<>`)

## Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/Harsh-6361/password_strength_awareness.git
   cd password_strength_awareness
   ```
2. Run the checker:
   ```bash
   python password_strength.py
   ```

## Example
```bash
Enter password: ***********
Password Score: 8/8 | Strength: Very Strong
```

## Password Criteria
| Criteria                | Points |
|-------------------------|--------|
| Length ≥ 12             | 2      |
| Uppercase letters       | 1      |
| Lowercase letters       | 1      |
| Digits                  | 1      |
| Special characters      | 1      |
| No common patterns      | 2      |

## Development
1. Create a feature branch:
   ```bash
   git checkout -b feature/improved-scoring
   ```
2. Merge changes:
   ```bash
   git checkout main
   git merge --no-ff feature/improved-scoring
   git push origin main
   ```

## Roadmap
- [ ] Add breach-check using [Have I Been Pwned](https://haveibeenpwned.com/API/v3)
- [ ] Create browser extension
- [ ] Add GUI interface

## License
MIT License - see [LICENSE](LICENSE) for details.
