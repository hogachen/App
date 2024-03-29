
                SecureCRT(R) 6.7 (Beta) -- May 3, 2011

            Copyright (C) 1995-2011 VanDyke Software, Inc.
                        All rights reserved.


Product Overview
----------------

SecureCRT protects your passwords, user accounts, and data, combining
rock-solid terminal emulation with the strong encryption, broad
authentication options, and data integrity of the Secure Shell (SSH)
protocol.

SecureCRT provides versatile solutions for a wide range of business,
network management, information security, and development tasks, from
accessing host-based applications and administering servers to
securely accessing behind-the-firewall network resources like e-mail,
files, and printers.

SecureCRT supports SSH1, SSH2, Telnet, Telnet/SSL, RLogin, Serial,
and TAPI protocols and authentication via password, public key, X.509
certificate, and Kerberos v5 via GSSAPI.  Ciphers include AES,
Twofish, Blowfish, 3DES, and RC4.

Choose from a wide range of emulations including VT100, VT102, VT220,
ANSI, SCO ANSI, Wyse 50/60, Xterm, and Linux console -� all with ANSI
color.  Unicode support includes the ability to display character sets
from multiple languages, support for languages with right-to-left
reading order, and a character encoding list that includes
commonly-used encodings as well as all encodings supported by the
local system.

SecureCRT features a multi-session tabbed interface with extensive
session management and customization features.  Customization options
include toolbars, menus, keymaps, button bar, and login scripts, as
well as fonts, cursors, and color schemes. 

Named sessions and firewalls let you create individual configurations
that can be used on a session-specific basis.  Other features include
auto logon, printing, Emacs mode, and SOCKS firewall support.

Powerful scripting capabilities including ActiveX scripting support
for VBScript and other scripting languages on Windows, embedded
Python support, and the script recorder save you valuable time by 
automating routine configuration tasks.  Secure file transfers can be
performed using Zmodem or Xmodem from an SSH1 or SSH2 session.  Upload
files easily by dragging and dropping them onto an SFTP tab or session
window.

Save steps with the close integration of SecureCRT and the SecureFX(R)
file transfer client, which share sessions and settings that let you
run SFTP, FTP, SCP, and FTP/SSL file transfer sessions without
reentering passwords.

SecureCRT includes a 30-day try-before-you-buy evaluation license for
the fully functional application and access to VanDyke Software(R)
technical support.


Contents
--------

   1. New for SecureCRT 6.7
   2. Enhancement Requests, Updates, and Questions
   3. Encryption Export
   4. Upgrades
   5. Product History
   6. SecureCRT Features
   7. Reporting Bugs
   8. Contact Information


1. New For SecureCRT 6.7
------------------------

SecureCRT 6.7 delivers a third major platform -� Linux �- with versions
for Ubuntu and Red Hat.  This release features a new Connect toolbar
and many improvements to the button bar and scripting, like Python
support in the script recorder and copy and paste for button bar 
buttons.

Here are some of the new features in SecureCRT 6.7:

Linux

  - SecureCRT for Linux brings the extensive SecureCRT feature set to 
    Ubuntu 10.x and RHEL 5.5.  Noteworthy for Linux are local shell 
    access and Python scripting.

Connect bar

  - The Connect bar provides a text entry box to connect to a session
    quickly without opening a dialog.  The Connect bar supports
    SecureCRT command-line options.

Scripting enhancements

  - Script recorder adds Python support: Automate connections and
    routines using the Python script recorder, which records
    keystrokes and then generates a Python script.

  - �Run Script� from a key or button: Map a key or button to browse
    for a script to run.

  - New scripting functions: The FileOpenDialog() function opens a
    file browser and returns the selected file.  ScriptFullName()
    returns the full path and filename of the currently running
    script.  The Connect() function adds an optional parameter to
    suppress pop-up messages.

Button bar enhancements

  - Add more than ten buttons to a button bar, copy and paste buttons
    from one button bar onto another, and move buttons within a button
    bar.

Please see SecureCRT_History.txt in the SecureCRT program group for
the list of new features, changes, and bug fixes.


2. Enhancement Requests, Updates, and Questions
-----------------------------------------------

We want to hear from you.  Let us know what features you would like to
see in future releases of SecureCRT by visiting our website at:

  http://www.vandyke.com/feedback.php

Every VanDyke Software license includes a full year of upgrades and
technical support.  To receive e-mail notification when new releases
of SecureCRT are available, sign up for our SecureCRT mailing list at:

  https://secure.vandyke.com/cgi-bin/subscribe.php?RMF=3

For tips, ideas, and product news, subscribe to VanDyke Software's
monthly newsletter at:

  https://secure.vandyke.com/cgi-bin/subscribe.php?RMF=3

You can also exchange useful tips and ideas with your peers and
VanDyke developers by joining the online forums:

  http://forums.vandyke.com/index.php?RMF=3

If you have any questions, please visit our website at:

  http://www.vandyke.com/feedback.php

SecureCRT for Windows supports Windows Server 2008 R2, Windows7,
Windows Server 2008, Windows Vista, 2003, Windows Server 2003 R2,
Windows Server 2003, and Windows XP for x86 and x64.


3. Encryption Export
--------------------

This Software is subject to export control.  The Software may be
transmitted, exported, or re-exported only under applicable export
laws and restrictions and regulations of the United States Bureau of
Industry and Security or foreign agencies or authorities.  By
downloading or using the Software, you are agreeing to comply with
export controls.  For more information see:

  http://www.vandyke.com/download/export.html


4. Upgrades
-----------

Users who purchased SecureCRT on or after October 1, 2009 are
eligible for a free upgrade to SecureCRT 6.7.  All users can evaluate
SecureCRT 6.7 for 30 days free of charge.  For more information on
upgrade eligibility and purchasing upgrades, please visit:

  http://www.vandyke.com/pricing/corporate/upgrades


5. Product History
------------------

The list of changes made for this release of SecureCRT can be found
in the SecureCRT_History.txt file installed with the program.


6. SecureCRT Features 
---------------------

Support for SSH1 and SSH2 Secure Shell protocols.
  - SSH2 Protocol support:
    - AES-128, AES-192, AES-256, Twofish, Blowfish, 3DES, and RC4
      ciphers.
    - RSA and DSA host key support.
    - Multiple ordered authentication methods, ciphers and MACs.
    - Public Key Assistant makes it easier to upload public keys.
    - Local port forwarding, X11 forwarding, remote forwarding, and
      dynamic forwarding.
    - MD5, MD5-96, SHA1, and SHA1-96 MACs.
    - RSA, DSA, public-key, X.509 certificate, Kerberos v5 via GSSAPI,
      and password authentication methods.
    - SFTP tab creates an SFTP session to an existing SSH session.
  - SSH1 Protocol support:
    - Blowfish, DES, 3DES, and RC4 ciphers.
    - RSA, TIS, and password authentication.
    - Local port forwarding, X11 forwarding.

Session Management.
  - Named sessions store different preferences for different hosts.
  - Tabbed sessions allow multiple sessions in the same window.
  - Tabbed sessions can be moved in and out of windows.
  - Launch multiple selected sessions in tabs with a single click.
  - Option to minimize SecureCRT windows to the Activator utility in
    the system tray.
  - Built-in SSH agent allows keys to be explicitly added or removed.
  - A session can be logged to a file, including options for logging
    custom data.

Configuration & Customization.
  - Easy configuration of basic SSH, port forwarding, remote
    forwarding and other settings in Session Options dialog.
  - Named firewalls.
  - Customizable toolbar and menus.
  - User-defined number of savelines (scrollback) up to 32,000.
  - User-configurable number of rows and columns.
  - User-defined foreground, background, and bold colors.
  - User-defined keymaps.
  - User-defined button bar.
  - User-defined word delimiter characters for double-click.
  - Emacs mode maps ALT+<key> to send ESC+<key>.
  - Real-time keyword highlighting.

Advanced Terminal Emulation.
  - Quality VT100, VT102, VT220, Linux console, SCO ANSI, Wyse 50/60
    and ANSI emulation:
    - VT line drawing.
    - Support for bold, underline, and reverse attributes.
    - Double-width and double-height fonts.
    - 80/132 column switching.
    - VT100 and VT220 keyboard emulation.
    - Optional ANSI color.
    - 256-color Xterm.
    - Xterm extensions for mouse support and changing title bar.
    - Unicode support includes the ability to display character sets
      from multiple languages, support for multi-byte character sets,
      right-to-left reading order languages, and an extensive
      character encoding list.
 
Other Features.
  - FIPS 140-2 validated cryptographic library support.
  - Variable compression increases performance on slow connections.
  - Simple interface for automating logins.
  - Support for Telnet, Telnet/SSL, and RLogin protocols:
    - Telnet supports Negotiate About Window Size (NAWS).
    - Telnet supports Local Flow Control (LFLOW).
  - Serial (COM) device support.
  - Integration with SecureFX 3.x or higher.
  - Scripting language support for VBScript and JScript.
  - Embedded support for Python scripting.
  - Script recorder.
  - Zmodem, Xmodem, and Ymodem file transfer (upload and download).
  - Drag and drop file transfer (upload).
  - Printing: auto print, selection, screen, and pass-through 
    printing.
  - Modem dialer support: configure and save modem, country code,
    phone, and redial settings for TAPI sessions.
  - SOCKS firewall support with password authentication.
  - Unauthenticated and basic HTTP proxy support.
  - Generic proxy firewall support.
  - Copy and paste, including an "auto copy" option and a "paste on
    middle or right mouse click" option.
  - Chat window option provides an editable type-ahead buffer with
    history support.
  - Support for use from the command line or web browsers.
  - Support for standard insertion caret so that it can be tracked
    by screen access technology for the blind.


7. Reporting Bugs
-----------------

If you experience something you believe is a bug, please fill out
our online form at:

  http://www.vandyke.com/feedback.php

Please do not assume someone else will report it.  We will try to
resolve reported bugs as quickly as possible.  However, we can't
resolve bugs that are not reported.

Please describe the problem in as much detail as possible. Please
include the following information:

  - Version of SecureCRT (as shown in the About dialog)
  - Operating system and version


8. Contact Information
-----------------------

For information on ordering licenses, please visit the VanDyke
Software website:

  http://www.vandyke.com


All other inquiries should be directed to:

  VanDyke Software, Inc.
  4848 Tramway Ridge Dr. NE
  Suite 101
  Albuquerque, NM 87111
  USA

  Inquiry form: http://www.vandyke.com/feedback.php


VanDyke Software, SecureCRT, and SecureFX are trademarks or registered
trademarks of VanDyke Software, Inc. in the United States and/or other
countries.

All other products and services mentioned are trademarks or registered
trademarks of their respective companies.