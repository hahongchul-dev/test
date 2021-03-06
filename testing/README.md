## testing

#### Images and ground truth text required for testing Tesseract.

A large number of test images are those provided by Google as part of
original release of Tesseract for testing and as part of unittests
for Tesseract 4.0.0. Original source of various examples used for testing
were documented earlier in [FILES](https://github.com/tesseract-ocr/test/blob/master/testing/FILES).
That information is now moved here.

- hebrew.png - Sample from Hebrew OCR with Nikud project by Adi Oz and Vered Shani
    project URL - http://www.cs.bgu.ac.il/~nlpproj/hocr/
    direct link to image - http://www.cs.bgu.ac.il/~nlpproj/hocr/images/image00.png

- hebtypo.jpg - Sample from OCR and Hebrew on the Web project at Universiteit van Amsterdam
    project URL - http://cf.uba.uva.nl/en/collections/rosenthaliana/menasseh/hebtypo.html
    direct link to image - http://cf.uba.uva.nl/en/collections/rosenthaliana/menasseh/gif/hebtypo.jpg

- DuTillet1004Pg2LG.jpg -  Sample from Hebrew Matthew Project with parallel texts in Hebrew & Greek
        as well as English page/chapter labels with Arabic numerals - test with -l heb+grc+eng
    project URL - http://www.torahresource.com/Dutillet.html
    direct link to image - http://www.torahresource.com/DuTillet/DuTillet1004Pg2LG.jpg

- hebrew-nikud-genesis-1-2.png - Genesis 1-2 Hebrew example from OCR forum
    forum post - https://community.logos.com/forums/p/16124/277997.aspx
    direct link to image - https://community.logos.com/cfs-filesystemfile.ashx/__key/CommunityServer.Discussions.Components.Files/77/4578.Gen.png





#### Fonts required for unittests

The following fonts should be copied to test/testing folder for stringrenderer_test to run.

- Arab
https://packages.ubuntu.com/trusty/fonts-arabeyes  - GNU  General Public License

- Lohit Hindi
https://releases.pagure.org/lohit/lohit-hindi-ttf-2.4.3.tar.gz  - GNU General Public License, version 2

- UNBatang
https://packages.ubuntu.com/trusty/fonts-unfonts-core  - GPL-2

- Verdana
https://packages.ubuntu.com/trusty/ttf-mscorefonts-installer  - /usr/share/doc/ttf-mscorefonts-installer/copyright
