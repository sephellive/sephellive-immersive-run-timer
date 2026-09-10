# Changelog

## 1.5.7
- Raised the Radiation Rig timer readout by 2 pixels.

## 1.5.6
- Raised the Artifact Detector timer readout by 2 pixels.

## 1.5.5
- Raised the Field Chrono readout by a further 2 pixels.

## 1.5.4
- Moved the Field Chrono readout up by 4 pixels to compensate for Letterica's low glyph baseline.

## 1.5.3
- Centred the Field Chrono timer text against the full frame width.

## 1.5.2
- Plain Text now uses left alignment, so X=0 places the visible timer text flush with the left edge.

## 1.5.1
- Centred the timer text inside the Field Chrono frame.

## 1.5.0
- Replaced the unsupported long dash in English and Russian live-positioning headings with a safe hyphen.
- Slightly increased the Radiation Rig frame height and re-centred its timer text for better proportions.

## 1.4.0

- Reduced all illustrated timer layouts to 60% (154x48) and proportionally resized the text areas.
- Reduced the Plain Text base size to the same compact scale; its MCM slider remains available for enlargement.
- Rebuilt the five frame silhouettes to connect fragmented details into coherent, shaped backings.

## 1.3.0

- MCM X/Y and text-size values are now polled by the real HUD every frame, including inside live positioning.
- Rebuilt all frame alpha masks: no rectangular black backdrop in-game, but a shaped shadow and readable dark timer inset remain.
- Rebuilt FOMOD preview images with a dark display background.

## 1.2.0

- Added complete English and Russian MCM localisation.
- Rebuilt live positioning after fixing the MCM-to-HUD reference; X/Y now move the actual active timer.
- Added an in-game live-positioning controller, based on the Popup Messages workflow.
- Removed opaque background pixels around the illustrated frames.
- Restored the **Plain Text** FOMOD choice; its font size is adjustable from 1 to 4 in MCM.

## 1.1.0

- Replaced the plain frame with five hand-crafted, illustrated Zone UI frames.
- Every FOMOD choice includes an image preview and a layout calibrated to keep the timer within its centre panel.

## 1.0.1

- MCM page is now provided by a dedicated `_mcm` script and appears as **Immersive Run Timer**.
- First launch now initializes from Anomaly's current playthrough time, matching the original NewRunTimer behaviour.

Document notable addon changes here when needed. GitHub generated release notes provide the per-release commit summary.
