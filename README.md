# Usage Examples

### Combining Rule Sets
```bash
# For a React project, combine these rules:
cat cursor-rules/global/core.mdc cursor/rules/js.json cursor/rules/react.mdc
```

### Customizing Rules
```json
{
  "includes": ["../../cursor-rules/global/core.json"],
  "rules": {
    "maxFunctionLength": 20
  }
}
```

## Benefits
- Consistent code quality across projects
- Reduced onboarding time for new team members
- Better AI suggestions from Cursor
- Codified best practices for multiple languages
- Community-vetted standards

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch
3. Add or modify rules
4. Submit a pull request with a clear description

Before submitting, ensure your rules:
- Follow established conventions for the target language
- Include clear documentation
- Are generally applicable (not too specific to a particular workflow)

## License
MIT License - See LICENSE file for details

## Maintenance
This repository is actively maintained. Rules are updated to reflect:
- New language features
- Evolving best practices
- Community feedback and contributions

---

**Note**: These rules are guidelines, not strict requirements. Customize them to fit your specific project needs and team preferences.
