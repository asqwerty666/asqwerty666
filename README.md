<!--
### Hi there š


**asqwerty666/asqwerty666** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->

### This is how I'm increasing entropy  š¤Ŗ

![](surfskate02.jpg)

---

 - *20220413*

Messing with XNAT these days. Learning the best way to use the experiment and subject API to store non image data. Visual reading reports and associated variables as experiment resources, custom subject variables and even pdf files with project acquisition protocols. XNAT proves to be very useful after some reading hours.

---

 - *20220401*

Lot of fun rewriting [xnatapic](https://github.com/asqwerty666/xnatapic) for reusing JSESSION ID.

---

 - *20220331*

I was having a lot of trouble with XNAT and my scripts. But last nigth I found this: [Generating and Reusing a JSESSION ID for Scripted Interactions](https://wiki.xnat.org/documentation/how-to-use-xnat/generating-and-reusing-a-jsession-id-for-scripted-interactions) and it seems to me that half of my problems with tomcat are solved. :godmode: 

---

 - *20220319*
 
 Quiet days. Doing some inavoidable repetitive tasks. The bad of semiautomatic is always that the semi part is quite large. Visual evaluation, manual checking and some other boring tasks.
 
---

 - *20220316*

I put an array into a hash, so I was dropping half of data. I needed to review the libraries looking for the output of functions. Yes it's painful but you need to doc all your functions. I don't have enough time to maintain everything properly š¢. Anyway, dumb errors are inescapable. But sometimes when everything is in place hard things could become easy. 

This days the hard work from past years are making things easier. š

![](brainage_working.png)

---

 - *20220315*
 
Doing some strange work with matlab. I have been commissioned to run [brainageR](https://github.com/james-cole/brainageR) on the HPC cluster. But no way. It depends on Matlab and I have no network licences š©ļø. So, the software runs OK but there is no way of using the SPM runtime or any container. Too bad I need to run this serial š . So, at least 10 days of calculations if everything is fine. š 

---

 - *20220309*
 
 SSDD
 
 - Studying some hierarchical clustering algorithms for improving things. Actually boring.
 - Exporting FS results in all devisable format
 
 
 
---

 - *20220216*

Working on longitudinal analysis. Figuring out a lot of things not done yet. š¤Æ

---

 - *20220211*
 
Shitty parser finished āŗļø
 
---

 - *20220210*

I should send some data in SPSS format. So, let's do some dirty tricks inside my Perl scripts to export the data through an R library. 

```
		my $rscript = mktemp($tmp_dir.'/rtmpscript.XXXXX');
		open ORS, ">$rscript";
		print ORS 'library("haven")'."\n";
		print ORS 'setwd("'.$odir.'")'."\n";
		print ORS 'read.csv("'.$tmpf.'") -> w'."\n";
		print ORS 'write_sav(w,"'.$savfile.'")'."\n";
		close ORS;
		print "$rscript\n";
		system("Rscript $rscript");
```

---

 - *20220209*

Writing another parser. š©. Some people think that improving a report means to change the format each month. š¤¦

Quiet night. 
Testing rpi3 as NFS server for backing up SDCards. Well, the SD Cards ussually get out of order and fixing again all the custom settings is boring. So, I will backup the card images in a home made NFS server an eventually I just will need to pull them into a new card. I hope.

---
 - *20220202*

Dealing with a lot of data. Very slow anonimization and uploading proccesses š¤® 

Thanks to [barrier project](https://github.com/debauchee/barrier) my work is a lot more easy these days

---
- *20220128*

Actually the WMH calculus works just fine. Doing some testing on real data. š 

![Working on now](3screens.png)

---

 - *20220127*

Working on WMH pipeline implementation with [PGS](https://wmh.isi.uu.nl/results/pgs/)

---
 - *20220125*

Lot of work: 

- Reviewing papers š
- Fixing PET-tau pipeline š„“
- Writing new imaging processing procedure š
- Making a new beamer presentation about SLURM and programatic tasks š¤  

<img src="IMG-0259.jpg" width="250" />

---
 - *20220115*

*slurm-modpy* released š

First version including a simple example. Lot of fun.

---
 - *20220114*

Working on a slurm related project. I'm doing a helper to launch sbatch jobs inside python scripts. Actually the helper writing was fun but the docs are doble large and half fun. :persevere: 

Whisky helps at nighty work, anyways

---
  - *20220104*

Updating neurodegeneration assessment implementation

---
  - *20211220*

New MRI protocol implemented. š Mostly based on *dcm3tools* and using *xnatapic* for and easy managment.  
 
---
  - *20211216*

I'm currently working on new implementations of working methods for DTI and looking for how to integrate them on XNAT. š¤¦

---
 - *20211020*
 
 Working in the integration of my pipeline with XNAT. Interaction is easy but the QC management is driving me crazy
