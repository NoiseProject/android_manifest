Noise Project Android Source
=============================

Getting Started 
---------------

To get started with NP, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the Noise Project trees, use this command:

    repo init -u https://github.com/NoiseProject/manifest.git -b n

Then to sync up:

    repo sync -j#

`j#` depends on the number of cpu cores - just use `repo sync` if you are unsure.

To build for your device:

	. build/envsetup.sh

	lunch `choose your device`

and "run":

	make otapackage

For more information on this Github Organization and how it is structured,
please [read the wiki article](http://wiki.cyanogenmod.org/w/Github_Organization)



[@slukk](https://plus.google.com/+romoldalslukk) on G+

<img src="https://raw.github.com/NoiseProject/android_manifest/m/np.png">
