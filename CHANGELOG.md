# Changelog

## [Enhanced Reset Functionality] - 2025-06-30

### Added
- Enhanced reset functionality for charter costs in booking management
- Always-visible reset button with smart state indicators
- Dual reset buttons (header and footer) for better accessibility
- Real-time pricing refresh from configuration
- Visual feedback for override status and loading states
- Improved error handling with fallback strategies

### Changed
- Reset button now always visible (not just when overridden)
- Button color changes based on override status (blue/orange)
- Enhanced user feedback with status indicators
- Improved reset logic with fresh data fetching

### Features
- 🔄 **Smart Reset Buttons**: Different colors and text based on current state
- ⚠️ **Override Indicators**: Clear visual feedback when costs are manually modified
- 💡 **Status Feedback**: Shows whether costs are from configuration or manual input
- 🔄 **Fresh Data Fetch**: Always gets latest pricing from configuration
- ⏳ **Loading States**: Visual feedback during reset operations
- 🛡️ **Error Recovery**: Graceful handling of network/database issues

### Technical Details
- Enhanced `resetToDefault()` function with better error handling
- Added `hasAnyOverrides` state tracking
- Improved user feedback with loading indicators
- Added tooltips for button clarity
- Robust fallback mechanisms for pricing data

### Benefits
- ✅ **Always accessible** - Reset button visible even without overrides
- ✅ **Real-time pricing** - Fetches latest configuration data
- ✅ **Clear feedback** - Users know when costs are from config vs. manual
- ✅ **Robust handling** - Works even if pricing config is incomplete
- ✅ **Visual clarity** - Different button colors show current state