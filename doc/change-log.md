# Change Log

## [Unreleased]
### Added
- Timeline zoom controls with 0.25x to 4x scaling
- Right-click context menus for clip operations
- Improved thumbnail generation with error handling

### Changed
- Moved toolbar from floating to fixed position below preview
- Increased timeline height to 400px for better usability
- Enhanced video playback synchronization

### Fixed
- Thumbnail generation reliability issues
- Timeline scrubber accuracy during playback
- Drag and drop data serialization

## [v0.5.2] - 2024-12-XX
### Added
- Traditional timeline view with time ruler
- Separate tracks for Video, Text, and Audio
- Click-to-seek functionality on timeline
- Proportional clip width based on duration

### Changed
- Replaced bubble timeline with professional track layout
- Improved visual hierarchy and spacing
- Enhanced timeline scrubbing precision

### Fixed
- Video playback sync issues
- Timeline element positioning
- Drag and drop between components

## [v0.5.1] - 2024-12-XX
### Added
- Enhanced canvas with larger preview area (720×500px)
- Improved toolbar with better tool organization
- Drag and drop from sidebar to timeline
- Basic clip management in timeline

### Changed
- Optimized canvas sizing for better space utilization
- Improved toolbar positioning and grouping
- Better visual feedback during interactions

### Fixed
- Canvas drag and drop zones
- Video file upload handling
- Component state synchronization

## [v0.5.0] - 2024-12-XX
### Added
- Initial video format selection (16:9, 9:16, 1:1, etc.)
- Video file upload with drag and drop support
- Basic video preview with play/pause controls
- Content library with sidebar organization
- Bubble-style timeline layout
- Basic toolbar with editing tools

### Features
- Format-aware canvas sizing
- Video thumbnail generation
- Multi-section sidebar (Uploads, Text, Graphics, Audio)
- Drag and drop element placement
- Basic video playback controls

### Technical
- React-based component architecture
- TypeScript for type safety
- Tailwind CSS for styling
- HTML5 video API integration
