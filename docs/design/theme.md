# Theme

[← Design index](README.md) · `Assets.xcassets`, `Main.storyboard`

## Appearance

The app is **light mode only**. `INFOPLIST_KEY_UIUserInterfaceStyle = Light` is set in the project build settings. The color assets do define dark variants (white), but they are never used. The tint color is the iOS default system blue, used for nav bar buttons, the selected tab and links.

## Color assets

| Asset | Light value | Used for |
|---|---|---|
| `color_walk_start_button` | #B9CBFF | Start/Stop button background |
| `color_map_path` | #0E54FF | Walk route polyline (Log a Walk, Walk Details) |
| `color_leaderboard_rank_0` | #FFD700 | 1st place card |
| `color_leaderboard_rank_1` | #C0C0C0 | 2nd place card |
| `color_leaderboard_rank_2` | #CD7F32 | 3rd place card |
| `color_leaderboard_rank_3+` | #E1E2ED | All other leaderboard cards |

## Colors set directly in the storyboard

| Color | Used for |
|---|---|
| `#674FA4` (custom RGB 0.404, 0.314, 0.643) | Primary buttons |
| `systemBackgroundColor` | Screen backgrounds |
| `systemRedColor` | Validation messages |
| `linkColor` | Phone/email links on Contact Us |
| black 25% / 50% | Mask behind modal cards and the sidebar |

## Typography

The system font (San Francisco) in fixed point sizes. Dynamic Type is not used.

| Size | Typical use |
|---|---|
| 25 pt | Modal card titles |
| 17 pt (regular/semibold) | Nav titles, Contact Us text, sidebar items |
| 15 pt medium | Leaderboard segmented controls, Retake |
| 13–14 pt (bold for buttons) | Body text, buttons, form fields |
| 10 pt | Validation messages, Start/Stop title |

## Icons

Vector icons in `Assets.xcassets`, mostly the same Material Symbols SVGs the Android app uses (`image_walk`, `image_bar_chart`, `image_newspaper`, `image_menu`, `image_user`, `image_edit`, `image_share`, `image_camera`, `image_flag_checkered`, `image_info`, `image_warning`, and the sidebar icons). There are also map markers (`image_trip_origin`, `image_trip_destination`), `image_rainbow_bg` for Login, and `image_launch_screen_icon` for the launch screen. Walk Details uses the SF Symbol `xmark`.

**vs Android:** Android uses Material 3 with dynamic (wallpaper-based) color on Android 12+ and supports dark mode. The fixed feature colors (route blue, medal colors) are the same on both platforms. See [Android theme](../../../MobileApplication/docs/design/theme.md).
