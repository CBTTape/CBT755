# CBT755
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 755 is JRP from Scott Vetter and is a version which runs  *   FILE 755
//*           on MVS 3.8 under Hercules.                            *   FILE 755
//*                                                                 *   FILE 755
//*           email:  svetter@ameritech.net                         *   FILE 755
//*                                                                 *   FILE 755
//*           JRP IS A DSPRINT REPLACEMENT                          *   FILE 755
//*                                                                 *   FILE 755
//*                J R P         (JES2 REMOTE PRINTERS)             *   FILE 755
//*                                                                 *   FILE 755
//*           THIS PRODUCT WAS DESIGNED AND WRITTEN WITH THE        *   FILE 755
//*           INTENT OF INCREASING USER AS WELL AS PROGRAMMER       *   FILE 755
//*           PRODUCTIVITY.  IT("JRP") MAKES USE OF 3270 PRINTER    *   FILE 755
//*           DEVICES TO PRINT SPOOLED JES2 OUTPUT.  OUTPUT         *   FILE 755
//*           DEVICES ARE DEFINED TO "JRP" VIA A SEQUENTIAL DATA    *   FILE 755
//*           SET.  EACH CONTROL CARD IN THIS DATA SET DESCRIBES    *   FILE 755
//*           THE ATTRIBUTES OF ONE PRINTER.                        *   FILE 755
//*                                                                 *   FILE 755
//*               AFTER "JRP" INITIALIZATION,A SUBSYSTEM REQUEST    *   FILE 755
//*           IS ISSUED TO JES2 BASED ON EACH PRINTER'S             *   FILE 755
//*           DESCRIPTION.  IF JES2 CONFIRMS THAT OUTPUT IS         *   FILE 755
//*           AVAILABLE FOR THE PRINTER DESCRIBED, A SUBTASK IS     *   FILE 755
//*           CREATED, USING THE ATTRIBUTES DEFINED FOR THAT        *   FILE 755
//*           PARTICULAR DEVICE.  THE SPOOL DATASET IS READ,        *   FILE 755
//*           BUFFERED, THEN WRITTEN TO THE PRINTER VIA "VTAM".     *   FILE 755
//*                                                                 *   FILE 755
//*               "JRP" SUPPORTS VTAM SNA AND NONSNA TERMINALS AS   *   FILE 755
//*           "JRP" CONTROL TERMINALS.  A MAXIMUM OF 25(TWENTY      *   FILE 755
//*           FIVE) TERMINALS ARE SUPPORT SIMULTANEOUSLY.  ALL      *   FILE 755
//*           FUNCTIONS REQUIRED TO SUPPORT "JRPS" PRINTER          *   FILE 755
//*           DEVICES ARE AVAILIBLE FROM A "JRP" CONTROL            *   FILE 755
//*           TERMINAL.                                             *   FILE 755
//*                                                                 *   FILE 755
//*    ---------------------------------------------------------    *   FILE 755
//*                                                                 *   FILE 755
//*    Enhancements by Scott Vetter:                                *   FILE 755
//*                                                                 *   FILE 755
//*      ADD HELP DISPLAY FOR JRP CONSOLE USERS                     *   FILE 755
//*                                                                 *   FILE 755
//*      ALLOW A "P JRP" TO BE ENTERED FROM SYSTEM CONSOLE AS       *   FILE 755
//*      OPPOSED TO HAVING A WTOR.  PLUS, ADD WTOR/NOWTOR OPTION    *   FILE 755
//*      IN CONTROL CARD STREAM                                     *   FILE 755
//*                                                                 *   FILE 755
//*      CREATE A LOGGING FACILITY - ALLOW EITHER TO CONSOLE,       *   FILE 755
//*      SYSLOG, OR TO "JRPLOG DD  SYSOUT=*".                       *   FILE 755
//*                                                                 *   FILE 755
//*      ENHANCE SECURITY EXIT ROUTINE.                             *   FILE 755
//*                                                                 *   FILE 755
//*      CREATE A COMMAND FOR PRINTER(S) WHICH WILL SEND A          *   FILE 755
//*      COMMAND STREAM TO A PRINTER TO FLUSH THE OUTPUT.  THIS     *   FILE 755
//*      APPEARS TO BE NEEDED FOR SOFTWARE PRINTER EMULATORS.       *   FILE 755
//*                                                                 *   FILE 755
```
