# CBT352
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 352 has been moved to the CBT Overflow Tape, File 301.    *   FILE 352
//*                                                                 *   FILE 352
//*           Below is a listing of what this file used to          *   FILE 352
//*           contain, so you can know whether to look at the       *   FILE 352
//*           CBT Overflow Tape, File 301, for this material, or    *   FILE 352
//*           not.                                                  *   FILE 352
//*                                                                 *   FILE 352
//*   CBT Overflow Tape, File 301:                                  *   FILE 352
//*                                                                 *   FILE 352
//*           CONTAINS THE INTEL MODS TAPE FROM INTEL SEE THE       *   FILE 352
//*           MEMBER CALLED $$DOC FOR ADDITIONAL INFORMATION THAT   *   FILE 352
//*           IS NOT DOCUMENTED BELOW.                              *   FILE 352
//*                                                                 *   FILE 352
//*     MEMBER   SV LANG  DESCRIPTION                               *   FILE 352
//*     ________ __ ____  _______________________                   *   FILE 352
//*     $$DOC       N/A   THIS FILE                                 *   FILE 352
//*     $$GENTAP    N/A   JCL USED TO GENERATE THIS TAPE.           *   FILE 352
//*     $$INDEX     N/A   THIS MEMBER - TABLE OF CONTENTS           *   FILE 352
//*     $$RELOAD    N/A   JCL TO LOAD DOWN TAPE TO DISK --          *   FILE 352
//*                       ALSO APPEARS AS FILE 1 ON THE             *   FILE 352
//*                       TAPE.                                     *   FILE 352
//*     ABEND       BAL   SUBROUTINE-ISSUE USER ABEND WITH          *   FILE 352
//*                       CODE OF YOUR CHOICE                       *   FILE 352
//*     ABENDPGM    BAL   PGM TO WTOR FAILURE MESSAGE (VIA          *   FILE 352
//*                       PARM FIELD) WHEN YOUR FAVORITE JOB        *   FILE 352
//*                       FAILS..REQUIRES OPERS TO ACK-             *   FILE 352
//*                       NOWLEDGE MESSAGE WITH JOBNAME.            *   FILE 352
//*     ACFEXITS    BAL   THIS IS 2 SMP JOBS TO INSTALL OUR         *   FILE 352
//*                       EXITS FOR ACF2.  ACFVAL AND ACFDSTBL      *   FILE 352
//*                       CONSTITUTE OUR NAMING CONVENTIONS         *   FILE 352
//*                       SUPPORT AT INTEL.  ACFVIOX IS OUR         *   FILE 352
//*                       VIOLATION EXIT TO SUPPORT PHASED          *   FILE 352
//*                       IMPLEMENTATION OF RULES.                  *   FILE 352
//*     ACF2MON     SAS   THIS SAS 79.3 PROGRAM READS SMF           *   FILE 352
//*                       RECORDS FOR ACF2 EVENTS- MATCH            *   FILE 352
//*                       MERGES SEVERAL 'WHODAT' FILES AND         *   FILE 352
//*                       PRODUCES A COMPOSITE REPORT ON ALL        *   FILE 352
//*                       ACF2 ACTIVITY FOR EACH GROUP              *   FILE 352
//*                       SECURITY ADMINISTRATOR..(BY HENRY         *   FILE 352
//*                       WACKER)                                   *   FILE 352
//*     ANLZUCB     PL/I  GEN REPORT ON WORK PACK USAGE/MSS         *   FILE 352
//*                       UCB USAGE REQUIRES P051B12L               *   FILE 352
//*                       (UCBLOGER) TO GATHER INFO.                *   FILE 352
//*     BKUPUTIL    BAL   PGM FROM SHARE MODS TAPE (FILE18) TO      *   FILE 352
//*                       INVOKE UTILITY TO CREATE STACKED          *   FILE 352
//*                       SL TAPE.  OUR MODS INCLUDE AUTO           *   FILE 352
//*                       SELECT FOR IEBISAM AND PANVALET           *   FILE 352
//*                       SUPPORT VIA PAN#2.  DYNAMIC ALLOC         *   FILE 352
//*                       OF VOLUMES, AND DATASET/TAPE DS           *   FILE 352
//*                       STATS ARE ALSO PRINTED.  MUST BE          *   FILE 352
//*                       LINKED WITH AC=1 TO ALLOW IEBCOPY         *   FILE 352
//*                       TO FUNCTION. (SUPPORTS                    *   FILE 352
//*                       PS/PO/IS/DA/PV                            *   FILE 352
//*     COMPMEMB    PL/I  COMPARE MEMBERS IN PDS OR PANVALET        *   FILE 352
//*                       LIBRARIES BY MEMBER NAME AND              *   FILE 352
//*                       PRODUCE CNTL CARDS BASED ON               *   FILE 352
//*                       EXISTENCE OF MEMBER IN EITHER OR          *   FILE 352
//*                       BOTH LIBRARIES.                           *   FILE 352
//*     DATTIM      BAL   SUBROUTINE- RETURNS 'HH:MM:SS' AND        *   FILE 352
//*                       'MM/DD/YY'                                *   FILE 352
//*     DELETDS     BAL   UTILITY- UNCATLG TAPES AND                *   FILE 352
//*                       UNCATLG/SCRATCH DATASETS SUPPORTS         *   FILE 352
//*                       MSS VIA DYNAMIC ALLOC OF MSS              *   FILE 352
//*                       VOLUMES.                                  *   FILE 352
//*     DIDOCS   ** BAL   TSO COMMAND TO ALLOW TSO 3270 TO          *   FILE 352
//*                       BECOME A OS OPER CONSOLE.  FINDS          *   FILE 352
//*                       MCS BUFFERS IN CSA AND REDISPLAYS         *   FILE 352
//*                       THEM TO TSO TUBE.  ACCEPTS                *   FILE 352
//*                       COMMANDS AND USES SVC 34 TO ISSUE         *   FILE 352
//*                       THEM. FROM SHARE DCMS SYSTEM              *   FILE 352
//*                       (CBT).                                    *   FILE 352
//*     DSINFO      BAL   PL/I SUBROUTINE- GET DSN INFORMATION      *   FILE 352
//*                       VIA RDJFCB (FROM IIH, ISRAEL)             *   FILE 352
//*     ERAS3270    BAL   TSO COMMAND- ERASE A 3270 SCREEN          *   FILE 352
//*                       (WITH SPF TRIGGERS).                      *   FILE 352
//*     FCIMOD07    BAL   FROM FLORIDA POWER AND LIGHT- THEIR       *   FILE 352
//*                       FULL SCREEN FAC.  WITH FCI ADDED          *   FILE 352
//*                       SPF FULLSCRN TRIGGERS.                    *   FILE 352
//*     FSF         BAL   FROM FLORIDA POWER AND LIGHT- THE         *   FILE 352
//*                       LINKABLE PORTION OF THEIR FULL            *   FILE 352
//*                       SCREEN FACILITY-INVOKES FCIMOD07          *   FILE 352
//*     HEXCONV     BAL   PL/I SUBROUTINE- CONVERT                  *   FILE 352
//*                       CHAR/BIT/ETC TO HEX CHAR (FROM            *   FILE 352
//*                       IIH, ISRAEL)                              *   FILE 352
//*     IEECVXIT    BAL   OUR MODS TO MSSCVXIT IN                   *   FILE 352
//*                       SYS1.SAMPLIB.. CAUSE OTHER                *   FILE 352
//*                       MESSAGES (IFG...) TO 'HANG' ON            *   FILE 352
//*                       SCREENS, SUBMIT JOB TO DUMP TRACE         *   FILE 352
//*                       WHEN TRACE SWITCH OCCURS.  (ONLY          *   FILE 352
//*                       SOURCE SUPPLIED...NO JCL TO               *   FILE 352
//*                       INSTALL)                                  *   FILE 352
//*     IPOUPDTE    SZAP  SIMPLE ZAP TO LET IPO AID (IPOUPDTE)      *   FILE 352
//*                       WORK ON ANY JCL OR SOURCE PDS.            *   FILE 352
//*     CPPUPDTE    SZAP  SIMPLE ZAP TO LET IPO AID (CPPUPDTE)      *   FILE 352
//*                       WORK ON ANY JCL OR SOURCE PDS.            *   FILE 352
//*     JCLFORMT    BAL   UTILITY TO REFORMAT A JOB OR A PROC       *   FILE 352
//*                       INTO SOME KIND OF ORDER.  INVOKED         *   FILE 352
//*                       BY 'CLEANJCL' CLIST IN JOBS.CNTL          *   FILE 352
//*     MAPDISK     BAL   GOOD OLD MAPDISK WITH ENHANCEMENTS:       *   FILE 352
//*                       1) DYNAMIC ALLOC FOR MSS VOLUMES          *   FILE 352
//*                       (SEE P963P30) 2) CAPABILITY TO LOG        *   FILE 352
//*                       VTOC INFO TO DATASET 3) ASM2 OPEN         *   FILE 352
//*                       MOD AND RACF SUPPORT                      *   FILE 352
//*     MOP         BAL   ALLOW OPER PRIV TSO USER TO DO            *   FILE 352
//*                       MVS/JES2 COMMANDS.  THE COMMAND IS        *   FILE 352
//*                       LOGGED, ALONG WITH THE ISSUING TSO        *   FILE 352
//*                       UID.                                      *   FILE 352
//*     MSSAMS      BAL   THE IPO MSSAMS AID, WITH A NOTIFY=        *   FILE 352
//*                       AND COND CODE CHK                         *   FILE 352
//*     MSSDUMP     PL/I  PGM TO DUMP MSS TABLES IN A NEAT          *   FILE 352
//*                       FORMAT (FROM FVT)                         *   FILE 352
//*     MSSPDATE    BAL   PGM TO WRITE A NICE DATE TO THE MSS       *   FILE 352
//*                       LOG CONSOLE INVOKE VIA A JES2             *   FILE 352
//*                       $TA,I=1800,'$VS,''S MSSPDATE'''           *   FILE 352
//*     MSSTSO      BAL   IPO MSSTSO WITH A FEW CHANGES FOR         *   FILE 352
//*                       3330-1 SUPPORT                            *   FILE 352
//*     MSSVOL      PL/I  INVOKED BY MSVGP CLIST IN JOBS.CNTL-      *   FILE 352
//*                       LIST VOLUMES IN MSVI FOR MSVGPS OF        *   FILE 352
//*                       YOUR CHOICE.                              *   FILE 352
//*     MVSMON      BAL   FROM FLORIDA POWER AND LIGHT- MVS         *   FILE 352
//*                       MONITOR USES TSO FULL SCREEN.  WE         *   FILE 352
//*                       ADDED DIDOCS INVOKE VIA THE               *   FILE 352
//*      (NOT FOR SE2/SP1)  'CO' COMMAND, DOMAIN NAME DISPLAY,      *   FILE 352
//*                       DISP DISK FORMAT IMPROVEMENTS AND         *   FILE 352
//*                       ELIM DUP VOLUME REPORTING VIA UCB         *   FILE 352
//*                       ALT PATH PLUS OTHER THINGS.....           *   FILE 352
//*     NETINFO     JCL/SAS   THE JOB IS PART OF THE                *   FILE 352
//*                        'VTAMDOC', 'CICSDOC', 'NETINFO'          *   FILE 352
//*                        JOBS WHICH WILL ASSEMBLE THE VTAM        *   FILE 352
//*                        NCP AND CICS TCT USING MACROS IN         *   FILE 352
//*                        MODS.NETINFO.  THE NETINFO JOB           *   FILE 352
//*                        USES A SAS PROGRAM (IN MODS.SASLIB)      *   FILE 352
//*                        TO READ THE ASSEMBLED VTAM, CICS,        *   FILE 352
//*                        ADMPRINT, DSPRINT, AND WHATNOT           *   FILE 352
//*                        TABLES TO PRODUCE A DOCUMENT OF THE      *   FILE 352
//*                        NETWORK IN INFO/SYSTEM FORMAT.           *   FILE 352
//*     NTLM801     BAL    PDS MEMBER LOGICAL READ SUBROUTINE.      *   FILE 352
//*                        USED BY PROCXREF PROGRAM.                *   FILE 352
//*     NTLM802     BAL    PDS DIRECTORY READ SUBROUTINE.  USED     *   FILE 352
//*                        BY PROCXREF.                             *   FILE 352
//*     OSDEBE   ** BAL   THE INFAMOUS 'DOES EVERYTHING BUT         *   FILE 352
//*                       EAT' UTILITY FOR FIDDLING WITH            *   FILE 352
//*                       TAPES AND CARDS.  OPERS L O V E           *   FILE 352
//*                       IT.  WORKS ONLY WITH OFFLINE              *   FILE 352
//*                       TAPES...................  INVOKE          *   FILE 352
//*                       VIA 'DEBE' IN JOBS.CNTL.                  *   FILE 352
//*     OZPDSUNL    BAL   THIS PROGRAM WILL UNLOAD A RECFM=VB       *   FILE 352
//*                       PDS AND CONSTRUCT A SEQUENTIAL            *   FILE 352
//*                       DATASET FOR USE BY THE BLGOZX             *   FILE 352
//*                       (INFO/SYSTEM) PROGRAMS.  USED AT          *   FILE 352
//*                       INTEL TO GENERATE A USER DATABASE         *   FILE 352
//*                       FOR TECHNICAL INFORMATION.  SEE           *   FILE 352
//*                       JOBS 'TEC.....' IN JOBS.CNTL FOR          *   FILE 352
//*                       MORE INFO.                                *   FILE 352
//*     PANFETCH    BAL   USES THE PANVALET ACCESS METHOD           *   FILE 352
//*                       (PAM) TO WRITE A MEMBER OF A              *   FILE 352
//*                       PANVALET LIBRARY TO A SEQUENTIAL          *   FILE 352
//*                       DSN EXPANDING ALL IMBEDDED                *   FILE 352
//*                       ++INCLUDE CARDS.  USED IN THE             *   FILE 352
//*                       'CICSDOC' JOB.                            *   FILE 352
//*     PANSCAN     PL/I   THIS IS A MORE USEFUL VERSION OF THE     *   FILE 352
//*                        'PAN#8' PROGRAM TO SCAN A PANVALET       *   FILE 352
//*                         LIBRARY FOR OCCURRENCES OF PARTICULAR   *   FILE 352
//*                         CHARACTER STRINGS.  THIS PL/I           *   FILE 352
//*                         VERSION IS A BIT SLOWER THAN PAN#8,     *   FILE 352
//*                         BUT OPENS THE LIBRARY FOR INPUT ONLY    *   FILE 352
//*                         (INSTEAD OF UPDATE), AND ALLOWS         *   FILE 352
//*                         MULTIPLE SCAN PASSES AND GENERIC        *   FILE 352
//*                         MEMBER SELECTION.                       *   FILE 352
//*     PROCXREF    BAL     READS A JCL PROCLIB AND PRODUCES 3      *   FILE 352
//*                         REPORTS:                                *   FILE 352
//*                           CROSS REF BY DATASET NAME             *   FILE 352
//*                           CROSS REF BY PROGRAM NAME             *   FILE 352
//*                           CROSS REF BY SYSOUT CLASS/FORMS       *   FILE 352
//*                         PROCXREF ALSO UNLOADS THE LIBRARY TO    *   FILE 352
//*                         A SEQUENTIAL FILE FOR FURTHER           *   FILE 352
//*                         PROCESSING VIA SAS PGM 'PROCANLZ'       *   FILE 352
//*                         (REQUIRES NTLM801,NTLM802 PDS READ      *   FILE 352
//*                         ROUTINES).                              *   FILE 352
//*     PSN         BAL   THIS IS OUR JCL STANDARDS CHECKER         *   FILE 352
//*                       AND JCL REFORMATTER PROGRAM.              *   FILE 352
//*                       OBVIOUSLY YOU WON'T WANT TO USE           *   FILE 352
//*                       OUR STDS FOR JCL, BUT THIS PGM IS         *   FILE 352
//*                       HIGHLY MODULAR AND INCLUDES A LOT         *   FILE 352
//*                       OF NEAT CODE BY MIKE FARMER.  IT          *   FILE 352
//*                       WILL BE EASY FOR YOU TO INSERT            *   FILE 352
//*                       YOUR OWN JCL FOIBLES IN THIS GEM..        *   FILE 352
//*     P051B10     BAL   THE TSO WHOGOT/DSN COMMAND - RUNS AS      *   FILE 352
//*                       STC ALSO FINDS USERS/JOBS ENQUEUED        *   FILE 352
//*                       ON A DATASET.                             *   FILE 352
//*     P051B12     BAL   THE TSO DSPACE COMMAND - RUNS AS STC      *   FILE 352
//*                       ALSO DOES LSPACE TO PACK(S) OF            *   FILE 352
//*                       CHOICE AND FORMATS RESULT.                *   FILE 352
//*                       DEFAULT PACKS ARE 'FCITS*'.               *   FILE 352
//*     P051B12L    BAL   THE UCBLOGER STC - FIRE OFF AT 10         *   FILE 352
//*                       MINUTE INTERVALS VIA JES2                 *   FILE 352
//*                       $TA,I=600,'$VS,''S UCBLOG''' AND          *   FILE 352
//*                       ONCE A WEEK RUN THE SAVELOG JOB TO        *   FILE 352
//*                       PRINT THE REPORT VIA ANLZUCB AND          *   FILE 352
//*                       REINITIALZE THE LOG DATASET.              *   FILE 352
//*     P051B15     BAL   THE TSO DDSTAR COMMAND- SPOOL LINES       *   FILE 352
//*                       FROM A CLIST INTO A DATASET FOR           *   FILE 352
//*                       READING BY PGMS/UTILITIES.                *   FILE 352
//*                       ARRIVED VIA MISHMODS TAPE FROM            *   FILE 352
//*                       UCLA-FCI INTERNALIZE MACROS FROM          *   FILE 352
//*                       URMACRO.                                  *   FILE 352
//*     P051B16     BAL   THE TSO LISTSPC COMMAND - REPLACES        *   FILE 352
//*                       LISTC USAGE FOR TSO USERS..SHOWS          *   FILE 352
//*                       ALLOCATIONS, AND DS ATTRIBS, AND          *   FILE 352
//*                       IF YOU HAVE ASM2, ALSO SHOWS WHO          *   FILE 352
//*                       LAST MODIFIED DS.                         *   FILE 352
//*     P051B19     BAL   THE TSO DTAPES COMMAND - RUNS AS STC      *   FILE 352
//*                       ALSO SHOWS TAPE DRIVES, VOLSER,           *   FILE 352
//*                       JOB USING AND DENSITY, MODEL              *   FILE 352
//*                       TYPES.                                    *   FILE 352
//*     P963P00     PL/I  DASD MANAGEMENT SYSTEM- MAINLINE          *   FILE 352
//*                       (COMPARE DSN FROM VTOC WITH GRANT         *   FILE 352
//*                       LIST) - GENERATE SCRATCH LIST AND         *   FILE 352
//*                       MERGED DSNLOG.                            *   FILE 352
//*     P963P02     PL/I  DASD MANAGEMENT SYSTEM- DATA SET          *   FILE 352
//*                       SCRATCH UTILITY                           *   FILE 352
//*     P963P10     PL/I  DASD MANAGEMENT SYSTEM- GENERATE          *   FILE 352
//*                       SCRATCH LOG FROM OUTLOG OF P963P00        *   FILE 352
//*                       (FOR RECOVERY ONLY).                      *   FILE 352
//*     P963P20     PL/I  DASD MANAGEMENT SYSTEM- PRINT SCRLOG      *   FILE 352
//*                       REPORT FOR TSO USERS - USED BY            *   FILE 352
//*                       CLIST SHOWSCR.                            *   FILE 352
//*     P963P27     PL/I  DASD MANAGEMENT SYSTEM- AUTOSCR           *   FILE 352
//*                       (EARLY SCR FOR ROLLED OFF GDG             *   FILE 352
//*                       DATASETS) + DATASET SIZE HISTORY          *   FILE 352
//*                       FILE                                      *   FILE 352
//*     P963P30     PL/I  PGM FROM OUR DASD MGMT                    *   FILE 352
//*                       SYSTEM..ACCEPTS CONTROL CARDS AND         *   FILE 352
//*                       LOOKS UP VOLUMES/MSVGPS FROM THE          *   FILE 352
//*                       MSVI DATASET.  USE PROC 'MAPMSVGP'        *   FILE 352
//*                       TO INVOKE THIS ONE, THEN MAPDISK          *   FILE 352
//*                       TO MAP ALL VOLUMES IN AN MSVGP.           *   FILE 352
//*     P963P35     PL/I  DASD MANAGEMENT SYSTEM- DUPLICATE         *   FILE 352
//*                       VOLUME ELIMINATOR TO ENSURE THAT          *   FILE 352
//*                       MAPDISK MAPS EACH VOLUME ONLY             *   FILE 352
//*                       ONCE.                                     *   FILE 352
//*     P963P70     PL/I  DASD MANAGEMENT SYSTEM- SUPERMATCH        *   FILE 352
//*                       PROGRAM-USED WITH P963P71/SUPERSCR        *   FILE 352
//*                       TO EXCLUDE DSNS FROM SUPERSCR             *   FILE 352
//*     P963P71     PL/I  DASD MANAGEMENT SYSTEM- GENERATE          *   FILE 352
//*                       SUPERSCR EXCLUDE CARDS TO EXEMPT          *   FILE 352
//*                       DATASETS FROM SUPERSCR AFTER              *   FILE 352
//*                       SYSTEM CRASH - INTERFACES WITH            *   FILE 352
//*                       OPERATOR VIA WTOR                         *   FILE 352
//*     P963P75     PL/I  DASD MANAGEMENT SYSTEM- DATASET SIZE      *   FILE 352
//*                       HISTORY FILE MAINT PROGRAM AND            *   FILE 352
//*                       AUTOSCR FOR MSVGP=XMIT                    *   FILE 352
//*     P963P75A    PL/I  DASD MANAGEMENT SYSTEM- MAINTAIN          *   FILE 352
//*                       MSVGP=XMIT                                *   FILE 352
//*     R062A10     BAL   DYNAMIC ALLOCATION INTERFACE              *   FILE 352
//*                       SUBROUTINE - ALLOWS MOST DA               *   FILE 352
//*                       SERVICES FROM A COBOL/PLI/FORT            *   FILE 352
//*                       PROGRAM.                                  *   FILE 352
//*     R941X11     BAL   UTILITY JULIAN<->GREGORIAN DATE           *   FILE 352
//*                       CONVERTOR-- USED BY SEVERAL PL/I          *   FILE 352
//*                       PROGRAMS ON THIS TAPE.                    *   FILE 352
//*     R963A30     BAL   HANDY SUBROUTINE TO                       *   FILE 352
//*                       SCRATCH/UNCATALOG DATASET..  DOES         *   FILE 352
//*                       DYNAMIC ALLOCATION OF VOLUME, AND         *   FILE 352
//*                       REPORTS WITH TEXT MESSAGES TO             *   FILE 352
//*                       CALLER                                    *   FILE 352
//*     SCOMPARE    BAL   PGM TO COMPARE 2 LRECL=80 DATASETS        *   FILE 352
//*                       AND SPOT DIFFERENCES.  BASED ON           *   FILE 352
//*                       CBT881 WITH MODS TO PRINT WHICH           *   FILE 352
//*                       DATASETS ARE BEING COMPARED, AND          *   FILE 352
//*                       PAGE CONTROL.                             *   FILE 352
//*     SHOWHIST    PL/I  DASD MANAGEMENT SYSTEM- SHOW TSO          *   FILE 352
//*                       USERS THE HISTORY (SIZE, ETC) ON          *   FILE 352
//*                       DATASETS OF THEIR CHOICE.. INVOKED        *   FILE 352
//*                       BY THE 'SHOWHIST' CLIST IN                *   FILE 352
//*                       JOBS.CNTL                                 *   FILE 352
//*     SHOWSMF     BAL   TSO CMD OR STC TO DISPLAY                 *   FILE 352
//*                       ''FULLNESS'' OF MANX/MANY FOR MVS         *   FILE 352
//*                       (NOT SE OR SP SYSTEMS)                    *   FILE 352
//*     SHOSMFSP    BAL   TSO CMD OR STD TO DISPLAY SYS1.MAN.       *   FILE 352
//*                       DATASETS FOR MVS SE2 OR SP1/SP3.          *   FILE 352
//*     SHOWRAW     PL/I  PGM TO DISPLAY START/END DATES OF         *   FILE 352
//*                        TRACE DUMP DATASETS (USED IN             *   FILE 352
//*                        MSSTRACE/TRACESAV JOBSTREAMS).           *   FILE 352
//*     SHOWTRC     PL/I  PGM TO DYNAM. ALLOC MSS TRACE             *   FILE 352
//*                       DATASETS AND READ HDR                     *   FILE 352
//*                       RECORD/FORMAT TRACE ON DATE/TIME.         *   FILE 352
//*                       THIS IS AN EXAMPLE OF USING               *   FILE 352
//*                       R062A10 DYNAM ALLOC AND S051B16B          *   FILE 352
//*                       (LOCINDEX) SUBROUTINE.  ONLY              *   FILE 352
//*                       SOURCE IS SUPPLIED- NO JCL TO             *   FILE 352
//*                       COMPILE AND LINK.                         *   FILE 352
//*     SMFACF2     PL/I  SMF PGM- DIGEST ACF2 RECORDS, PRINT       *   FILE 352
//*                       ACF2 INFORMATION                          *   FILE 352
//*     SMFACFM     PL/I  SMF PGM- MERGE DIGESTED ACF2 RECORDS      *   FILE 352
//*                       AND RESPONSIBILITY LIST.                  *   FILE 352
//*     SMFACFPR    PL/I  SMF PGM- PRINT NICELY FORMATTED ACF2      *   FILE 352
//*                       INFORMATION                               *   FILE 352
//*     SMFDSND     PL/I  SMF PGM- LOOK FOR TYPE 14/15/17           *   FILE 352
//*                       RECORDS FOR UP TO 20 GENERIC              *   FILE 352
//*                       DATASETS-SHOW RAW INFO                    *   FILE 352
//*     SMFDSNPR    PL/I  SMF PGM- PRINT SORTED SMFDSND OUTPUT      *   FILE 352
//*                       TO SHOW CHRONOLOGICAL HISTORY OF          *   FILE 352
//*                       DATASET ACCESS.                           *   FILE 352
//*     SMFRACF     PL/I  SMF PGM- PRINT RACF EVENTS FROM TYPE      *   FILE 352
//*                       0,80 AND 81 RECS PROVIDE LISTING          *   FILE 352
//*                       OF EVENTS AND BUILD CLIST TO ALLOW        *   FILE 352
//*                       RECONSTRUCTION OF RACF DATASET            *   FILE 352
//*                       AFTER CRASH.                              *   FILE 352
//*     SMFSEL      BAL   SMF PGM- RECORD SELECTION UTILITY         *   FILE 352
//*     SMFTERM     PL/I  SMF PGM- ANALYZE TYPE 34 RECORDS AND      *   FILE 352
//*                       PRODUCE TSO USAGE SUMMARY.                *   FILE 352
//*                       REQUIRES IEFUJI TO PUT TERMINAL           *   FILE 352
//*                       UCB ADDR IN LAST HALFWORD OF              *   FILE 352
//*                       SMFUSER FIELD IN ORDER TO PROVIDE         *   FILE 352
//*                       TERMINAL USAGE STATS BY TERMINAL          *   FILE 352
//*                       ADDRESS                                   *   FILE 352
//*     SPACEZAP    PL/I  PGM TO DYNAM. ALLOC MSS VOLUMES           *   FILE 352
//*                       WHICH ARE NOT MOUNTED BUT HAVE            *   FILE 352
//*                       DOWN LEVEL SPACE FLAG SET ON IN           *   FILE 352
//*                       MSVI.  MSVGPS SCANNED CONTROLLED          *   FILE 352
//*                       BY SYSIN PARM CARDS.  (STC JCL IN         *   FILE 352
//*                       MSSMODS.JOBS.CNTL + SAMPLE CNTL           *   FILE 352
//*                       DS)                                       *   FILE 352
//*     SUPERSCR ** BAL   SUPER SCRATCH FOR REAL/VIRTUAL            *   FILE 352
//*                       DISKS..                                   *   FILE 352
//*     SUPERSPY ** BAL   THE THING TO RUN TO HELP DIAGNOSE         *   FILE 352
//*                       PROBLEMS WITH MVS/ MSS..REQUIRES          *   FILE 352
//*                       MSC TABLES MAINT. IUP IN SECOND           *   FILE 352
//*                       STEP.                                     *   FILE 352
//*     S051B22     BAL   THE FIND SUBROUTINE..USED BY              *   FILE 352
//*                       TSO044(UCBUNLD) TO FIND 'VOL=(SL,'        *   FILE 352
//*                       ON PARM CARD.                             *   FILE 352
//*     TECHINFO    JCL   JOB TO UPDATE YOUR VERY OWN INFO/MVS      *   FILE 352
//*                       FORMATTED DATABASE.  USES UTILITY         *   FILE 352
//*                       'OZPDSUNL'.  SEE JOBS.CNTL FOR THE        *   FILE 352
//*                       FOLLOWING MEMBERS:                        *   FILE 352
//*          TECINFOC - CLIST TO RUN TECHINFO UNDER TSO             *   FILE 352
//*          TECHINFO - JOB TO RELOAD TECHINFO DATABASE             *   FILE 352
//*          TECINFO1 - USES IDCAMS TO DEFINE VSAM CLUSTER FOR DB   *   FILE 352
//*          TECINFO2 - USES BLG... UTILITIES TO CREATE UNLOADED    *   FILE 352
//*                     HELP, CICS, VTAM, VSAM FILES FROM THE       *   FILE 352
//*                     INFO/MVS MONTHLY UPDATE TAPE.               *   FILE 352
//*     TRAC3850    BAL   IPO TRAC3850 WITH MODS..ANLZ              *   FILE 352
//*                       IGCTRINT OUTPUT                           *   FILE 352
//*     TSO020SU    BAL   TSO DJOBS COMMAND - STC USAGE ALSO.       *   FILE 352
//*                       LIKE 'D J,L' WITH SWAP STATUS,CPU         *   FILE 352
//*                       TIME,XACT TIME                            *   FILE 352
//*     TSO025AS ** BAL   TSO DTSO COMMAND  - STC USAGE ALSO.       *   FILE 352
//*                       LIKE DJOBS ABOVE, BUT FOR TSO;            *   FILE 352
//*                       SHOWS LINE ADDR TOO.                      *   FILE 352
//*     TSO032      BAL   TSO DDMN COMMAND  - STC USAGE ALSO.       *   FILE 352
//*                       LIKE 'D DMN' BUT NEATER, SHOWS IPS        *   FILE 352
//*                       IN EFFECT TOO.                            *   FILE 352
//*     TSO033      BAL   TSO DUPTIME COMMAND - STC USAGE           *   FILE 352
//*                       ALSO.  SHOWS HOW LONG SYSTEM HAS          *   FILE 352
//*                       BEEN UP (FROM LAST IPL)                   *   FILE 352
//*     TSO034   ** BAL   TSO SYSMAINT COMMAND - STC USAGE          *   FILE 352
//*                       ALSO.  WRITTEN BEFORE THE DAYS OF         *   FILE 352
//*                       'FORCE', ALLOWS A CALLRTM MEMTERM         *   FILE 352
//*                       TO BE ISSUED TO AN ADDRESS SPACE          *   FILE 352
//*                       HANDLES 'STARTING' TSO USERS TOO.         *   FILE 352
//*     TSO036      BAL   TSO SHOWASM COMMAND  - STC USAGE          *   FILE 352
//*                       ALSO.  DISPLAYS AUXSTM STATS, RSM         *   FILE 352
//*                       PAGE USAGES, AND PAGE/SWAP DATASET        *   FILE 352
//*                       STATUS/STATS.                             *   FILE 352
//*     TSO041      BAL   TSO LPDS COMMAND.  THE EVER POPULAR       *   FILE 352
//*                       PDS MANIPUATOR COMMAND, DOES              *   FILE 352
//*                       EVERYTHING BUT DRY-CLEAN A PDS            *   FILE 352
//*                       OF YOUR CHOICE.  (SEE FILE 182 FOR NEW.)  *   FILE 352
//*     TSO042      BAL   TSO DUNITS COMMAND  - STC USAGE           *   FILE 352
//*                       ALSO.  LIKE 'D U,...' BUT MORE            *   FILE 352
//*                       INFORMATIVE WITH USE/OPEN COUNTS.         *   FILE 352
//*                       SELECTION IS BY GENERIC VOLSERS.          *   FILE 352
//*     TSO044   ** BAL   STARTED TASK..UNLOAD ALL MSS VOLUMES      *   FILE 352
//*                       NOT ON A LIST OF VOLSERS IN MEMBER        *   FILE 352
//*                       'MOUNTMSS'.  PARSES '$VS,'M               *   FILE 352
//*                       XXX,VOL=(SL,VOLSER)'' COMMANDS TO         *   FILE 352
//*                       FIND VOLUMES TO EXEMPT...                 *   FILE 352
//*     TSO045      BAL   THE CHIMP MVS SYSTEM DISPLAY COMMAND      *   FILE 352
//*                       FOR 3270 FULLSCR OPERATION.  SHOWS        *   FILE 352
//*                       JOBS/TSO USER STATS, AND WE ADDED         *   FILE 352
//*                       A DYNAMIC DOMAIN DISPLAY (OPTION          *   FILE 352
//*                       'D').  OPERS LOVE IT..SHOWS STEP          *   FILE 352
//*                       NAME AND CPU TIME...  (ORIG FROM          *   FILE 352
//*                       SHARE VIA THE CBT TAPE).                  *   FILE 352
//*     TSO048      BAL   THE TSO #PANVIEW COMMAND - ALLOW          *   FILE 352
//*                       LISTING OF PANVALET LIBRARY               *   FILE 352
//*                       MEMBERS AND LIBRARY DIRECTORY ON A        *   FILE 352
//*                       3270 TUBE IN FULL SCREEN MODE.            *   FILE 352
//*                       (ORIG FROM SHARE JES2 MODS TAPE           *   FILE 352
//*                       (MEMOREX) WITH                            *   FILE 352
//*                        DIRECTORY LIST MOD BY FAIRCHILD). USES   *   FILE 352
//*                        THE 'PANVIEW' CLIST IN MSSMODS.JOB.CNTL  *   FILE 352
//*                        TO RUN.                                  *   FILE 352
//*     TSO050      BAL   TSO '$' COMMAND- INVOKE PROGRAM FROM      *   FILE 352
//*                       LINKLIST.  THIS VERSION ARRIVED           *   FILE 352
//*                       FROM SOURCES UNKNOWN, BUT WE              *   FILE 352
//*                       INTERNALIZED THE MACROS-(LOOKS            *   FILE 352
//*                       LIKE UCLA MACROS...)                      *   FILE 352
//*     TSO051      BAL   TSO 'GETINFO' COMMAND - ALLOWS YOU        *   FILE 352
//*                       TO STUFF GOODIES FROM OS/JCT (OR          *   FILE 352
//*                       OTHER CONTROL BLOCKS) INTO CLIST          *   FILE 352
//*                       VARIABLES WITHIN A CLIST.                 *   FILE 352
//*                       (TAILORED FOR ACF2)                       *   FILE 352
//*     UCBZAP   ** BAL   FIX MSS UCBS WITH STATUS 'A' AND          *   FILE 352
//*                       USECNT>250.  CLEANS 'DIRTY' MSS           *   FILE 352
//*                       UCBS LEFT BY SOMEONE IN MVS NOT           *   FILE 352
//*                       PLAYING FAIR WITH THE UCB USECOUNT        *   FILE 352
//*                       FIELD.  ISSUES UNLOADS FOR DIRTY          *   FILE 352
//*                       UNITS AFTER FIXING THE 'ALLOC' AND        *   FILE 352
//*                       USECOUNT.                                 *   FILE 352
//*                                                                 *   FILE 352
```
