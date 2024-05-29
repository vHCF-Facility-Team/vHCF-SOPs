The following is a description of vZOB Alias commands available.


These commands are specific to the vZOB facility and this document will not cover alias commands that are built-in to the CRC software; For CRC-Specific commands, please reference the CRC manual found [HERE](https://crc.virtualnas.net/docs/#/). vZOB only supports the use of CRC; All other programs will not be explained via this document.


Alias commands were once primarily used for text-to-pilot communications but these days they are used in a much more powerful manner such as the in-scope reference system. Also, with more pilots using voice capabilities, one should consider the alias command system more as a tool rather than a communication method. Therefore, to avoid confusion between tools and communication, if information is going to be sent to a pilot in any manner, the command will be prefixed with a “T" for “text" after the initial period.
See "Text to Pilots" section for context.


## COLUMNS EXPLANATION

- SYNTAX
    - How the command is formatted.
    - Unless otherwise stated, Airport ID’s (APT ID) are the FAA code, not the ICAO.
    - {== FAC ID ==} = Facility ID code
    - {== POS ID ==} = Position ID code/The computer ID code assigned to a position/controlling position.
    - Text that is {== HIGHLIGHTED ==} conveys the info that is required to be typed in that place.
    - Text that is <ins>UNDERLINED</ins> indicates that it is optional information and is not required.
    - ``(space)`` indicates when to hit the space-bar at that point.
    - Unless otherwise indicated, to complete a command, the user must press the ENTER button on their keyboard. If the term ASEL is present after the command, the user is to complete the command by first selecting the aircraft, type the alias command, then pressing their designated “Aircraft Select" key on their keyboard. Choosing an ASEL should have been part of the initial setup of your software; For more info on what the ASEL key is, consult the software manual.
- DESCRIPTION
    - Describes what happens when the command is completed or will provide an example of what is displayed.
    - If a note with a number is referenced in this box, refer to the NOTES section of this reference document for further information concerning how to effectively utilize this command.
- EXAMPLE
    - Displays an example of the command using a procedure or other variables.
- NOTES
    - TTP = This command has a "Text-To-Pilot" equivalent. Generally, all the user has to do is put a T right after the period and before starting the rest of the command and have either the aircraft selected or in a private message to that pilot.

## ZOB WEBSITE REFERENCE

|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .COMMANDS   |   Opens this Command Reference Page.   |   .COMMANDS   |      |
|   .FEEDBACK   |   Opens the ZOB “Feedback from Controllers "page to allow you to quickly report issues, requests, etc …   |   .FEEDBACK   |      |
|   .IDS   |   Opens the ZOB IDS page.   |   .IDS   |      |

## EXTERNAL SITE COMMANDS
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .ICAO   |   Opens the users default browser to the ICAO site to search aircraft codes.   |   .ICAO   |      |
|   .SEE <br> AC    |   Opens the users default browser to google images to show the selected aircrafts picture.   |   .SEEAC   |      |
|   .N# <br> FORMAT   |   Opens the users default browser to the FAA N-Number format page.   |   .N#FORMAT   |   TTP   |
|   .ID <br> FORMAT   |   Opens the users default browser to the FAA Air-Carrier telephony page.   |   .IDFORMAT   |   TTP   |
|   .ROF   |   With the aircraft selected, opens the users default browser to skyvector page and shows a direct routing between the departure and arrival airport. Reference NOTE [^1].   |   .ROF   |      |
|   .ROF <br> FA   |   With the aircraft selected, opens the users default browser to FlightAware page and depicting routes flown between the departure and arrival airport.   |   .ROFFA   |      |
|   .SKY   |   Opens the users default browser to the Skyvector site.   |   .SKY   |      |
|   .EQUIP   |   Opens the users default browser to the FlightAware FAA equipment suffix code page.   |   .EQUIP   |   TTP   |
|   .ICAO <br> EQUIP   |   Opens the users default browser to the ForeFlight equipment suffix code page.   |   .ICAOEQUIP   |      |
|   .65   |   Opens the users default browser to the FAA 7110.65 HTML page.   |   .65   |      |
|   .CHARTS <br> ``(space)`` <br> ({== APT ID ==})   |   Opens the users default browser to the AIRNAV page IFR section for the given airport ID.   |   .CHARTS {== DTW ==}   |      |
|   .TMU <br> MAP   |   Opens the users default browser to the VATUSA TMU page for ZOB.   |   .TMUMAP   |      |
|   .HOLDING <br> SHEET   |   Opens a hold tracking spreadsheet in google that allows the facility to coordinate simultaneous holding.   |   .HOLDINGSHEET   |      |

## GENERAL ASSISTANCE
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .EQUIP <br> ({== FAA EQUIPMENT SUFFIX LETTER ==})   |   Responds with a description of what capabilities the given equipment suffix has.   | .EQUIP{==L==}   |      |
|   .PRC   |   Displays a script to read to the pilot who is clearly not equipped with the knowledge or skill to complete the flight they are trying to conduct.   |   .PRC   |   TTP   |
|   .SWITCH <br> TO <br> TWR   |   Displays a script to read to the who has reached the assigned departure runway and is inquiring why they didn ’t get a switch to tower instruction.   |   .SWITCHTOTWR   |   TTP   |
|   .OVERHEAD   |   Displays a phraseology guide to use for reference when providing instructions for an Overhead Break maneuver.   |   .OVERHEAD   |      |
|   .MIL <br> CT   |   Displays specific phraseology for takeoff clearance for a USA/USN/USAF aircraft.   |   .MILCT   |   No need for TTP because the standard .TCT is formatted this way.   |
|   .MIL <br> CL   |   Displays specific phraseology for landing clearance for a USA/USN/USAF aircraft.   |   .MILCL   |   No need for TTP because the standard .TCL is formatted this way.   |
|   .RFD   |   Displays script to read to the pilot with the format for a Release-For-Departure clearance that includes a 10min void time from the current time and an advisory to contact the issuing controller no later than 15min of intentions if not off in time.   |   .RFD   |   TTP   |
|   .HOLDING   |   Displays script to read to the pilot with the format of a Holding clearance.   |   .HOLDING   |      |
|   .OTP   |   Displays a script to read to the pilot with the format of a VFR-ON-TOP clearance.   |   .TOP   |      |
|   .POS <br> CHECK   |   Displays a item list for a position relief checklist.   |   .POSCHECK   |      |
|   .AC <br> INFO <br> ({== ACFT ICAO CODE ==})   |   Returns info concerning the given aircraft.   |   .ACINFO{==B738==}  |   This is different than the .ACINFO command native to CRC.   |

## GROUND TO GROUND COMMUNICATION
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .M <br> ``(space)`` <br> ({== POS ID ==}) <br> ``(space)`` <br> (<ins>FREE TEXT</ins>)  |   With the subject aircraft selected, sends a Generic private message to the given ATC while automatically inserting the subject aircraft’s callsign.   |   .M {==D1==} {==F==} <ins>has declared MinFuel</ins> |      |
|   .RC <br> ``(space)`` <br> ({== POS ID ==}) <br> ``(space)`` <br> (<ins>FREE TEXT</ins>)  |   With the subject aircraft selected, sends a Rolling Call Notification private message to the given ATC while automatically inserting the subject aircraft’s callsign.   |   .RC {==D1E==}  <ins>RWY 21</ins>   |      |
|   .RT <br> ``(space)`` <br> ({== POS ID ==})   |   With the subject aircraft selected, sends a Rejected Takeoff Notification private message to the given ATC while automatically inserting the subject aircraft’s callsign.   |   .RT {== D1E ==}   |      |
|   .MA <br> ``(space)`` <br> ({== POS ID ==}) <br> ``(space)`` <br> (<ins>FREE TEXT</ins>)  |   With the subject aircraft selected, sends a Missed Approach Notification private message to the given ATC while automatically inserting the subject aircraft’s callsign.   |   .MA {==D1E==}  <ins>Published</ins>   |      |
|   .DT <br> ``(space)`` <br> ({== POS ID ==})   |   With the subject aircraft selected, sends a Down-Time Notification private message to the given ATC while automatically inserting the subject aircraft’s callsign and current time.   |   .DT {== D1F ==}   |      |
|   .RR <br> ``(space)`` <br> ({== ATPOS ID ==}) <br> ``(space)`` <br> (<ins>FREE TEXT up to 8 elements</ins>)  |   With the subject aircraft selected, sends a Release Request private message to the given ATC while automatically inserting the subject aircraft’s callsign, Departure and Arrival airports, and route of flight.   |   .RR {==D1E==} <ins>H120 8K S280</ins>   |      |
|   .RA <br> ``(space)`` <br> ({== POS ID ==}) <br> ``(space)`` <br> (<ins># of min from now</ins>)  |   With the subject aircraft selected, sends a Release Approved private message to the given ATC while automatically inserting the subject aircraft’s callsign and the number of minuets from now that the aircraft is approved for release.   |   .RA {== D2P ==}  <ins>3</ins>   |   If the ACFT is released at this current time, do not specify a number of min from now.   |
|   .PO <br> ``(space)`` <br> ({== POS ID ==}) <br> ``(space)`` <br> ({== POINT ==}) <br> ``(space)`` <br> (<ins>FREE TEXT</ins>)  |   With the subject aircraft selected, sends a Point-Out request private message to the given ATC while automatically inserting the subject aircraft’s position relative to the given point, callsign and assigned altitude.   |   .PO {== D1F ==} {== WNGNT ==} <ins>to the boundary and then turning northeast bound</ins>    |      |
|   .HO <br> ``(space)`` <br> ({== POS ID ==}) <br> ``(space)`` <br> ({== POINT ==}) <br> ``(space)`` <br> (<ins>FREE TEXT</ins>)  |   With the subject aircraft selected, sends a Handoff Notification private message to the given ATC while automatically inserting the subject aircraft’s position relative to the given point, assigned beacon code, callsign and assigned altitude.   |   .HO {== D1F ==} {== WNGNT ==} <ins>Requesting FL230</ins>   |      |
|   .APREQ <br> ``(space)`` <br> ({== POS ID ==}) <br> ``(space)`` <br> (<ins>FREE TEXT</ins>)  |   With the subject aircraft selected, sends a Approval Request (APREQ) private message to the given ATC while automatically inserting the subject aircraft’s callsign.   |   .M {== 77 ==} <ins>Direct STENT</ins>   |      |

## AUTO-TRACK CONFIGURATIONS
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .AT <br> ({==FAC ID ==}) <br> <ins>OFF</ins> |   Turns on/off auto-track for all underlying towered fields for the given facility.   |   .AT{==D21==} <br> .AT{==D21==}<ins>OFF</ins>   |      |
|   .AT <br> ZOB <br> <ins>OFF</ins>  |   Turns on/off auto-track at all towered fields under ZOB which are open during the day/mid.   |   .ATZOB <br> .ATZOB<ins>OFF</ins>   |      |

## OTHER TOOLS

|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .RLS <br> FP   |   With the subject aircraft selected, sends a message to the VATSIM FSD releasing control of the flight plan, allowing the pilot to edit elements in it and resend it.   |   .RLSFP   |   This is not a ZOB specific command but is not a well-documented command in external reference materials.   |

## TEXT TO PILOTS (TTP)
### General
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .T <br> CME   |   Sends a contact-me message to the selected aircraft.   |   .TCME   |      |
|   .T <br> SQ   |   Squawk the assigned squawk code.   |   .TSQ   |      |
|   .T <br> CON <br> ({==POS ID ==})      |   Contact the given ATC position.   |   .TCON{==D1F==}   |      |
|   .T <br> MON <br> ({==POS ID ==})   |   Monitor the given ATC position.   |   .TMON{==D1F==}   |      |
|   .T <br> CLOSING <br> ``(space)`` <br> ({==# of min ==})   |   Announces that you will be closing in the give number of min.   |   .TCLOSING  {==10==}   |   Ensure you do not have an aircraft selected prior to sending this command.   |
|   .T <br> CLOSED   |   Announces that you are now closed.   |   .TCLOSED   |      |
|   .T <br> SWITCH <br> TO <br> TWR   |   Private messages the selected aircraft information concerning how they are expected to switch to TWR on their own holding short of the assigned RWY.   |   .TSWITCHTOTWR   |      |
|   .T <br> EQUIP   |   Private messages the selected aircraft asking for their FAA equipment suffix code and provides a link to a tutorial showing them how to determine their code.   |   .TEQUIP   |      |
|   .T <br> N# <br> FORMAT   |   Private messages the selected aircraft advising them that their N-number format seems to be incorrect and links them to the FAA site to help them figure out how to reconnect with a correctly formatted callsign.   |   .TN#FORMAT   |      |
|   .T <br> ID <br> FORMAT   |   Private messages the selected aircraft advising them that their air-carrier callsign format seems to be incorrect and links them to the FAA site to help them figure out how to reconnect with a correctly formatted callsign.   |   .TIDFORMAT   |      |

### Clearance Delivery
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .T <br> RBC   |   Readback Correct   |   .TRBC   |      |
|   .T <br> CRAFT<br> AF <br> <ins>U</ins> <br> ``(space)`` <br> ({==INITIAL ALTITUDE ==}) <br> ``(space)`` <br> ({==DEP POS ID ==})   |   Issues a CRAFT clearance “as filed ".   |   .TCRAFTAF {== 17K D1E ==} <br> .TCRAFTAF<ins>U</ins> {== 17K D1E ==}   |   U = Departure offline/unicom   |
|   .T <br> CRAFT <br> FR <br> <ins>U</ins> <br> ``(space)`` <br> ({==INITIAL ALTITUDE ==}) <br> ``(space)`` <br> ({==DEP POS ID ==})   |   Issues a CRAFT clearance with a full route.   |   .TCRAFTFR {== 17K D1E ==} <br> .TCRAFTFR <ins>U</ins> {== 17K D1E ==}   |   U = Departure offline/unicom   |
|   .T <br> CRAFT <br> CVS <br><ins>U</ins> <br> ``(space)`` <br> ({==DP with ver # ==}) <br> ``(space)`` <br>   ({==DP END POINT ==}) <br> ``(space)`` <br> ({==DEP POS ID ==})   |   Issues a CRAFT clearance with a DP, DP endpoint, and issues Climb Via SID.   Reference note[^4]   |   .TCRAFTCVS {== HHOWE4 ==} {== LNCON ==} {== D1E ==} <br> .TCRAFTCVS<ins>U</ins> {== HHOWE4 ==} {== LNCON ==} {== D1E ==}   |   U = Departure offline/unicom.   |
|   .T <br> CRAFT <br> CVS <br> EM <br> <ins>U</ins> <br>``(space)`` <br> ({==DP with ver # ==}) <br>  ``(space)`` <br> ({==DP END POINT ==}) <br> ``(space)`` <br> ({==INITIAL ALTITUDE ==}) <br> ``(space)`` <br> ({==DEP POS ID ==})   |   Issues a CRAFT clearance with a DP, DP endpoint, and issues Climb Via SID, except  maintain .   Reference note[^4]   |   .TCRAFTCVSEM {==HHOWE4 ==} ({==LNCON ==} {==17K ==} {== D1E ==} <br> .TCRAFTCVSEM<ins>U</ins> {== HHOWE4 ==} {== LNCON ==} {== 17K ==} {== D1E ==}   |   U = Departure offline/unicom.   |

### Ground Control
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .T <br> RTV <br> ``(space)`` <br> ({==RWY ID ==}) <br> ``(space)`` <br> ({==TAXI INSTRUCTIONS ==})   |   Runway __, taxi via __   |   .TRTV {== 22L ==} {== V M, HOLD SHORT TAXIWAY M ==}   |      |
|   .T <br> TPV <br> ``(space)`` <br> ({==TAXI INSTRUCTIONS ==})   |   Taxi to parking via __   |   .TTPV {== M V ==}   |      |

### Local Control
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .T <br> CT <br> ``(space)`` <br> ({==RWY ID ==})   |   Instructs the selected aircraft to takeoff on the given RWY and inserts the departure field wind information.   |   .TCT {== 22L ==}   |      |
|   .T <br> CL <br> ``(space)`` <br> ({==RWY ID ==})   |   Instructs the selected aircraft to land on the given RWY and inserts the arrival field wind information.   |   .TCL {== 22L ==}   |      |

### RADAR - General
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .T <br> SQ <br> I   |   Squawk assigned code and ident.   |   .TSQI   |      |
|   .T <br> RC   |   RADAR Contact   |   .TRC   |      |
|   .T <br> RC <br> DB <br> ``(space)`` <br> ({== POINT ==})   |   RADAR Contact with their position (distance &bearing) relative to the given point   |   .TRCDB {== DJB ==}   |      |
|   .T <br> FH <br> ``(space)`` <br> ({==HEADINGD ==})   |   Fly the given heading.   |   .TFH {== 220 ==}   |      |
|   .T <br> T <br> ({==L/RD ==})   |   Turn left/right, fly the given heading.   |   .TT{==L 220 ==} <br> .TT{==R 220 ==}   |      |
|   .T <br> RST   |   RADAR Services Terminated   |   .TRST   |      |
|   .T <br> LMA   |   Leaving my airspace, radar services terminated.   |   .TLMA   |      |
|   .T <br> ({==D/C ==}) <br> M <br> ``(space)`` <br> ({==ALTITUDED ==})   |   Climb/Descend and maintain the given altitude.   |   .T{==D==}M {==8K==} <br> .T{==C==}M {==FL230==}   |      |

### Departure
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .T <br> HFR   |   Hold for release.   |   .THFR   |      |
|   .T <br> RFD   |   Issues a Release-For-Departure clearance that includes a 10min void time from the current time and an advisory to contact the issuing controller no later than 15min of intentions if not off in time.   |   .TRFD   |      |

### Approach
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .T <br> PTAC <br> ``(space)`` <br> ({==POINT ==}) <br> ``(space)`` <br> ({==HEADING ==}) <br> ``(space)`` <br> ({==ALTITUDE ==}) <br> ``(space)``<br> ({==IAP TYPE ==}) <br> ``(space)`` <br> ({==RUNWAY ==})      |   Issues standard PTAC given the relative position to the given point, including heading and altitude to fly until established and then the clearance to fly the given instrument approach type and the given runway.   |   .TPTAC {== DOTTI ==} {== 250 ==} {== 3K ==} {== ILS ==} {== 27R ==}   |      |
|   .T <br> PTAC <br> ILS <br>  ``(space)`` <br> ({==POINT ==}) <br> ``(space)`` <br> ({==HEADING ==}) <br> ``(space)`` <br> ({==ALTITUDE ==}) <br> ``(space)`` <br> ({==RUNWAY ==})   |   Completes the same thing as the .TPTAC command except the user does not have to indicate that ILS is the type of approach.   |   .TPTAC {== DOTTI ==} {== 250 ==} {== 3K ==} {== 27R ==}  |      |
|   .T <br>  RFIS   |   Advises the selected aircraft of their position relative to their destination and then asks them to report the field in sight.   |   .TRFIS   |      |
|   .T <br> CVA <br> ``(space)`` <br> ({==RWY ID ==})   |   Clears the pilot for a visual approach to the given runway.   |   .TCVA {== 22L ==}   |      |

### Enroute
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .T <br>  ({==SUBJECT POINT ==}) <br> ({==E/W/N/S for PIT restrictions ==})   |   Issues a crossing restriction to the pilot for the given subject point.   |   .{==EMMMA==} <br> .{==SLT==} <br> .{==PSB==} <br> .{==PSB==}<ins>LGA</ins> <br> .{==CUTTA==}{==E==}   |   The .PSBLGA command is the one command that is different than the rest to set it apart from the base .PSB command.   |

## FE-Buddy Commands
The following aliases are generated every AIRAC cycle by FE-Buddy and merged into the ZOB alias file.

### In-Scope Reference
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   .APT <br> ({==FAA or ICAO APT ID ==})   |   Returns the following for the given airport:   FAA &ICAO code   Name   Elevation   Towered status   Responsible ARTCC   ASOS frequency   |   .APT{==PTK==}   |      |
|   .NAV <br> ({==NAVAID ID or Name ==})   |   Returns the following for the given NAVAID:   ID   Frequency   Name   Type   |   .NAV{==CGT==} <br> .NAV{==CHICAGOHEIGHTS==}   |   When entering the name, do not include special characters or spaces.   |
|   .ID <br> ({==AIR-CARRIER 3 LETTER ID or TELEPHONY ==})   |   Returns the 3LID and Telephony of the given air-carrier.   |   .ID{==DAL==} <br> .ID{==NKP==} <br> .ID{==ABAKANAIR==}   |   When entering the telephony, do not include special characters or spaces.   |

### Data Display
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   . ({==AWY ID ==}) <br> F   |   Displays all the fixes, including NAVAIDs and airports, for the given airway.   |   .{==J15==}F   |   ERAM-Only   |
|   . ({==APT ID ==}) <br> ({==DP/STAR ID ==}) <br> F   |   Displays all the fixes, including NAVAIDs, for the given DP/STAR.   Reference note [^2].   |   .{==DTW==}{==PAVYL==}F   |   ERAM-Only   |

### FE-Buddy Chart Recall
|   SYNTAX   |   DESCRIPTION   |   EXAMPLE   |   NOTES   |
| --- | --- | --- | --- |
|   . ({==APT ID ==}) <br> TM <br>  C   |   Launches users browser to the given airports Takeoff Minimums, ODP, and DVA (TM) page.   |   .{==D98==}TMC   |      |
|   . ({==APT ID ==}) <br> DVA <br> C   |   Launches users browser to the given airports Diverse Vector Area page.   |   .{==SDL==}DVAC   |      |
|   . ({==APT ID ==}) <br> HS <br> C   |   Launches users browser to the given airports Hot Spots (HS) page.   |   .{==EDF==}HSC   |      |
|   . ({==APT ID ==}) <br> LAHSO <br> C   |   Launches users browser to the given airports Land and Hold Short (LAHSO) page.   |   .{==BZN==}LAHSOC   |      |
|   . ({==APT ID ==}) <br> APD <br>  C   |   Launches users browser to the given airports Airport Diagram (APD) page.   |   .{==DTW==}APDC   |      |
|   . ({==APT ID ==}) <br> ({==DP/STAR ID ==}) <br> (<ins>Page # if not 1</ins>) <br> C   |   Launches users browser to the given DP/STAR page.   Reference note #2.   |   .{==CLE==}{==BRWNZ==}C <br> .{==CLE ==}{==BRWNZ==}<ins>2</ins>C <br> .{==CLE==}{==BRWNZ==}<ins>3</ins>C   |      |
|   . ({==APT ID ==}) <br> ({==1st 5 CHAR OF DEP/STAR CHART NAME ==}) <br> (<ins>Page # if not 1</ins>) <br> C   |   Launches users browser to the given DP/STAR page.   |   .{==TNX==}{==TUMBE==}C <br> .{==GEG ==}{==SPOKA==}C <br> .{==GEG==}{==SPOKA==}<ins>2</ins>C   |   These commands are reserved for procedures that do not have a computer code assigned to them.   |
|   . ({==APT ID==}) <br> ({==IAP SPad Code==}) <br> (<ins>Page # if not 1</ins>) <br> C   |   Launches users browser to the given IAP page.   Reference note [^3].   |   .{==DTW==}{==I3R==}C <br> .{==CLE==}{==IY4L==}C <br> .{==CLE==}{==RU4L==}C   |      |
|   . ({==APT ID ==}) <br> V <br> ({==1st CHAR of EACH WORD IN THE VIS APP NAME ==}) <br> (<ins>Page # if not 1</ins>) <br> C   |   Launches users browser to the given Charted Visual Approach page.   |   .{==SFO==}V{==QBC==}C <br> .{==ASE==}V{==RF==}C   |      |

## Notes

[^1]: Prior to completing this command, it is suggested that you copy the route to the clipboard (CTRL+C). Complete the command and then paste (CTRL+P) into the Skyvector route field.
[^2]: 
    Commands like these are useful because they have another command that is similar. For example if you wanted to draw all the fixes for the CLE BRWNZ arrival on your scope and you wanted the chart to be recalled, simply complete one of the commands, then use your keyboards UP arrow to have it display again, use your backspace button to remove the last character and replace it with the appropriate letter for the other command. <br>
      **Example**:
      - .CLEBRWNZC
      - *Up arrow to display .CLEBRWNZC again, Then I just backspace to remove the C*
      - *Then type F resulting in:*
      - .CLEBRWNZF
[^3]: Reference the [FE-Buddy manual](https://docs.google.com/presentation/d/e/2PACX-1vRMd6PIRrj0lPb4sAi9KB7iM3u5zn0dyUVLqEcD9m2e71nf0UPyEmkOs4ZwYsQdl7smopjdvw_iWEyP/embed?slide=id.p) for SPad Code concept and syntax explanations. 
[^4]:
    Given this alias is meant to be sent to a text-only pilot, and these situations are dying out, so not every variable will be accounted for with these commands as it would take too long to develop those resources, let alone expect ATC to become moderately familiar with all of the syntaxes that are available
