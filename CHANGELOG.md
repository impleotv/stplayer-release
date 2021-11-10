Change Log
==========
### Ver. 1.6.1.2 (04/11/21)
- Update MisbCore (user defined plugin)

### Ver. 1.6.1.1 (02/11/21)
- Update MisbCore

### Ver. 1.6.1.0 (17/10/21)
- Low level update (3.8.9)
- Add FrameAccuracyRequiresSequenceHeaders option

### Ver. 1.6.0.2 (04/10/21)
- Fix mission/sensor playback reporting to server

### Ver. 1.6.0 (12/09/21)
- StanagOnDemandServer support

### Ver. 1.5.7 (27/06/21)
- Low level update
- Fix Rvt decoding (remove hard coded write to disk)

### Ver. 1.5.6 (14/06/21)
- Add plugin support for RVT

### Ver. 1.5.7.5 (10/05/21)
- Add UseDirectX (renderer) option

### Ver. 1.5.7.4 (02/05/21)
- Remove No Source pupup

### Ver. 1.5.7.3 (27/04/21)
- Fix crash after minimize with overlay opened
- Improve detection in HLS recorder

### Ver. 1.5.7.2 (12/04/21)
- Fix HLS offset playback
- Low level update

### Ver. 1.5.7.1 (04/04/21)
- Fix HLS duration (sanity check)
- HLS split segments on discontinuity, including I frame manifest
- Low level update

### Ver. 1.5.7.0 (31/03/21)
- Fix HLS duration (with discontinuity) 
- Remove EnforcedDecoder
- Low level update

### Ver. 1.5.6.3 (24/02/21)
- Fix Json packets recasting.

### Ver. 1.5.6.2 (22/02/21)
- Move to .Net 4.7.2
- Add Timeline control
- Add Export (Cut) clip

### Ver. 1.5.6.1
- Add Hls detection info
- Update ffprobe

### Ver. 1.5.6  (8/01/21)
- Update HLS recorder. Accurate duration calculation + discountinuity
- Add ContiguousDemuxedVideo
- Low level update

### Ver.1.5.5.4  (18/01/21)

- Low level update
- HLS error handling

### Ver.1.5.5.3  (15/01/21)

- Use video segment duration in HLS recording
- Add TsOverRtp recording validation

### Ver.1.5.5.2  (11/01/21)

- Screen capture option changes
- Add snapshot REST automation

### Ver.1.5.5.1  (07/01/21

- Low level update

### Ver. 1.5.5

- Low level update
- Fix Config save

### Ver. 1.5.4.5

- Low level update

### Ver. 1.5.4.4

- Add command line stream url support

### Ver. 1.5.4.3

- Fix MpegTransportAnalyzerLib.dll

### Ver. 1.5.4.2

- Fix Tag 20 (Sensor Relative Roll Angle) validation

### Ver. 1.5.4.1

- Fix recorder stop hang without source

### Ver. 1.5.6 (05/02/21)

- Add startup logs


### Ver. 1.5.4

- Add RTSP playback
- Enable FIPS Compliant authorization

### Ver. 1.5.3

- HLS playback improvements
- Fix Klv short special values

### Ver. 1.5.2.1

- Fix MisbCore nested items 

### Ver. 1.5.2

- MisbCore and recorder updates

### Ver. 1.5.1.1

- Fix overlay timestamp

### Ver. 1.5.1

- Add DoNotDecodeKlv mode
- Low level update

### Ver. 1.5.0

- MisbCore
- Move to .NET 4.6.1
- HLS Master / I Frame manifest support
- RotateFlip snapshot
- Update recorder (replace boost asio with winsocket)

### Ver. 1.4.18

- Low level update (StCore 3.7.18)
- Movie Win32 binaries of Encoder Process to a subfolder

### Ver. 1.4.17

- Low level update (StCore 3.7.17)
- Frame Accuracy stability fixes for reverse playback

### Ver. 1.4.16

- Low level update (StCore 3.7.16)

### Ver. 1.4.15

- Low level update (StCore 3.7.15)

### Ver. 1.4.14

- Low level update (StCore 3.7.14)

### Ver. 1.4.11

- Low delay fixes
- Adding option to modify incoming PTS in Injector according to local CPU time

### Ver. 1.4.10

- Low level update
- 0.0.0.0 binding

### Ver. 1.4.10

- Low level update (StCore 3.7.10)
- Add back 2013 redistributables for Chromium
- HLS discountinuity
- Goto without stop/start upon ingest
- 0.0.0.0 nic binding

### Ver. 1.4.9

- Low level update (StCore 3.7.9)
- Vendor customisation

### Ver. 1.4.8

- Low level update (StCore 3.7.8)

### Ver. 1.4.7

- Fix recorder error message
- Fix delayed KLV start after seek
- Low level update (StCore 3.7.6)

### Ver. 1.4.6

- Fix DVR crash
- Low level update (StCore 3.7.5)

### Ver. 1.4.5

- Low level update (StCore 3.7.4)

### Ver. 1.4.4

- Low level update (StCore 3.7.3)

### Ver. 1.4.3

- Low Level Git move
- Klv2Jon changes
- Fix stuck video with wrong klv data

### Ver. 1.4.2

- Add SourceDetectionTimeoutMsec

### Ver. 1.4.1

- Low level update (StCore 3.7.1)

### Ver. 1.4.0

- BER-OID encoded tags
- Low level update (StCore 3.7.0)

### Ver. 1.3.17

- Low level update (StCore 3.6.0)
- Fix high bitrate ingest
- Fix EC_COMPLETE without video decoding

### Ver. 1.3.16

- Several low level improvements. This includes better performance in snapshot, and detection of a source timeout
- Add GEModelScale to Session options.
- XML license validation added
- Off Earth support (for KlvView and Map)

### Ver. 1.3.15

- Fix StCore release stuck
- Low lelvel update and interface change (add)
- Fix segment duration (sec instead of ms)

### Ver. 1.3.14

- Low level update (vc141 and boost 1.71)

### Ver. 1.3.13

- Low level update
- InternaUnicast2MulticastTtl default set to 0

### Ver. 1.3.12

- MISB 601 tags updates
- Overlay AllowOutsideScreenPlacement fix
- Video on second monitor fix
- Recorder updated

### Ver. 1.3.11

- Fix Session window NIC selection persistance
- MISB 601 tags updates
- H.265 opened in .ini by default

### Ver. 1.3.10

- Low level update
- Add 0601 tags
- 0903 fixes

### Ver. 1.3.9

 - InternaUnicast2MulticastRecast can be set to false in cfg file
 - PLAYER_EVENT.DEMO_EXPIRED during ingest
 - DB file lock on the second ingest

### Ver. 1.3.8

- Low Level StCore update
- HLS source failed to load fix
- Klv payload length calculation prior to checksum validation

### Ver. 1.3.7

- Low Level StCore update
- Low latency mode added
- HLS Recording "sliding window" - Max Playlist configuration

### Ver. 1.3.6

- Vmti fix

### Ver. 1.3.5.1

 - MaxDelay default set to 60 ms
 - MaxDelay default remembered between the sessions

### Ver. 1.3.5

- Full corner points added to the 104.5 transcoding
- Internal DB change (added klvJson and VideoPosition indexing)
- Export GE Tour added
- Network link now served from the internal webserver

### Ver. 1.3.4.1

- ValidateKlvChecksum added to Klv2Json

### Ver. 1.3.4

- Pcap playback
- Demux fix for video with multiple slices
- KlvView Updated
- MISB 903 Rev. 3 / Rev. 4 changes


### Ver. 1.3.3

- Supporting 10 bits per color in HEVC - decoder downscales it to regular 4:2:0 YUV

### Ver. 1.3.2

- Open HLS session added
- http hls playback fix
- Transcode104_to_601 added

### Ver. 1.3.1

- Low level StCore update
- Slider is missing in DVR Mode when switched from file to stream playback fix

### Ver. 1.3.0

- Default stream IP, Port, Cache and Timeout are set according to the last assignment.
- DVR mode integration
- TsOverRTP unicast to multicast recasting fix (Not tested)
- #EXT-X-MEDIA-SEQUENCE is set to 0 in HLS recording

### Ver. 1.2.2

- Fix Finalize in non HLS Recording mode
- GoToTime improvements, jump to start fix

### Ver. 1.2.1

- GoTo time picker is enabled right after ingest.
- Klv info extended for HLS
- Frame accuracy and FrameAccuracyBufferMsec added to Options
- Fix play delay on Seek in frame accuracy mode

### Ver. 1.2.0

- Recorder added
- Unicast recasting to local multicast
- Status bar Lat/Lon and Overlay telemetry is cleared on the Start
- ClassifyingCountry is missing in Security Metadata fix
- Low level update
- Recovering the audio master mode
- GetPosition should not jump
- Fixing SetPosition for long files (PTS wraparound)
- Reverse playback improvment

### Ver. 3.1.2

- Low level update

### Ver. 3.1.1

- GetCurrentPosition override for stream (low level returns 0 for some reason)

### Ver. 3.1.0.1

- Audio fixes for frame accuracy mode
- Audio pid selection

### Ver. 3.1.0

- IStCoreLib - interface update
- Removing the filter SyncSampleGrabberFilter, 
- Adding the following filters:
	SampleSynchronizerFilter
	SyncSampleFrameAccuracyFilter
	SyncSampleDispatcherFilter

### Ver. 1.1.2

- Low level update
- ST1204 WindowID allocation fix 

### Ver. 1.1.1

- Silent snapshot (screenshot + metadata json, geoJson, Kmz).
- Current position in stream playback fix.
- Map and KlView controls updated to the latest npm packages. 

### Ver. 1.1.0

- Major low level upgrade (frame accuracy)
- Step forward / backward
- Separate text overlay control
- Fix unticking the telemetry overlay in the settings while the master overlay is off, crashes the SW.
- Recast license bug fix
- Tag #94 (MIIS Core Identifier, MISB ST 1204) added

### Ver. 1.0.27
- Ingest Enable / disable fix
- Default Platform values are copied from the current session now.
- TS over RTP added.
- Mil symbols added
- Updated charts, jsonklv and map controls.
- Log4Net config change
- Added an option to run StPlayer with ts / m38u file argument.
- Added options to selectively control text overlay, compass, colors, etc.

### Ver. 1.0.26
- SetRate / GetRate after stop fix
- Error handling in HLS
- No Klv (for some time) after seek fix
- Fix for - illegal (no packet size / pos) data in analyzer
- Fix for - slider position does not update after seek

### Ver. 1.0.25
- KML Network Link
- Klv Recast updated
- Configuration and logs are moved from CommonApplicationData to ApplicationData
- Wrong packet saved in KlvView (during Pause)

### Ver. 1.0.24
- Map. Platfrom color, trail, line width, etc now configurable and persistent between the sessions.
- Map. Last map position is persistent.
- Map. Control activated / deactivated message removed.
- Ingest for HLS
- Fast Forward added (including HLS). For decent HLS FF must have I Frame playlist 
- Export Klv packets added to the main menu
- QueryVideoCoverage fix
- REST automation added
- Load / Save config fix
- AreaCalculated and HeatmapCalculated aded to the configuration

### Ver. 1.0.23
- Low level update
- HLS path with spaces for local playback fix
- KMZ export
- Map changes - color icons
- Platform persistency for map
- Slider behavior changed
- Klv Recasting added

### Ver. 1.0.22
- Millisecond accuracy for Klv metadata (file info - Start / End time)
- Scale added to the map
- Full screen added to the map
- Last selected platform type is assigned for new configurations
- Show / Hide trail and trail duration was added to the map
- Full screen mode added
- DTS / PTS graph for large values fix

### Ver. 1.0.21
- OTB Klv added
- VMTI targets added to map
- VMTI track added to map

### Ver. 1.0.20

- Data PTS delta chart added
- Demo restrictions added to Analyzer

### Ver. 1.0.19

- Analyzer Option added
- Play button not grayed out when no valid url exists
- Video coverage rewritten
- Multiple Klv Pid
- Ingest is done for all klv pids.
- Area calculated and saved per pid.
- Coverage query window not refreshed in STPlayer when nothing is found.
- Time parse globalization fix
- Ingest with non existing klv fix
- Ingest / Stream info of the files with spaces fix


### Ver. 1.0.18
- GoTo time added
- Klv type (SYNC/ASYNC) detection added
- Injector sampling with interval fixed
- File empty check
- Charts added
- NumberOfScaleCores added

### Ver. 1.0.17
- Ingest added
- Fixed -application would not exit with overlay closed
- Klv Pid selection

### Ver. 1.0.16
- Based on StCore 1.0.30
- HLS mode added
- GUI changes related to HLS
- Menu exit fixed

### Ver. 1.0.15
- Klv Decoder now scans for entire packet start and not just 4 bytes
- Some Stream / File license changes

### Ver. 1.0.14
- log4net.Appender MinimalLock added
- Overlay tools are now optional and not shown without proper license
- Geo (Lat / Lon) is not shown when Overlay is disabled.

### Ver. 1.0.13
- File format validation
- Target location added
- Json double fields accuracy adjusted
- MPEG extension support added
- Slider click SetPosition added


### Ver. 1.0.12
- MS Web control replaced by Chrome
- Local schema for webcontrol updated
- Fast Klv View
- Webcontrols folder structure changed

### Ver. 1.0.11
- Configurable Sync Offset added
- Duration indicator added
- Missing File Info fixed
- Recent sessions added

### Ver. 1.0.10
- PES per frame duration fixed
- Added VC 2013 runtime (setup)
- Added Save GeoJSON button
- KlvViewWindow redone
- StMonitor removed
- Low level fixes (durattion)

### Ver. 1.0.9
- Based on StCoreSDK ver 3.0.26
- Video / Klv sync (time to render)
- Klv Packet sampling
- Fix null object error on the first run

### Ver. 1.0.9
- Updates

### Ver. 1.0.7
- Map modified
- License validation fix
- Add Drag&Drop TS file
- Remove STDetector bitrate / duration detection
- Overlay is optional now.

### Ver. 1.0.6
- Map added
- Check file path for non ASCII symbols

### Ver. 1.0.5
- Stream info changed to json web control
- Self Hosting added

### Ver. 1.0.4
- Low level fixes (for ADTS and other stuff)
- Logs added.
- Log location changed
- Default config changes


### Ver. 1.0.3
- Fixed Audio
- Removed error reporting on stop (stream playback without source)

### Ver. 1.0.2
- Validations added
- Demo Session expire exit.
- Config session window modifications

### Ver. 1.0.1
- Load / Save Session Config fixed
- OutOfBand VMTI added.

### Ver. 1.0.0
- Initial version.



    