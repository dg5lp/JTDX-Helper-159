# JTDX-Helper-159

Important note!

When downloading the exe file, virus-alarm might occur. This is a false alarm. The FT8-Helper software use macro commands. Most virus checker cannot distinguish harmless and harmful macros, althought they are not encrypted. Upload and check the software to virustotal.com. You can trust the software.

New in JTDX-Helper-159-1

The FT8-Helper and JTDX-Helper share the most part of the source code. On this reason the manuals were merged. The WSJT-X and JTDX specific parts are marked accordingly. On this occasion the version numbering of the software has been changed. The first part of the number identifies the matching WSJTX/JTDX version, die number following the “-“ shows the actual version of the Helper. The current version for JTDX-2.2.159 the JTDX-Helper-159-1

- Selection of CQ, S/P, XCHG and MIX mode by menas of selection menu instead of dedicated Start-SP and Start-CQ buttons
- CQ+SP mode was re-named to XCHG-mode
- New MIX-mode: Combined CQ/SP-mode. If no CQ calling stationa are available, it calls CQ. MIX-mode is available for Band-Hopping
- New function: CQ=73. When in split-mode, the Helper can call stations sending 73 or RR73.
- Invalid or unwanted endings (e.g. /R) can be excluded by entering */R
- Exclude entries can be specified for both in- and outgoing calls or only for outgoing calls. Example: #DL would prevent calling DL stations, but calls from DL stations would be accepted.

==========================================================================

The FT8-Helper program was developed as macro extension for WSJT-X using the Quick-Macros program. Comparing to other FT8-Robot programs, the FT8-Helper is more “intelligent”, it interprets the received messages of WSJTX and acts according to the own pre-programmed QSO strategy. The delivered EXE file contains the licence for Quick-Macros.

Main Features:

- Works with JTDX-2.2.159 32- and 64 bit version (no derivates)
- Automatic operation in both "CQ" and "S/P" mode.
- MIX-mode: If no CQ calling stationa are available, it calls CQ
- XCHG-mode: Changes between CQ and S/P automatically with programmable intervals
- Automatic find of free frequency in CQ-mode
- Repeat RR73 if no closing 73 received. Warning if no colsing 73 received.
- Skip-Tx1: calls stations with report instead of QRA-grid.
- CQ=73. When in split-mode, the Helper can call stations sending 73 or RR73.
- Comfortable set-up of all parameter
- Easy installation
- JTDX can start with the -rig-name argument
- Opens the QRZ.com page of the station when starting a QSO
- Counts logged and broken QSOs.
- Shows the average difference between received and transmitted reports.

Various strategies for incoming and outgoing calls:

- est Priority acording the WSJT-X "Colours" settings.
- Best S/N: If Stations with the same priority received, the one with the best S/N selected
- Only DX: Minimum DX-distance can be specified in Km and Miles.
- Prefer-DX: DX stations are prefered.
- Most distance: Calls the station with the greatest distance.
- Prefer Wanted: prefixes, DXCC-entities and continents can be specified.
- Only Wanted: prefixes, DXCC.entities and continents can be specified
- Exclude stations, prefixes DXCC-entities and continents can be specified
- DXCC entities and prefixes can be excluded for outgoing and for both in/outcoming calls
- Keep-Even/Odd cycle for 6m DX-ing

Band-Hopping:

 - Programmable on daily basis
 - Two time ranges per day can be programmed
 - Operating band, mode, and strategy can be selected.

Feedback to: dg5lp@darc.de
