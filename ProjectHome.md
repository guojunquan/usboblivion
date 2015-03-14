<table border='0' cellspacing='10'><tr><td valign='top'>

<h1>USB Oblivion 1.10.2.0</h1>

<b>USBOblivion</b> utility designed to erase all traces of USB-connected drives and CD-ROMs from the registry in Windows XP, Windows 2003, Windows Vista, Windows 7, Windows 8 32/64-bit versions. The utility has a test mode of operation, i.e. without actually removing data from the registry, and, just in case, creates a .reg-file to undo any changes. There is also a fully automatic mode.<br>
<br>
<h2>Downloads</h2>

<a href='http://www.cherubicsoft.com/_media/projects/usboblivion/usboblivion32-1.10.2.0.zip'>usboblivion32-1.10.2.0.zip</a> - 32-bit.<br>
<br>
<a href='http://www.cherubicsoft.com/_media/projects/usboblivion/usboblivion64-1.10.2.0.zip'>usboblivion64-1.10.2.0.zip</a> - 64-bit.<br>
<br>
<h2>Usage</h2>

<blockquote>USBOblivion<code>[</code>32|64<code>]</code>.exe <code>[</code>params<code>]</code></blockquote>

<h3>Params</h3>

<ul><li>-enable - Do real clean (simulation otherwise);<br>
</li><li>-auto - Automatic run;<br>
</li><li>-nosave - Don't save backup .reg-file;<br>
</li><li>-lang:XX - Use language XX (hex-code);<br>
</li><li>-silent - Hidden mode (if possible);<br>
</li><li>-? - Show this help.</li></ul>

<h3>Languages</h3>

<ul><li>-lang:08 - Greek (by Geogeo)<br>
</li><li>-lang:09 - English (by Nikolay Raspopov)<br>
</li><li>-lang:0a - Spanish (by CesarRG)<br>
</li><li>-lang:0c - French (by Miel, Mathieu Bergounioux)<br>
</li><li>-lang:10 - Italian (by Marcello)<br>
</li><li>-lang:12 - Korean (by 4Li)<br>
</li><li>-lang:15 - Polish (by dmocha)<br>
</li><li>-lang:16 - Brazilian Portuguese (by Paulo Guzmán)<br>
</li><li>-lang:19 - Russian (by Nikolay Raspopov)<br>
</li><li>-lang:1d - Swedish (by Ake Engelbrektson)</li></ul>

<h2>System Requirements</h2>

<ul><li>Windows XP/2003/Vista/2008/7/8 32/64-bit<br>
</li><li>About 2 MB of disk space. No installation needed.<br>
</li><li>Administrative privileges.</li></ul>

<h2>Changelog</h2>

<h3>1.10.2.0</h3>

<ul><li>Added Polish translation (by dmocha)<br>
</li><li>Dropped Windows 2000 support</li></ul>

<h3>1.10.1.0</h3>

<ul><li>Added Greek translation</li></ul>

<h3>1.10.0.0</h3>

<ul><li>Added key "CurrentControlSet\Control\DeviceContainers\{40258d5b-c399-5c39-b26f-a3250b527c3c}" (Windows 8)<br>
</li><li>Added key "CurrentControlSet\Control\DeviceClasses\{7f108a28-9833-4b3b-b780-2c6b5fa5c062}" (Windows 8)<br>
</li><li>Updated translations</li></ul>

<h3>1.9.0.0</h3>

<ul><li>Added "-silent" command-line option<br>
</li><li>Added key "CurrentControlSet\Control\DeviceContainers\{beb6f4cc-ba87-5134-a5c9-a2b619ef4e3a}" (Windows 8)<br>
</li><li>Added key "CurrentControlSet\Control\DeviceClasses\{7fccc86c-228a-40ad-8a58-f590af7bfdce}" (Windows 8)</li></ul>

<h3>1.8.0.0</h3>

<ul><li>Fixed GUI freezes<br>
</li><li>Added Italian translation</li></ul>

<h3>1.7.0.0</h3>

<ul><li>Added multi-language interface and English translation</li></ul>

<h3>1.6.0.0</h3>

<ul><li>Added "CurrentControlSet\Services\USBSTOR\Enum" key clean-up<br>
</li><li>Added "CurrentControlSet\Control\usbflags" key clean-up<br>
</li><li>Added "SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\MuiCache" key clean-up<br>
</li><li>Added "SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\SyncMgr\HandlerInstances" key clean-up<br>
</li><li>Project moved to Google Code: <a href='http://code.google.com/p/usboblivion/'>http://code.google.com/p/usboblivion/</a></li></ul>

<h3>1.5.0.0</h3>

<ul><li>Added "INFCACHE.1" file removing<br>
</li><li>Added "{10497b1b-ba51-44e5-8318-a65c837b6661}" key clean-up (Windows 7)<br>
</li><li>Added SafelyRemove key clean-up</li></ul>

<h2>Translation</h2>

To help in USBOblivion translation you'll need to perform next steps:<br>
<br>
<ol><li>Download and install <a href='http://www.poedit.net/'>poEdit</a> utility;<br>
</li><li>Download <a href='http://usboblivion.googlecode.com/svn/trunk/USBOblivion.pot'>POT-file</a>;<br>
</li><li>Translate it by poEdit to your language;<br>
</li><li>Save to file "USBOblivion32.exe.XX.po" or to "USBOblivion64.exe.XX.po" near USBOblivion32.exe or USBOblivion64.exe correspondingly. Where "XX" is a 2- or 4-digit hexadecimal <a href='http://msdn.microsoft.com/en-us/library/windows/desktop/dd318693.aspx'>primary language identifier</a> for example "09" - English, "19" - Russian, "07" - German, etc.<br>
</li><li>Test it. Application loads translation according to current user language. To select other language than current specify command-line option "-lang:XX" (XX - hexadecimal language code).<br>
</li><li>Send PO-file to me: <a href='mailto:raspopov@cherubicsoft.com'>raspopov@cherubicsoft.com</a></li></ol>

Complete translations:<br>
<br>
<ul><li>English (built-in)<br>
</li><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.08.po'>Greek</a>
</li><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.0C.po'>French</a>
</li><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.10.po'>Italian</a>
</li><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.12.po'>Korean</a>
</li><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.15.po'>Polish</a>
</li><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.16.po'>Brazilian Portuguese </a>
</li><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.19.po'>Russian</a></li></ul>

Incomplete translations:<br>
<br>
<ul><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.0a.po'>Spanish</a>
</li><li><a href='http://usboblivion.googlecode.com/svn/trunk/res/USBOblivion32.exe.1d.po'>Swedish</a></li></ul>

Technical info: Translation for USBOblivion supported by my <a href='http://code.google.com/p/po-localization/'>open-source "PO-Localization" library</a>.<br>
<br>
<h2>License</h2>

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.<br>
<br>
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.<br>
<br>
You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA  02111-1307, USA.<br>
<br>
<h2>Copyrights</h2>

Copyright (C) Nikolay Raspopov, 2009-2014.<br>
<br>
</td><td width='360' valign='top'>

<h2>Screenshots</h2>

<a href='http://usboblivion.googlecode.com/svn/trunk/usboblivion-screenshot.png'><img src='http://usboblivion.googlecode.com/svn/trunk/usboblivion-screenshot.png' width='330' /></a>
<hr />
<h3>Project Information</h3>
<wiki:gadget url="http://www.ohloh.net/p/586097/widgets/project_basic_stats.xml" width="350" height="239" border="0"/><br>
<wiki:gadget url="http://www.ohloh.net/p/586097/widgets/project_users_logo.xml" height="70" border="0"/><br>
<br>
</td></tr></table>