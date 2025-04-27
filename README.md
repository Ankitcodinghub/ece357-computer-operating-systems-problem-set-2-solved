# ece357-computer-operating-systems-problem-set-2-solved
**TO GET THIS SOLUTION VISIT:** [ECE357:Computer Operating Systems  Problem Set 2 Solved](https://www.ankitcodinghub.com/product/ece357computer-operating-systems-problem-set-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;70631&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp; ECE357:Computer Operating Systems&nbsp;&nbsp;Problem Set 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<strong>Problem 1 — File allocation</strong>

The following diagram depicts part of the information contained inside an inode which represents an ordinary file. Specifically, it shows the block allocation area of the inode and the size. Also shown is one data block which is being used as an indirect block. This is a Linux EXT3 filesystem and block sizes are the default 4K. <em>Note: all values in the diagram below are expressed in decimal (base 10)</em>

Inode (partial view)

Data block #9000

<table width="395">
<tbody>
<tr>
<td width="18"></td>
<td width="190">&nbsp;

<table width="115">
<tbody>
<tr>
<td width="115"></td>
</tr>
<tr>
<td width="115">65600</td>
</tr>
<tr>
<td width="115"></td>
</tr>
<tr>
<td width="115">10000</td>
</tr>
<tr>
<td width="115">10001</td>
</tr>
<tr>
<td width="115">10002</td>
</tr>
<tr>
<td width="115">10003</td>
</tr>
<tr>
<td width="115">10004</td>
</tr>
<tr>
<td width="115">10005</td>
</tr>
<tr>
<td width="115">10006</td>
</tr>
<tr>
<td width="115">10007</td>
</tr>
<tr>
<td width="115">10008</td>
</tr>
<tr>
<td width="115">10009</td>
</tr>
<tr>
<td width="115">10010</td>
</tr>
<tr>
<td width="115">10011</td>
</tr>
<tr>
<td width="115">9000</td>
</tr>
<tr>
<td width="115">0</td>
</tr>
<tr>
<td width="115">0</td>
</tr>
<tr>
<td width="115"></td>
</tr>
</tbody>
</table>
</td>
<td width="187">&nbsp;

<table width="115">
<tbody>
<tr>
<td width="115">10012</td>
</tr>
<tr>
<td width="115">10013</td>
</tr>
<tr>
<td width="115">10014</td>
</tr>
<tr>
<td width="115">10015</td>
</tr>
<tr>
<td width="115">10016</td>
</tr>
<tr>
<td width="115">The rest of this block is filled with all 0</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
size:

Direct Block

Map slots

Single Indirect Slot

Double Indirect Slot

Triple Indirect Slot

a)What is the number of the data block (express in decimal) which contains byte 4100 decimal (0x1004 hexadecimal)?

<ol>
<li>Ditto, for byte 65535 dec (0xFFFF hex)</li>
<li>If instead of EXT3, this were an EXT4 filesystem using extent-based allocation, but the same blocks wereallocated to the file in the same order, how many extent descriptors would be required? Where would the extent descriptor(s) be stored? Justify your answer.</li>
<li>Now, back to EXT3, and we modify the file as follows: we lseek to file offset 409600 (decimal) bytes and then write a single byte. How many additional data blocks does the kernel have to allocate? Justify your answer.</li>
</ol>
<strong>Problem 2 — Exploratory Questions</strong>

Answer each of the following with a paragraph or two <strong>in your own words</strong>. After you read the lecture notes, you’ll have enough material to answer. <strong>Don’t just copy the lecture notes verbatim</strong>, use your own words.

<ol start="4">
<li>In browsing the inode table of an EXT3 filesystem I observe an inode with inode type S_IFDIR and nlink==4. What does this link count tell us about the contents of this directory inode?</li>
<li>There is a directory say /home/pcooper/stuff which has about 50,000 files. The first time I open(“/home/pcooper/stuff/12345.txt”,O_RDONLY) it takes a “long time” but when I open the same file again a few seconds later the open system call returns much faster. Explain.</li>
<li>We hav e an EXT3 filesystem with journalling turned on, using mode data=ordered. Some schlemeil trips over the power cord while the system has filesystem activity. When the system powers back up, fsck examines the journal and finds this:</li>
</ol>
–BEGIN TRANSACTION ID#1234–

Copy of block containing inode #9999 type==FILE size==0 nlink==1 Copy of block containing entry 9999 in free inode bitmap, showing i9999 allocated

Copy of block containing new directory entry referring to ino9999 Copy of block containing ino100 (parent of i9999) with updated mtime

–COMMIT TRANSACTION ID #1234–

–BEGIN TRANSACTION ID#1235-Copy of block containing free block bitmap entry for block #5555, showing d5555 allocated Copy of disk block containing inode #9999, now size==4096, mtime updated

–COMMIT TRANSACTION ID #1235–

<ol>
<li>From examining the journal, what does it appear was happening?</li>
<li>Before we “replay” the above two journal entries, can we say what state inode #9999 is on the disk?iii) After the “replay” would there be any perceptable corruption of the filesystem? iv) Reconsider question (iii) but this time assume the filesystem journal mode was set to data=writeback</li>
<li>I mount a filesystem:</li>
</ol>
# mount /dev/sdb1 /mnt/usbdrives/volume01

# ls -ladi /mnt/usbdrives/volume01

Where /mnt/usbdrives/volume01 was an empty directory within the root filesystem (aka root volume) and is inode #10. What is the inode # reported by the ls command? Explain your answer.

<ol>
<li>A user runs the command mv /A/B/F1 /A/C/F2; where F1 is a fairly large file. This command runs very quickly. Then the user runs mv /A/C/F2 /A/Z/F3; but this takes quite a while to run. Why might that be the case?</li>
</ol>
<strong>SUBMISSION</strong>: Submit your answers to problems 1 / 2 in the format of either a PDF or plain text document.

<h1>Problem 3 — Recursive filesystem statistics checker</h1>
Write a program which recursively explores the filesystem starting from a given point, which is the sole argument to the program. The order in which the filesystem tree is explored (e.g. depth-first) is not important. Tabulate the following statistics and report at the end:

<ol>
<li># of inodes of each type (e.g. directory, file, symlink, etc.) encountered</li>
<li>for all regular files encountered, the sum of their sizes, and the sum of the number of disk blocks allocated forthem. The ratio gives you, in a sense, the spatial efficiency of the filesystem</li>
<li># of inodes (except, of course, directories) which have a link count of more than 1.</li>
<li># of symlinks encountered that did not (at least at the time of the exploration) resolve to a valid target</li>
<li># of directory entries encountered which would be “problematic” to enter at the keyboard. This means any name which contains non-printable characters, non-ASCII characters, or special characters that confuse the shell unless properly escaped.</li>
</ol>
Error handling: you might encounter errors, especially if you try to explore a part of the filesystem where you don’t have permission. Do not terminate the entire program because of an error. Report the error and take reasonable action to continue, if possible.

&nbsp;
