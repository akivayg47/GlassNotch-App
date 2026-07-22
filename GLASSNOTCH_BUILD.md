# GlassNotch Full Fork

This is a direct fork of Boring Notch with the original functionality retained and a Liquid Glass appearance system added.

## Included
- Original Boring Notch music, calendar, mirror, file shelf, HUD and related features
- GlassNotch branding/product name
- Liquid Glass toggle and 10 presets in Settings > Appearance
- Custom tint, opacity, blur, glow and saturation controls
- Existing Launch at Login toggle in Settings > General
- Xcode 26.6 compatibility fix for the Saturation settings row
- Repaired MediaRemoteAdapter.framework symbolic links

## Open and run
1. Open `boringNotch.xcodeproj` in Xcode.
2. Select the `boringNotch` scheme and `My Mac`.
3. Use Product > Clean Build Folder.
4. Run.

The target name remains `boringNotch` internally to avoid breaking project references; the built product and display name are GlassNotch.

This fork remains licensed under GPL-3.0 and preserves the original license and notices.
