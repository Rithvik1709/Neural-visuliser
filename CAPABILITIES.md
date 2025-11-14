# What I Can Do - AI Coding Agent Capabilities

Hello! I'm an advanced AI coding agent designed to help you work with code repositories. Here's what I can do to help you with the **Neural Network Visualizer** project:

## 🎯 General Capabilities

### Code Development
- **Write and modify code** in multiple programming languages (JavaScript, Python, HTML, CSS, etc.)
- **Debug existing code** by analyzing errors and proposing fixes
- **Add new features** based on your specifications
- **Refactor code** to improve readability, performance, or maintainability
- **Fix bugs** identified in issues or through testing

### Testing & Validation
- **Run existing tests** to verify functionality
- **Create new tests** to cover new features or edge cases
- **Debug test failures** and fix underlying issues
- **Perform integration testing** by running the application

### Documentation
- **Write or update documentation** (README files, code comments, API docs)
- **Create usage examples** and tutorials
- **Document API endpoints** and function interfaces
- **Generate changelog entries** for new releases

### Repository Management
- **Analyze repository structure** to understand project organization
- **Review code changes** before committing
- **Create and manage git branches** (already on `copilot/add-new-features`)
- **Handle merge conflicts** when needed
- **Manage dependencies** (npm, pip, etc.)

### Build & Deployment
- **Run build processes** (bundlers, compilers, etc.)
- **Execute linters and formatters** to maintain code quality
- **Test deployment scripts** like your `deploy.sh`
- **Set up development environments**

## 🧠 Specific to This Neural Network Visualizer

### Frontend Development (Three.js Visualization)
- Modify the 3D neural network visualization in `assets/main.js`
- Update UI components and styling in `assets/main.css`
- Add new interactive features to the drawing grid
- Enhance the prediction chart display
- Improve responsive design for different devices
- Add new visualization modes or effects

### Backend/Training (Python)
- Modify the training script `training/mlp_train.py`
- Experiment with different network architectures
- Add new export formats or checkpoints
- Optimize training performance
- Add support for additional datasets
- Implement new activation functions or layers

### Integration & Features
- Connect the frontend to new weight exports
- Add timeline scrubbing functionality
- Implement new color schemes
- Add keyboard shortcuts
- Create interactive tutorials
- Add accessibility improvements (ARIA labels, keyboard navigation)

### Internationalization
- Improve or extend the German-to-English translation in `index.html`
- Add support for additional languages
- Extract hardcoded strings for localization

### Performance Optimization
- Optimize 3D rendering performance
- Reduce bundle sizes
- Improve loading times
- Add lazy loading for timeline snapshots
- Profile and optimize bottlenecks

## 🔍 Analysis & Understanding

I can help you understand:
- **How the neural network works** - the MLP architecture and forward pass
- **How Three.js renders** the 3D visualization
- **Weight loading and processing** from JSON exports
- **The training pipeline** from MNIST to browser
- **Connection highlighting logic** (top-N strongest connections)
- **Color encoding** for activations and weights

## 🚀 Examples of What I Can Do Right Now

### Feature Additions
```
"Add a screenshot/download feature for the 3D visualization"
"Implement a dark mode toggle"
"Add support for custom MNIST images via file upload"
"Create an animation when switching between timeline checkpoints"
"Add a reset camera view button"
```

### Bug Fixes
```
"Fix the mobile touch controls on iOS"
"Resolve memory leaks in the 3D scene"
"Fix timeline slider not updating properly"
"Correct the prediction chart overflow on small screens"
```

### Improvements
```
"Make the brush size adjustable in real-time"
"Improve the neuron detail panel with more statistics"
"Add tooltips explaining what each control does"
"Optimize the connection rendering for larger networks"
"Add keyboard shortcuts (e.g., 'R' to reset, 'D' for dark mode)"
```

### Testing & Quality
```
"Run the local development server and verify functionality"
"Check for console errors or warnings"
"Test the application on different screen sizes"
"Validate the training script works correctly"
"Run any existing linters or formatters"
```

## 🛠️ How to Work With Me

### Be Specific
Instead of: "Make it better"
Try: "Add a button to download the current visualization as a PNG image"

### Provide Context
If something isn't working, tell me:
- What you expected to happen
- What actually happened
- Any error messages you see
- Steps to reproduce the issue

### Iterative Development
I can work incrementally:
1. You request a feature
2. I implement a basic version
3. You provide feedback
4. I refine based on your input
5. We iterate until it's perfect

### Testing Capabilities
I can:
- Run your local development server
- Execute Python training scripts
- Test the visualization in a browser environment
- Take screenshots to show you the results
- Run automated tests if they exist

## ⚠️ Limitations

### What I Cannot Do
- Access external APIs or databases (limited internet access)
- Push directly to GitHub main branch (I work on feature branches)
- Run GUI applications that require display output (but I can test web apps)
- Install system packages that require root access
- Access files outside this repository

### What I Must Not Do
- Commit secrets or credentials to the repository
- Introduce security vulnerabilities
- Remove working code without good reason
- Break existing functionality
- Violate copyright or generate harmful content

## 📝 Current Repository Status

**Branch:** `copilot/add-new-features`
**Last Commit:** Initial plan
**Project:** MNIST MLP Visualizer - Interactive 3D neural network visualization

The repository is clean and ready for changes. I can help you implement new features, fix bugs, improve documentation, optimize performance, or anything else you need!

## 💡 What Would You Like Me To Do?

Just tell me what you need! Some ideas:
- "Add a feature that..."
- "Fix the bug where..."
- "Improve the performance of..."
- "Document how to..."
- "Test whether..."
- "Help me understand..."

I'm here to help make this Neural Network Visualizer even better! 🚀
