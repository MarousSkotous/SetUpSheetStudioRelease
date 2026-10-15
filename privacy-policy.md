# Privacy Policy — Setup Sheet Studio

Effective date: 16 October 2026

Setup Sheet Studio processes CAM data locally on the user's computer. The
Autodesk Design and Make Marketplace distribution does not transmit document,
CAM, tool, company-profile or generated-report data to the publisher or to a
third party.

## Data accessed

When requested by the user, the add-in reads setup, operation, tool, stock,
WCS and viewport information from the active Autodesk Fusion document through
the public Fusion API. The information is used only to display the preview and
generate the local report.

## Local storage

Saved company information, logo, theme, layout and report profiles are stored locally in:

- Windows: `%APPDATA%\CCSoft\SetupSheetStudio\`
- macOS: `~/Library/Application Support/CCSoft/SetupSheetStudio/`

The same location may contain a diagnostic log with application/Fusion
version, operating system and error information. Document content and CAM data
are not intentionally written to the log.

## Network communication

The Marketplace package contains no external updater and does not make network
requests. Updates to this distribution are delivered through Autodesk
Marketplace after Autodesk review.

The separately distributed direct-download edition can check the publisher's
public GitHub release repository and download a platform installer. That
updater is not included in the Marketplace submission package.

## Analytics, advertising and accounts

The add-in contains no analytics, advertising, crash-reporting SDK, Autodesk
account integration or licensing/entitlement service. No personal information
is sold or shared.

## Contact

Questions about this policy can be sent to m.skotak@ccsoftcz.com.
