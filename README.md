4b353ddb3dcda9b1cc70f292cac919b9d98e7199  checksum

<h2>Checksum</h2>

<b>Synopsis</b>
    <br>
&nbsp;&nbsp;&nbsp;&nbsp;Checksum is a lightweight command line utility which takes a downloaded file and a provided sha1 sum as arguments. It will calculate a sha1 sum on the provided file, compare the calculated sum to the provided sum, and produce a human readable result based on the comparison.

<u><b>Usage</b></u>
    <br>
    &nbsp;&nbsp;&nbsp;&nbsp;checksum [<i>file</i>] [<i>sum</i>]


<u><b>Arguments</b></u>
    <br>
    &nbsp;&nbsp;&nbsp;&nbsp;<i>File</i>
    <br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A file downloaded from the internet, transferred from another machine, or newly created.
    <br>
    &nbsp;&nbsp;&nbsp;&nbsp;<i>Sum</i>
    <br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A sha1 sum provided at the time of the download OR A sha1 file provided with the download.
    <br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*Checksum will determine if the sum is provided as a file or string.

<u><b>Installation</b></u>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;First run "chmod a+x checksum" to make it executable.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;<i>Checksum</i> should be moved to /usr/bin for use from anywhere in the file system.
