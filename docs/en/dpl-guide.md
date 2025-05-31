# DPL-1.0 Usage Guide

The DJYX Permissive License (DPL-1.0) is designed for maximum compatibility and ease of use.

## Key Features

- ✅ **Commercial Use**: Freely use in commercial projects
- ✅ **Modification**: Modify source code without restrictions
- ✅ **Distribution**: Distribute original or modified versions
- ✅ **Private Use**: Use privately without disclosure
- ⚠️ **Art Assets**: Require modification before use

## Requirements

### Attribution
You must include:
1. Original author name
2. Original project URL
3. Copyright notice
4. Disclaimer

### Art Assets
- Direct use of logos, images, graphics is prohibited
- Modification of art assets is encouraged
- You may incorporate design elements from original logos

## How to Apply DPL-1.0

### Step 1: Add License File
Copy the [DPL-1.0 license text](../../licenses/DPL-1.0-LICENSE.md) to your project's `LICENSE` file.

### Step 2: Update Copyright
Replace placeholders:
```
Copyright (c) [YEAR] [AUTHOR_NAME]
```

### Step 3: Add File Headers
```javascript
/*
 * Copyright (c) 2025 Your Name
 * 
 * SPDX-License-Identifier: DPL-1.0
 * Licensed under the DJYX Permissive License 1.0
 */
```

### Step 4: Add Badge
```markdown
![License: DPL-1.0](https://img.shields.io/badge/License-DPL--1.0-blue.svg)
```

## Examples

### Package.json
```json
{
  "name": "your-project",
  "license": "DPL-1.0",
  "licenses": [
    {
      "type": "DPL-1.0",
      "url": "https://github.com/your-repo/LICENSE"
    }
  ]
}
```

### README Template
```markdown
## License

This project is licensed under the DJYX Permissive License 1.0 - see the [LICENSE](LICENSE) file for details.

### Attribution
- Original Author: [Author Name]
- Project URL: [Repository URL]
```

## Best Practices

1. **Clear Attribution**: Always provide clear attribution in documentation
2. **Art Asset Guidelines**: Create new visual assets inspired by originals
3. **License Compatibility**: DPL-1.0 is compatible with most other licenses
4. **Documentation**: Include license information in your project documentation

## FAQ

**Q: Can I use DPL-1.0 code in proprietary software?**
A: Yes, with proper attribution.

**Q: Do I need to open source my modifications?**
A: No, but attribution is required.

**Q: Can I change the license of my derivative work?**
A: Yes, DPL-1.0 allows relicensing.
