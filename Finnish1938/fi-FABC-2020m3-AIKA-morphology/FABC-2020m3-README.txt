
                              "FABC 2020.3 README"

  (c) 1997 by the Analytical Bible Concordance Project of Aika[media]
  (c) March 2020 by Anssi Yli-Jyrä
 
  for the 2020.3 Text Edition of the 1933/1938 Finnish Bible
  Translation by the Finnish Analytical Bible Concordance Project (the
  FABC 2020.3 Text Edition)

  This description (FABC 2020.3 README) of the FABC 2020.3 Text
  Edition of the 1933/1938 Finnish Bible translation is licenced under
  a Creative Commons Attribution Share-Alike 4.0 International license
  https://creativecommons.org/licenses/by-sa/4.0/. For attribution
  purposes, credit the Finnish Analytical Bible Concordance Project of
  Aika[media] (c) 1997 and Anssi Yli-Jyrä (c) March 2020.


The 1933/1938 Finnish Bible Translation
=======================================

The 1933/1938 Finnish Bible translation is called 'Pyhä Raamattu' (the
Holy Bible).  It is in public domain.  No authoritative, 100% exact
copy of the translation is known to exist.

The described digital edition of the 1933/1938 Finnish Bible consists
of 66 digitised books.  The corresponding files '01-gn.txt'
... '66-rv.txt' are in this directory.  The files and their checksums
are specified in 'books-md5.txt' copied below.  

You may distribute these files freely, but you are kindly asked to
distribute the FABC 2020.3 README as well or describe the edition
indirectly by citing its name.

The file names can be mapped to book names used by the FABC Project
using this Python code:

   filenames = ['01-gn','02-ex','03-lv','04-nu','05-dt','06-js','07-jg','08-ru','09-1s','10-2s','11-1k','12-2k','13-1x','14-2x','15-er','16-ne','17-es','18-jb','19-ps','20-pr','21-ec','22-ca','23-is','24-jr','25-lm','26-ek','27-da','28-ho','29-jl','30-am','31-ob','32-on','33-mi','34-na','35-ha','36-zp','37-hg','38-zc','39-ma','40-mt','41-mk','42-lk','43-jn','44-ac','45-rm','46-1c','47-2c','48-ga','49-ep','50-pp','51-cl','52-1q','53-2q','54-1t','55-2t','56-ti','57-pm','58-hb','59-jm','60-1p','61-2p','62-1j','63-2j','64-3j','65-jd','66-rv']
   booknames = ['1Ms','2Ms','3Ms','4Ms','5Ms','Jos','Tm','Ruut','1Sm','2Sm','1Kn','2Kn','1Ak','2Ak','Esr','Neh','Est','Job','Ps','Snl','Srn','KV','Jes','Jer','Val','Hel','Dan','Hos','Jl','Aam','Ob','Jna','Mka','Naah','Hab','Sef','Hag','Sak','Mal','Mt','Mk','Lk','Jh','Apt','Rm','1Kr','2Kr','Gal','Ef','Flp','Kol','1Ts','2Ts','1Tm','2Tm','Tiit','Flm','Heb','Jaak','1Pt','2Pt','1Jh','2Jh','3Jh','Juud','Ilm']
   for fn in filenames:
       print("{} -> {}".format(fn, booknames[filenames.index(fn)]))

The Format of the FABC 2020.3 Edition
=====================================

Inside the files, we have named the books of the Finnish Bible
according to the list:

    1Ms, 2Ms, 3Ms, 4Ms, 5Ms, Jos, Tm, Ruut, 1Sm, 2Sm, 1Kn, 2Kn, 1Ak,
    2Ak, Esr, Neh, Est, Job, Ps, Snl, Srn, KV, Jes, Jer, Val, Hel,
    Dan, Hos, Jl, Aam, Ob, Jna, Mka, Naah, Hab, Sef, Hag, Sak, Mal,
    Mt, Mk, Lk, Jh, Apt, Rm, 1Kr, 2Kr, Gal, Ef, Flp, Kol, 1Ts, 2Ts,
    1Tm, 2Tm, Tiit, Flm, Heb, Jaak, 1Pt, 2Pt, 1Jh, 2Jh, 3Jh, Juud, Ilm

Each verse is referred with verse references such as

     1Ms␣1:1
     Ps␣1:1
     Ob␣0:1
     Flm␣0:1

The white space is signaled with the Unicode Character “␣” (U+2423)
known as "Open Box". The verse references of the translation are
included to the text and separated with a space from the surrounding
words.  The same character is used to indicate the location of white
spaces in the text.  After a period, there is only one Open Box
character.  In the end of the verse, there is also one.

The verses are separated with the new line character.  The text is not
otherwise wrapped to separate lines.  Instead, each verse corresponds
to a one line.

The resulting plain text of the Finnish Bible has been encoded with
the UTF8 encoding and distributed to 66 files corresponding the books.
When concatenated, the text would look like this:

   1Ms␣1:1␣Alussa␣loi␣Jumala␣taivaan␣ja␣maan.␣
   1Ms␣1:2␣Ja␣maa␣oli␣autio␣ja␣tyhjä,␣ja␣pimeys␣oli␣syvyyden␣päällä,␣ja␣Jumalan␣Henki␣liikkui␣vetten␣päällä.␣
   ...
   Ilm␣22:20␣Hän,␣joka␣näitä␣todistaa,␣sanoo:␣"Totisesti,␣minä␣tulen␣pian".␣Amen,␣tule,␣Herra␣Jeesus!␣
   Ilm␣22:21␣Herran␣Jeesuksen␣armo␣olkoon␣kaikkien␣kanssa.␣Amen.␣

Checking the Identity of the Text Files
=======================================

The MD5 message-digest algorithm is a widely used hash function
producing a 128-bit hash value from a digital message.  This is
available on Mac OS X and other systems as a command line utility.
The utility was applied to the set of files of the digital edition
to produce the following checksums:

MD5 (01-gn.txt) = 722c76bd365ba2b8d9908a60421e911b
MD5 (02-ex.txt) = e06c7a5da5ae4cc7d5b5af3a819ab8d5
MD5 (03-lv.txt) = 577c2cbefafb1acf605dc103b5e152ef
MD5 (04-nu.txt) = b187c8b19795e6bf0ee92e84ca6b269a
MD5 (05-dt.txt) = 41e6e3dd3ef8d1969d514596abc039e0
MD5 (06-js.txt) = fce800e786b93f28b03163d165e5ba03
MD5 (07-jg.txt) = a9b022764596ceaaef48af8dd618e368
MD5 (08-ru.txt) = ac987b1ffb47eabdbe03db1293074e25
MD5 (09-1s.txt) = 82b16f7c3a5a21e073090f78aaab9d8c
MD5 (10-2s.txt) = 0411e825992a90c69c15be200264564c
MD5 (11-1k.txt) = d6d507707fd11e23f5b78ef20ee0e3f8
MD5 (12-2k.txt) = 416d4cb3fb9c1e1e8a734b25a0a14e06
MD5 (13-1x.txt) = b8e1f71bb17d253d9b8402818c2ea12f
MD5 (14-2x.txt) = 8e43cb86d70fa21f19b55b6f2e2f4725
MD5 (15-er.txt) = 871e5e74abe19d90fbf358d7cb224d70
MD5 (16-ne.txt) = 82446edeff07c94523eec16d90427506
MD5 (17-es.txt) = 43f66ca01e4b6263cb0730aaa7811e4d
MD5 (18-jb.txt) = 9976724d6737b03cf7d76437ed1dc00d
MD5 (19-ps.txt) = 4d8d99ac18251604a7a52e4fa0151806
MD5 (20-pr.txt) = 0394205a801dfcf2fa35ffc2d0b915a5
MD5 (21-ec.txt) = 12d00d2b422b717eb86d9303d4c51bb1
MD5 (22-ca.txt) = e6163d386f76b014f6c4906e3badde6b
MD5 (23-is.txt) = ef02a353437339b266f13e720200671d
MD5 (24-jr.txt) = 88953da71c2a20bd7945cfb6cece7663
MD5 (25-lm.txt) = 1cc54c438a26c312cb2a674257e056a4
MD5 (26-ek.txt) = 13c73e782865e40e2e4b34182c875c54
MD5 (27-da.txt) = b73f8ee0bf53fc92920633384a2c9f06
MD5 (28-ho.txt) = 82b996d4ca1d43e77a90660216b64aee
MD5 (29-jl.txt) = 24673e04a08378db7ec5823640701ac0
MD5 (30-am.txt) = 4e96d28d550a508200d92204cdb56c17
MD5 (31-ob.txt) = d7329fa907a3fdea81ed049605b61397
MD5 (32-on.txt) = 3d077469c3de398a5751d12be8662dee
MD5 (33-mi.txt) = 87b18c4187908fbc3473811ac0700aed
MD5 (34-na.txt) = 8759fe048b6466d48108faf196e6c82a
MD5 (35-ha.txt) = 94bbbcf97df4614a4a621b31668599cf
MD5 (36-zp.txt) = e4ddfe9baf83049bdf9de34d8323bfe8
MD5 (37-hg.txt) = ecb6caecfaaad5586674e3fe7d319a17
MD5 (38-zc.txt) = 0492f3c88eaea5d9dc3d514d7044140e
MD5 (39-ma.txt) = cd17f9a6fc005adf71e88af0bec52c3d
MD5 (40-mt.txt) = 8136fcdd905bf3f598fe564f38cc6acc
MD5 (41-mk.txt) = 38ce55a94cf0b31c78bd8cca7217b4e4
MD5 (42-lk.txt) = 03615098124f1ecf13346f97dc522c4e
MD5 (43-jn.txt) = 6bd3f4c185f336a1fbfabbbe27a50ccc
MD5 (44-ac.txt) = 7ebc3ff5dbeaf303c680c452f79b2a69
MD5 (45-rm.txt) = 79746b9f7218d99c77d8bb3080c7c7d6
MD5 (46-1c.txt) = c8842eb668dbf071d10e4ccb834a3c34
MD5 (47-2c.txt) = 89875160d7ad7bc32bbe926bc8e60562
MD5 (48-ga.txt) = 318fab68f4d790d8833be5db1bff07a0
MD5 (49-ep.txt) = e58d5f0cb03ee268b4924d5ce4f04554
MD5 (50-pp.txt) = a1285e3a102dd9d8683ddaa5e23b7d6d
MD5 (51-cl.txt) = 74ab449217c1b5fb09570f4c03bf678c
MD5 (52-1q.txt) = f2f88ce156ec0ef91974d4aadd517695
MD5 (53-2q.txt) = 58663cd8bf308fa282c6bd6b0af92c72
MD5 (54-1t.txt) = c1b9ecb9af2fbbd09e79ae75051fbe1a
MD5 (55-2t.txt) = 8133443356f49651ead8f0a2a784e94f
MD5 (56-ti.txt) = 71381a8f6b760e6d388402fb54b9e8dd
MD5 (57-pm.txt) = 89a9b874261c23822fa785c88cf77f6c
MD5 (58-hb.txt) = 8e5ae877085d5fd8e9f8eefffd650ecc
MD5 (59-jm.txt) = 644c32a0ad6f259158bca8823044c1fc
MD5 (60-1p.txt) = 006830dd603c16c41439f76aecd857bb
MD5 (61-2p.txt) = c0cc4eefa74d3703134cca203284d657
MD5 (62-1j.txt) = 1fa2befe10b3ef788052d7e877ef7fe9
MD5 (63-2j.txt) = 9758ac7a48a39c68c8f246f4664da4a9
MD5 (64-3j.txt) = 102bdfc46cff32ad61ff26e8218f18d5
MD5 (65-jd.txt) = ff71201d80531fce9c658bf349de0440
MD5 (66-rv.txt) = b7124036491373d7ec9c7f5965416b28

If two text files have the same MD5 checksum, a 100% certainty of
the identity of two MD5-equivalent text files can be obtained by
direct comparison, but this is not likely to be necessary as it is
extremely rare to have two files with the exactly same MD5 hash value.
   
A Version Tracking Initiative
=============================

The editor of the FABC 2020.3 Edition of the 1933/1938 Finnish Bible
translation wishes that the further digital editions would describe
their validation target.  This can be, for example, one of the
following targets:

1. Exact copy of the official originals of the translation stored
in the National Archive.

2. A consensus of a grammar and punctuation corrected translation
recommended for a printed representation of the Finnish translation.

3. An approximate majority vote representing the most common text form
in actual printed impressions.

4. A documented result of a more or less corrected OCR pass, a
typist's output or an editorial outcome resulting from the comparison
and proof reading.

The FABC 2020.3 Text Edition belongs to the category 4 although its
documentation is not as complete as we wished.

The History of the 2020.3 FABC Edition
======================================

The FABC 2020.3 Text Edition has been prepared by combining 2-3 sets of
files containing of different versions of ditisised text of 1933/1938
translation and several printed impressions of the translation.  There
is an intention to document the digital text sources and the printed
impressions and who have produced them but currently we do not have
reliable information.  These digital versions that were used were
around in 1991-1997.

Further processing of the inofficial FABC files was carried out in
2020 by Anssi Yli-Jyrä but this should not have changed anything in
the text.  The release of the FABC 2020.3 Text Edition happens in 
March 2020.

On Appying the License
======================

According the above license related to this material (FABC 2020.3
README), you are free to

   Share — copy and redistribute the material in any medium or format

   Adapt — remix, transform, and build upon the material
   for any purpose, even commercially. 

Under the following terms:

   Attribution — You must give appropriate credit, provide a link to
   the license, and indicate if changes were made. You may do so in
   any reasonable manner, but not in any way that suggests the
   licensor endorses you or your use.

   ShareAlike — If you remix, transform, or build upon the material,
   you must distribute your contributions under the same license as
   the original.

   No additional restrictions — You may not apply legal terms or
   technological measures that legally restrict others from doing
   anything the license permits.

Please include this FABC 2020.3 README if you distribute the FABC
2020.3 Text Edition of the translation.

If you distribute changes to the FABC 2020.3 Text Edition, you should
name your distribution differently while sharing it.  Please also
update and rename the FABC 2020.3 README, describing the changes, and
include the updated README to your distribution under the CC-BY-AS 4.0
license.  In this file, you should attribute the creators of the FABC
2020.3 README.

Under the conditions of the license, you may also include the relevant
parts of this desciption to your TEI XML headers or to the resource
descriptions of data center facilities.

