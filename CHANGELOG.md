Change Log
==========

### Ver. 2.3.1 (15/09/25)
- Fix inconsistent DirectX mode
- Low level Ver. Ver. 1.7.23 (17/9/25)

### Ver. 2.3.0 (31/08/25)
- Add support for AV1 in mpegts  
 Low level Ver. 1.7.22 (31/8/25)
- Add support for MPEG TS Demux with AV1

### Ver. 2.2.15 (28/08/25)
- Fix Option dialog opening with expired license

### Ver. 2.2.14 (16/06/25)
 Low level Ver. 1.7.15 (15/6/25)
- Fixing the pid name detection in the demux filter

### Ver. 2.2.13 (02/06/25)
- Replace manual with mkdocs
- Increase accuracy in vmti target tag 17

### Ver. 2.2.12 (14/05/25)
- MISB 601. Add tag 140 (WeaponsStores)
- Add Node info QR code presentation

### Ver. 2.2.11 (12/05/25)
- Low level Ver. 1.7.13 (11/5/25)
	- Fix decoder state machine stability while playing corrupted content

### Ver. 2.2.10 (27/04/25)
- Fix VMTI target presentation (edge case)
- Low level Ver. 1.7.12
	- Fixing failure in DirectX image resizing in some computers

### Ver. 2.2.9 (10/04/25)
- Low level Ver. 1.7.11 (9/4/25)
	- Fix exception on decoding stop 

### Ver. 2.2.8 (03/04/25)
- Low level 1.7.10 
	- Fixing demux of h265 with bad syntax

### Ver. 2.2.7 (16/0/25)
- Fix recast license

### Ver. 2.2.6 (16/0/25)
- Update low level to v4.2.6
- Fix VMTI overlay expiration
- Configurable VmtiExpireTimeout 

### Ver. 2.2.5 (24/02/25)
- Replace x32 h264 encoder with x64
- low level Ver. 1.7.9 (23/2/25)
	- Added API for enable/disable transport discontinuity events (default is ignore discontinuity)

### Ver. 2.2.4 (19/02/25)
- Replace x32 h264 encoder with x64
- low level Ver. 1.7.8 (19/2/25)
	- Fixed resolution detection in HEVC
	- supporting synthetic video insertion and dynamic input resolution change in encoder
	- fixing a regression bug in video capture mode
	- Supporting aspect ration dynamic change in encoder

### Ver. 2.2.2 (4/02/25)
- Add RTP mode with m2t, h264, h265, av1
- low level
 - Adding support for AV1 in RTP input and in decoding
 - AV1 stabilization fixes
 - Detection fix

### Ver. 2.2.0 (12/01/25)
- low level
 - Upgrading ffmpeg to 5.1.2
 - Use Filters v1.7

### Ver. 2.1.5 (29/12/24)
- low level
 - fix playback stability in switch sources
 - improve time jumps resync handling

### Ver. 2.1.4 (15/11/24)
- low level
	- support decoding of H265 with P10 pixel format

### Ver. 2.1.2 (16/10/24)
- Fix JWT license apply. No need to restart
- low level
	- Fix RTSP if more than 4 tracks
	- Fix Directx renderer dead-lock in low delay

### Ver. 2.1.1 (10/09/24)
- low level modifications
	- Comply with H264 SEI NAL in the beginning of PES

### Ver. 2.1.0 (12/07/24)
- low level modifications
- MisbCore VMTI modifications
	- Add MISB903.6 support 

### Ver. 2.0.2 (26/05/24)
- Add patch enabling Klv presentation for wrongly formated packets
- Improve time accuracy in KlvConditionsTable in stservercontrols. Now allows to specify seconds and milliseconds
- Add HW acceleration selection
- Add Hardware Accelerating Device Number

### Ver. 2.0.1 (4/05/24)
- Remove file playback option from license - make it always true

### Ver. 2.0.0 (4/05/24)
- Move Low level to .Net 4.7.2 - StCore 4.0.2
- Add JWT license
 low level 
	- Fix pause handling in VideoOverlayMixer
	- improve D3d video renderer performance
	- Add delay option in videoOverlayMixer
	- Add option to override aspect ratio in VideoOverlayMixer
	- Improvements in presentation filters
	- Initial latency configuration fixes
	- Fix aspect ratio handling
	- Improve logging of monitored events (specifically for video renderer)

- Modify low level 
	- Add delay option in videoOverlayMixer
	- Add option to override aspect ratio in VideoOverlayMixer
	- Improvements in presentation filters

### Ver. 1.12.7  (28/04/24)
- Modify low level 
	- Add delay option in videoOverlayMixer
	- Add option to override aspect ratio in VideoOverlayMixer
	- improvements in presentation filters

### Ver. 1.12.6 (26/03/24)
- Modify NodeInfo format (SDK)
Low level:
- Improving performance in D3d rendering
- Fixing VideoOverlayMixer in handling I420 pixel format

### Ver. 1.12.4 (24/03/24)
- Update MisbCore
	- Remove length from VMTI Location (tag 17)
	- Remove length from VMTI Velocity and Acceleration DLP 

### Ver. 1.12.3 (12/03/24)
 - DirectX mode playback improvements
 - Add PreferEvrOnVmr9 option

### Ver. 1.12.2 (10/03/24)
Low level changes:
- Add support for EVR renderer
- Add debug monitoring points for D3D9 Renderer
- Add an ini patch to disable footer search. To use it, 
To activate the patch, DemuxFilter.ini containing the following should be copied to Filters folder
[Parsing]
FooterSearchIsDisabled=1

### Ver. 1.12.1 (22/02/24)
- Update low level
- Add option for async callback of sync frames
- Modify StCore interface

### Ver. 1.11.17 (15/02/24)
- Update low level

### Ver. 1.11.16 (11/02/24)
- Added new property in IStCoreWr - SequenceHeaderInsertionIntervalMsec
- Update low level

### Ver. 1.11.10 (14/12/23)
- Low level update. 

### Ver. 1.11.9 (13/12/23)
- Low level update. 

### Ver. 1.11.8 (07/12/23)
- Low level update. Quicksync related
- Disable config editing if not stopped.
- Add initial configuration loading with argument
- Add support for nic 0.0.0.0 to recorder
- Increase recaster buffer size to 8mb

### Ver. 1.11.7 (12/10-/23)
- Fix long VMTI tracker (over 14 items)

### Ver. 1.11.6 (05/09/23)
- Report MouseDown and MouseMove if only screen coordinates are available

### Ver. 1.11.5 (03/09/23)
- Move HiddenButtons Settings to the application scope
- Make websocket reporting for MouseMove event optional

### Ver. 1.11.4 (23/08/23)
- Low level update (StCore 3.10.3) 
- Support the sps information provided in an rtp packet with a format STAP-A 
- Fix the SequenceHeaderInsertionOnKeyFrames property did not reach its destination in the DVR mode
- Add SequenceHeaderInsertionOnKeyFrames (default true) to config file
- Enable back DVR mode for rtsp

### Ver. 1.11.3 (17/08/23)
- Fix rtsp playback. Disable DVR mode for rtsp

### Ver. 1.11.2 (11/08/23)
- Add lastPacketGeoJson endpoint to the websocket interface
- Add lastPacketGeoJson endpoint to the REST interface
- Hide pre-confugured buttons. REST interface commands 

### Ver. 1.11.1 (14/06/23)
- Add websocket interface
- Add initial app window pos control (via args) 
- Fix BER-OID Encoding/Decoding for VMTI Target ID

### Ver. 1.10.1 (27/06/23)
- Low level update. Decoder memory leak fix

### Ver. 1.10.0 (23/05/23)
- Low level update. FFmpeg version change
- Add api for configuring decoding hw acceleration type

### Ver. 1.9.5 (11/05/23)
- Recorder update (HEVC I-frame manifest)

### Ver. 1.9.4 (11/05/23)
- License time server
- Fix HLS HEVC recording

### Ver. 1.9.3 (01/02/23)
- Implement JWT for secure HLS access for StanagOnDemand server
- Update StServer web controls.
- Update low level (StCore 3.9.7)

### Ver. 1.9.2 (01/02/23)
- Add VChip support (to VMTI metadata)

### Ver. 1.9.1 (10/22)
- Add command line arguments
- Low level update (3.9.2)

### Ver. 1.9.0 (08/22)
- Update klvView. Remove quotes on tags
- Add KlvBreakpoints (KlvConditionsWindow in KlvView)

### Ver. 1.8.3 (22/08/22)
- Fix clip cut/export (no pts) 

### Ver. 1.8.2 (14/08/22)
- Update MisbCore (fix VMTI target id)

### Ver. 1.8.1 (09/08/22)
- Add tag 122, 138, 139
- Low level update 

### Ver. 1.8.0 (07/08/22)
- Add tags 115, 116, 121, 128
- Low level update 

### Ver. 1.7.10 (03/07/22)
- Set AudioMayBeMissing property to default true. (False prevented some files from playing)

### Ver. 1.7.9 (29/06/22)
- Low level update (memory leak)
- Fix window size on expire 

### Ver. 1.7.8 (26/06/22)
- New nodeinfo implementation
- Add Error handing in case the configuration file creation failed (disk full)

### Ver. 1.7.7 (22/06/22)
- Add support for on-the-fly video resolution change.

### Ver. 1.7.6 (20/06/22)
- Prevent passing packets for map presentation if no geo info present in it.
- Update Map control

### Ver. 1.7.5 (14/06/22)
- Update vmti targets map presentation
- StServerUtils rewrite to async methods due to restsharp breaking changes
- Integrate updated StServerUtils
- Fix user manual typos

### Ver. 1.7.4 (05/22)
- Fix crash on null m_MainWindow.GetStServerUtils

### Ver. 1.7.3 (09/05/22)
- Fix VMTI overlay drawing with incomplete tracker
- Rewrite StServer integration with StServerUtils dll

### Ver. 1.7.2 (28/04/22)
- Implement mission video coverage query in VOD mode from StServer
- Add StServer Area and heatmap query
- Update low level

### Ver. 1.7.1 (12/04/22)
- Add timestamp and "Save packet option" to Bookmarks
- Version Update check from github 
- Update low level

### Ver. 1.7.0 (06/04/22)
- Add Bookmarks
- Fix stserver url persistence

### Ver. 1.6.5 (27/02/22)
- Update MisbCore (VObject)

### Ver. 1.6.4.1 (19/12/21)
- Update overlay target presentation

### Ver. 1.6.4 (19/12/21)
- Update MisbCore ( VMTI update )
- Update low level. DirectX renderer

### Ver. 1.6.3 (24/11/21)
- Update recorder runtime to v142
- Boost v142
- STANAG Player SDK v3.8.10
- Fix file cut mode
- Add time restricted license support

### Ver. 1.6.2 (10/11/21)
- Update VS runtime to v142

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



    