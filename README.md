# Prism Break - Multi-Project Manager

A cyberpunk-themed project management tracker that lets you manage multiple projects with weighted task completion, beautiful visual exports, and persistent data storage.

## Features

### 🎯 Multi-Project Dashboardyber
- Create unlimited projects with start dates and target completion dates
- Real-time completion percentage tracking per project
- Interactive task checkboxes directly in project cards
- Responsive grid layout for all screen sizes
- Beautiful cyberpunk aesthetic with neon colors and scanline animations

### ⚖️ Intelligent Weight System
- Allocate project work as percentages (0-100%)
- Steps must total exactly 100% per project
- Real-time validation prevents invalid configurations
- Progress calculated by completed weight, not step count
- Visual indicator showing total weight allocation (Total: 65% / 100%)

### 📊 Visual Exports
- **Dashboard Export**: Beautiful HTML view of all projects with summary statistics
- **Project Export**: Detailed project visualization with progress bars, weight breakdown, and task status
- Print-friendly layouts for sharing and reporting
- Animated headers with glowing effects
- Mobile-responsive design

### 💾 Data Management
- **JSON Export**: Backup all projects as JSON for data portability
- **JSON Import**: Restore projects with duplicate detection and merge strategy
- **LocalStorage**: Automatic persistence (survives browser refresh)
- **Reset Dashboard**: Clear all projects with double-confirmation safety

### 📅 Smart Calendar System
- Month and year dropdown pickers for quick date navigation
- Previous/Next/Today buttons for convenience
- Single-click date selection
- Supports any year range

### ✨ Task Management
- Add unlimited steps per project
- Allocate percentage weight to each step
- Mark tasks complete with checkboxes
- Strikethrough visual feedback
- Edit and delete steps anytime
- Add/remove steps without losing data

### 🔒 Safety Features
- Double-confirmation on destructive actions (reset)
- Validation prevents projects exceeding 100%
- Error handling for file imports
- User feedback with alerts and confirmations

## How to Use

### Create a Project
1. Click **+ NEW PROJECT**
2. Enter project name, start date, target completion date
3. Add a description (optional)
4. Add steps with percentage weights (must total 100%)
5. Click **SAVE PROJECT**

### Track Progress
1. View all projects on the dashboard
2. Click checkboxes on steps to mark complete
3. Watch completion % update in real-time
4. Progress bar fills as you complete weighted tasks

### Export
- **📊 EXPORT VISUAL**: Download beautiful HTML of entire dashboard
- **📊 VISUAL** (on project): Download detailed project report
- **📤 EXPORT JSON**: Backup all projects as JSON file
- **📥 IMPORT**: Restore projects from JSON file

### Reset
1. Click **⚠ RESET ALL** (red button)
2. Confirm deletion (twice for safety)
3. All projects cleared
4. Start fresh

## Technical Details

### Stack
- Pure HTML5/CSS3/JavaScript
- No external dependencies
- Single-file deployment
- Works offline

### Data Storage
- **Browser LocalStorage**: Automatic persistence
- Projects stored as JSON in browser
- Clear on reset, preserved on import
- Survives browser refresh

### Export Formats
- **HTML**: Standalone files with inline CSS
- **JSON**: Data interchange format for backup/restore
- All exports include metadata and timestamps

### Browser Support
- Chrome/Edge: ✓ Full support
- Firefox: ✓ Full support
- Safari: ✓ Full support
- Mobile browsers: ✓ Responsive design

### Performance
- File size: ~50 KB
- Fast rendering for 100+ projects
- Smooth animations and transitions
- Optimized for mobile and desktop

## Design

### Cyberpunk Aesthetic
- Neon cyan (#00d4ff), magenta (#ff006e), bright green (#39ff14)
- Dark gradient backgrounds
- Scanline animations
- Glowing effects and shadows
- IBM Plex Mono monospace font

### Responsive Layout
- Mobile-first design
- Auto-adjusting grid
- Touch-friendly controls
- Print-optimized exports

## Use Cases

- **Project Managers**: Track multiple concurrent initiatives
- **Team Leads**: Monitor project progress and dependencies
- **Freelancers**: Manage client projects and deliverables
- **Product Teams**: Organize feature development with weighted priorities
- **Students**: Organize assignments and study projects
- **Personal Projects**: Track hobbies and side projects

## File Structure

```
prism-break-timetracker.html
├── HTML Structure
│   ├── Dashboard header
│   ├── Control buttons
│   ├── Project grid
│   └── Modal dialogs
├── CSS Styling
│   ├── Cyberpunk theme variables
│   ├── Animations (scanlines, glow)
│   ├── Responsive grid layout
│   └── Print styles
└── JavaScript (23 functions)
    ├── Project CRUD operations
    ├── Weight validation
    ├── Calendar system
    ├── Export/import handlers
    ├── localStorage management
    └── DOM rendering
```

## Getting Started

1. Download `prism-break-timetracker.html`
2. Open in any web browser
3. Start creating projects
4. Data automatically saves to browser storage

No installation, no server, no dependencies.

## Keyboard Shortcuts

None required - fully mouse/touch driven for accessibility.

## Limitations & Notes

- Data stored in browser LocalStorage (not synced across devices)
- Export JSON for cross-device backup
- Reset is permanent (no undo)
- Maximum practical projects: 100+ (tested and performant)

## Tips & Tricks

- Use step percentages to weight tasks by effort/importance
- Export JSON periodically as backup
- Print exports for physical tracking
- Share exported HTML files with team members
- Use dates strategically to track project milestones

## Changelog

### v1.0 - Initial Release
- Multi-project dashboard
- Percentage-based weighted tasks
- Visual exports (dashboard & project)
- JSON export/import with backup/restore
- LocalStorage persistence
- Reset with safety confirmation
- Month/year calendar pickers
- Task completion tracking
- Mobile responsive design
- Double-confirmation on destructive actions

## License

This project is provided as-is for personal and commercial use.

## Author

Created as a cyberpunk-themed productivity tool with a focus on beautiful design and intuitive project management.

## Support

All features are self-contained in the single HTML file. No external APIs or services required.

For data backup: Use JSON export feature before clearing or resetting.

---

**Prism Break** - Decompose & Track Project Components

*A standalone, offline-first project manager with beautiful visual exports and intelligent weight-based task completion.*
