+++
title = "Project Trident 12-U10 Now Available"
menutitle = "12-U10 Available"
description = "STABLE release repository updates"
date = "2019-10-21"
draft = true
pre = "<i class='fa fa-wrench'></i>	"
+++

This is the tenth general package update to the STABLE release repository based upon TrueOS 12-Stable.

# Package Changes From STABLE 12-U9
*For a full list of available packages, please visit [the GitHub repository](https://github.com/project-trident/trident-core/tree/master/version-lists)!*

## Package Summary
* New Packages: 45
* Deleted Packages: 46
* Updated Packages: 753

## New Packages (45)
* OpenFodder (games/openfodder) : 1.5.3
* abclock (x11-clocks/abclock) : 1.0d_4
* amath (math/amath) : 1.8.5
* apache-commons-cli (java/apache-commons-cli) : 1.4
* apache-commons-collections (java/apache-commons-collections) : 3.2.1
* apache-commons-configuration (devel/apache-commons-configuration) : 1.10
* apache-commons-daemon (devel/apache-commons-daemon) : 1.2.2
* apache-commons-dbutils (databases/apache-commons-dbutils) : 1.7
* apache-commons-digester (textproc/apache-commons-digester) : 2.1_1
* apache-commons-io (devel/apache-commons-io) : 2.6
* apache-commons-jelly (lang/apache-commons-jelly) : 1.0
* apache-commons-jxpath (devel/apache-commons-jxpath) : 1.3
* apache-commons-lang (java/apache-commons-lang) : 2.6
* apache-commons-lang3 (java/apache-commons-lang3) : 3.8.1
* apache-commons-logging (java/apache-commons-logging) : 1.2
* apache-commons-modeler (devel/apache-commons-modeler) : 2.0.1
* apache-commons-net (net/apache-commons-net) : 3.6
* apache-commons-primitives (java/apache-commons-primitives) : 1.0
* darknet (math/darknet) : g20180914_1
* direvent (sysutils/direvent) : 5.2
* dual-dhclient-daemon (net/dual-dhclient-daemon) : 0.1
* exifprobe (graphics/exifprobe) : 2.0.1
* gemmlowp (math/gemmlowp) : g20190812
* gtk-layer-shell (x11-toolkits/gtk-layer-shell) : 0.1.0
* jstrack (science/jstrack) : 3.4.0
* libstorj (net/libstorj) : 1.0.3_2
* lsblk (sysutils/lsblk) : 1.0
* luv (devel/luv) : 1.30.1.1
* mcsim (math/mcsim) : 6.1.0
* mimalloc (devel/mimalloc) : 1.1.0
* protonvpn-cli (security/protonvpn-cli) : 1.1.2_1
* py27-pipreqs (devel/py-pipreqs) : 0.4.9
* py27-yapsnmp (net-mgmt/py-yapsnmp) : 0.7.8_8
* py27-yarg (devel/py-yarg) : 0.1.9
* py36-pipreqs (devel/py-pipreqs) : 0.4.9
* py36-tensorflow (science/py-tensorflow) : 1.14.0_2
* py36-yarg (devel/py-yarg) : 0.1.9
* rshim-user-space (sysutils/rshim-user-space) : 1.0
* spin (devel/spin) : 6.5.0
* stoken (security/stoken) : 0.92
* tcping (net/tcping) : 1.3.5_1
* viewnior (graphics/viewnior) : 1.6_5
* vmaf (multimedia/vmaf) : 1.3.15
* wcm (x11/wcm) : 0.3
* wdisplays (x11/wdisplays) : s20190924

## Deleted Packages (46)
* asterisk15 (net/asterisk15) : Moved to net/asterisk16. [2019-10-04] Has expired: Asterisk 15.x will reach EOL on 2019-10-03. Please migrate to net/asterisk16
* asterisk15-espeak (audio/asterisk-espeak) : Unknown reason
* asterisk15-flite (audio/asterisk-flite) : Unknown reason
* asterisk15-g72x (net/asterisk-g72x) : Unknown reason
* dovecot (mail/dovecot) : Unknown reason
* dovecot-fts-xapian (mail/dovecot-fts-xapian) : Unknown reason
* dovecot-pigeonhole (mail/dovecot-pigeonhole) : Unknown reason
* froxlor (sysutils/froxlor) : Unknown reason
* gtk-gnutella (net-p2p/gtk-gnutella) : Unknown reason
* jakarta-commons-cli (java/jakarta-commons-cli) : Moved to java/apache-commons-cli. [2019-10-06] Renamed upstream
* jakarta-commons-collections (java/jakarta-commons-collections) : Moved to java/apache-commons-collections. [2019-10-06] Renamed upstream
* jakarta-commons-configuration (devel/jakarta-commons-configuration) : Moved to devel/apache-commons-configuration. [2019-10-06] Renamed upstream
* jakarta-commons-daemon (devel/jakarta-commons-daemon) : Moved to devel/apache-commons-daemon. [2019-10-07] Renamed upstream
* jakarta-commons-dbutils (databases/jakarta-commons-dbutils) : Moved to databases/apache-commons-dbutils. [2019-10-06] Renamed upstream
* jakarta-commons-digester (textproc/jakarta-commons-digester) : Moved to textproc/apache-commons-digester. [2019-10-06] Renamed upstream
* jakarta-commons-io (devel/jakarta-commons-io) : Moved to devel/apache-commons-io. [2019-10-06] Renamed upstream
* jakarta-commons-jelly (lang/jakarta-commons-jelly) : Moved to lang/apache-commons-jelly. [2019-10-06] Renamed upstream
* jakarta-commons-jxpath (devel/jakarta-commons-jxpath) : Moved to devel/apache-commons-jxpath. [2019-10-06] Renamed upstream
* jakarta-commons-lang (java/jakarta-commons-lang) : Moved to java/apache-commons-lang. [2019-10-06] Renamed upstream
* jakarta-commons-lang3 (java/jakarta-commons-lang3) : Moved to java/apache-commons-lang3. [2019-10-07] Renamed upstream
* jakarta-commons-logging (java/jakarta-commons-logging) : Moved to java/apache-commons-logging. [2019-10-06] Renamed upstream
* jakarta-commons-modeler (devel/jakarta-commons-modeler) : Moved to devel/apache-commons-modeler. [2019-10-06] Renamed upstream
* jakarta-commons-net (net/jakarta-commons-net) : Moved to net/apache-commons-net. [2019-10-06] Renamed upstream
* jakarta-commons-primitives (java/jakarta-commons-primitives) : Moved to java/apache-commons-primitives. [2019-10-06] Renamed upstream
* openra (games/openra) : Unknown reason
* php-mode.el-emacs27 (lang/php-mode.el) : Unknown reason
* php-mode.el-emacs27_nox (lang/php-mode.el) : Unknown reason
* py27-fonttools-graphite (print/py-fonttools-graphite) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py27-fonttools-interpolatable (print/py-fonttools-interpolatable) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py27-fonttools-lxml (print/py-fonttools-lxml) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py27-fonttools-plot (print/py-fonttools-plot) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py27-fonttools-symfont (print/py-fonttools-symfont) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py27-fonttools-ufo (print/py-fonttools-ufo) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py27-fonttools-unicode (print/py-fonttools-unicode) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py27-fonttools-woff (print/py-fonttools-woff) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py36-fonttools-graphite (print/py-fonttools-graphite) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py36-fonttools-interpolatable (print/py-fonttools-interpolatable) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py36-fonttools-lxml (print/py-fonttools-lxml) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py36-fonttools-plot (print/py-fonttools-plot) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py36-fonttools-symfont (print/py-fonttools-symfont) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py36-fonttools-ufo (print/py-fonttools-ufo) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py36-fonttools-unicode (print/py-fonttools-unicode) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* py36-fonttools-woff (print/py-fonttools-woff) : Moved to print/py-fonttools. [2019-10-07] Folded back into main port
* qbittorrent-nox (net-p2p/qbittorrent) : Unknown reason
* softhsm (security/softhsm) : Moved to security/softhsm2. [2019-10-04] Has expired: End-of-life announced
* yuzu (emulators/yuzu) : Unknown reason

## Updated Packages (753)
* 0ad (games/0ad) : 0.0.23b_6 -> 0.0.23b_7
* 1password-client (security/1password-client) : 0.5.7 -> 0.6.2
* CLDR (textproc/CLDR) : 35.1 -> 36.0
* FreeCAD (cad/freecad) : 0.18.3_2 -> 0.18.3_3
* GiNaC (math/GiNaC) : 1.7.7 -> 1.7.8
* InsightToolkit (science/InsightToolkit) : 5.0.1_1 -> 5.0.1_2
* R (math/R) : 3.6.1_2 -> 3.6.1_3
* R-cran-RJSONIO (converters/R-cran-RJSONIO) : 1.3.1.2_1 -> 1.3.1.3
* R-cran-backports (math/R-cran-backports) : 1.1.4_1 -> 1.1.5
* R-cran-data.table (devel/R-cran-data.table) : 1.12.2 -> 1.12.4
* R-cran-htmltools (textproc/R-cran-htmltools) : 0.3.6_3 -> 0.4.0
* R-cran-htmlwidgets (www/R-cran-htmlwidgets) : 1.3_2 -> 1.5
* R-cran-later (devel/R-cran-later) : 0.8.0_1 -> 1.0.0
* R-cran-maptools (astro/R-cran-maptools) : 0.9.5_1 -> 0.9.8
* R-cran-promises (devel/R-cran-promises) : 1.0.1_2 -> 1.1.0
* R-cran-stringi (textproc/R-cran-stringi) : 1.4.3_1 -> 1.4.3_2
* acerhdf-kmod (sysutils/acerhdf-kmod) : 0.1.2 -> 0.1.3
* aegisub (multimedia/aegisub) : 3.2.2_41 -> 3.2.2_42
* amass (dns/amass) : 3.1.6 -> 3.1.10
* an (games/an) : 1.2_7 -> 1.2_8
* aom (multimedia/aom) : 1.0.0.2439 -> 1.0.0.2474
* apache-jmeter (www/jmeter) : 2.11_1 -> 2.11_2
* apache-openoffice (editors/openoffice-4) : 4.1.7 -> 4.1.7_1
* apache-openoffice-devel (editors/openoffice-devel) : 4.2.1568906168 -> 4.2.1568906168_2
* asymptote (math/asymptote) : 2.44_8 -> 2.56_1
* avidemux-plugins (multimedia/avidemux-plugins) : 2.6.11_16 -> 2.6.11_17
* aws-sdk-cpp (devel/aws-sdk-cpp) : 1.7.182 -> 1.7.197
* awscli (devel/awscli) : 1.16.227_2 -> 1.16.255
* barrier (sysutils/barrier) : 2.3.1 -> 2.3.2
* bind9-devel (dns/bind9-devel) : 9.15.3.a0.2019.09.30 -> 9.15.4.a0.2019.10.06
* bn-freebsd-doc (misc/freebsd-doc-bn) : 53316 -> 53465
* boost-libs (devel/boost-libs) : 1.71.0 -> 1.71.0_1
* bspwm (x11-wm/bspwm) : 0.9.7 -> 0.9.9
* ca_root_nss (security/ca_root_nss) : 3.46_1 -> 3.46.1_1
* cacti (net-mgmt/cacti) : 1.2.5 -> 1.2.7
* cage (x11-wm/cage) : 0.1.1_2 -> 0.1.1_4
* calibre (deskutils/calibre) : 3.48.0_1 -> 4.0.0
* cargo-audit (security/cargo-audit) : 0.9.2 -> 0.9.3
* casadi (math/casadi) : 3.4.5.49_2 -> 3.5.0
* cascadia-code (x11-fonts/cascadia-code) : 1909.16 -> 1910.04
* ccextractor (multimedia/ccextractor) : 0.85_14 -> 0.85_15
* charva (devel/charva) : 1.1.4_5 -> 1.1.4_6
* chromium (www/chromium) : 76.0.3809.132 -> 76.0.3809.132_1
* chromium-gn (devel/chromium-gn) : 76.0.3809.132 -> 76.0.3809.132_1
* cimg (graphics/cimg) : 2.7.2 -> 2.7.3
* cinelerra-gg (multimedia/cinelerra-gg) : 5.1.20180714_10 -> 5.1.20180714_11
* citra (emulators/citra) : s20190924 -> s20191005
* citra-qt5 (emulators/citra-qt5) : s20190924 -> s20191005
* clickhouse (databases/clickhouse) : 19.11.5.28_1 -> 19.11.5.28_3
* cling (lang/cling) : 0.5.2018.08.13_3 -> 0.5.2018.08.13_4
* cliqz (www/cliqz) : 1.29.0 -> 1.29.0_1
* clover (lang/clover) : 18.3.2_3 -> 18.3.2_4
* cmake (devel/cmake) : 3.15.3 -> 3.15.4
* cmake-doc (devel/cmake-doc) : 3.15.3 -> 3.15.4
* cmake-gui (devel/cmake-gui) : 3.15.3 -> 3.15.4
* coin-or-cppad (math/cppad) : 20190200.4 -> 20190200.5
* couchdb (databases/couchdb) : 1.7.2_3 -> 1.7.2_4
* couchdb2 (databases/couchdb2) : 2.3.1_2 -> 2.3.1_3
* cowrie (security/cowrie) : 1.6.0 -> 1.9.7
* cppcms (www/cppcms) : 1.2.1_6 -> 1.2.1_7
* cups-filters (print/cups-filters) : 1.25.6 -> 1.25.7
* cxxtest (devel/cxxtest) : 3.10.1_1 -> 4.4
* cyberchef (security/cyberchef) : 9.7.1_2 -> 9.7.7
* cyrus-imapd30 (mail/cyrus-imapd30) : 3.0.11 -> 3.0.11_1
* da-freebsd-doc (misc/freebsd-doc-da) : 53316 -> 53465
* dav1d (multimedia/dav1d) : 0.4.0 -> 0.4.0_1
* dcmtk (graphics/dcmtk) : 3.6.4_2 -> 3.6.4_3
* ddclient (dns/ddclient) : 3.8.3.104_1 -> 3.8.3.104_2
* de-freebsd-doc (misc/freebsd-doc-de) : 53316 -> 53465
* dee (devel/dee) : 1.2.7_12 -> 1.2.7_13
* dino (net-im/dino) : 0.0.20190220_1 -> 0.0.20190220_2
* dnscap (dns/dnscap) : 1.10.2 -> 1.10.3
* dnsdbq (dns/dnsdbq) : 1.0.0 -> 1.4.0
* dvdstyler (multimedia/dvdstyler) : 2.9.6_13 -> 3.1
* dwdiff (textproc/dwdiff) : 2.0.9_12 -> 2.0.9_13
* easyrpg-player (games/easyrpg-player) : 0.6.1_1 -> 0.6.1_2
* eksctl (sysutils/eksctl) : 0.5.3 -> 0.6.0
* el-freebsd-doc (misc/freebsd-doc-el) : 53316 -> 53465
* elasticsearch6 (textproc/elasticsearch6) : 6.5.4 -> 6.8.3
* emacs-devel (editors/emacs-devel) : 27.0.50.20190917 -> 27.0.50.20191007
* emacs-devel-nox (editors/emacs-devel) : 27.0.50.20190917 -> 27.0.50.20191007
* emby-server (multimedia/emby-server) : 4.2.1.0 -> 4.2.1.0_1
* emscripten (devel/emscripten) : 1.38.45 -> 1.38.47
* en-freebsd-doc (misc/freebsd-doc-en) : 53316 -> 53465
* endless-sky (games/endless-sky) : 0.9.8_5 -> 0.9.10
* endless-sky-high-dpi (games/endless-sky-high-dpi) : 0.9.8 -> 0.9.10
* epiphany (www/epiphany) : 3.28.5_4 -> 3.28.5_5
* erlang (lang/erlang) : 21.3.8.7 -> 21.3.8.8
* erlang-java (lang/erlang-java) : 21.3.8.7 -> 21.3.8.8
* erlang-runtime20 (lang/erlang-runtime20) : 20.3.8.22 -> 20.3.8.23
* erlang-runtime21 (lang/erlang-runtime21) : 21.3.8.7 -> 21.3.8.8
* erlang-runtime22 (lang/erlang-runtime22) : 22.1.1 -> 22.1.2
* erlang-wx (lang/erlang-wx) : 21.3.8.7 -> 21.3.8.8
* es-freebsd-doc (misc/freebsd-doc-es) : 53316 -> 53465
* evolution (mail/evolution) : 3.28.5_3 -> 3.28.5_4
* evolution-data-server (databases/evolution-data-server) : 3.28.5_3 -> 3.28.5_4
* evolution-ews (mail/evolution-ews) : 3.28.5_2 -> 3.28.5_3
* facter (sysutils/facter) : 3.14.4_1 -> 3.14.5
* fastahack (biology/fastahack) : g20160702 -> 1.0.0
* fasttracker2 (audio/fasttracker2) : 1.00 -> 1.00_1
* ffmpeg (multimedia/ffmpeg) : 4.2.1_3 -> 4.2.1_5
* firebird25-client (databases/firebird25-client) : 2.5.8_3 -> 2.5.8_4
* firebird25-server (databases/firebird25-server) : 2.5.8_3 -> 2.5.8_4
* firefox (www/firefox) : 69.0.1_2 -> 69.0.2_1
* firefox-esr (www/firefox-esr) : 68.1.0_4 -> 68.1.0_5
* fluent-bit (sysutils/fluent-bit) : 1.0.4 -> 1.3.1
* fossil (devel/fossil) : 2.9_1 -> 2.10
* fr-freebsd-doc (misc/freebsd-doc-fr) : 53316 -> 53465
* fr-verbiste (french/verbiste) : 0.1.44 -> 0.1.47
* freebsd-doc-all (misc/freebsd-doc-all) : 53316 -> 53465
* freebsd-release-manifests (misc/freebsd-release-manifests) : 20190928 -> 20191004
* freerdp (net/freerdp) : 2.0.0.r4_5 -> 2.0.0.r4_6
* fusefs-smbnetfs (sysutils/fusefs-smbnetfs) : 0.6.1_2 -> 0.6.1_3
* garcon (sysutils/garcon) : 0.6.4_1 -> 0.6.4_2
* gcc7-devel (lang/gcc7-devel) : 7.4.1.s20190926 -> 7.4.1.s20191003
* gcc8-devel (lang/gcc8-devel) : 8.3.1.s20190927 -> 8.3.1.s20191004
* gcc9-devel (lang/gcc9-devel) : 9.2.1.s20190928 -> 9.2.1.s20191005
* gdcm (devel/gdcm) : 3.0.2 -> 3.0.3
* gdisk (sysutils/gdisk) : 1.0.4_5 -> 1.0.4_6
* giacxcas (math/giacxcas) : 1.5.0.63_1 -> 1.5.0.67
* gitlab-ce (www/gitlab-ce) : 12.3.2 -> 12.3.3
* gitlab-runner (devel/gitlab-runner) : 12.1.0 -> 12.3.0
* gmic (graphics/gmic) : 2.7.1_1 -> 2.7.2
* gnucash (finance/gnucash) : 3.7 -> 3.7_1
* gnustep-base (lang/gnustep-base) : 1.26.0_2 -> 1.26.0_3
* gnustep-gui (x11-toolkits/gnustep-gui) : 0.27.0_1 -> 0.27.0_2
* go14 (lang/go14) : 1.4.3_5 -> 1.4.3_6
* googlemock (devel/googlemock) : 1.8.1_2 -> 1.10.0
* googletest (devel/googletest) : 1.8.1_3 -> 1.10.0
* gperf31 (devel/gperf31) : 3.1 -> 3.1_2
* gpxsee (graphics/gpxsee) : 7.11 -> 7.14
* grafana6 (www/grafana6) : 6.3.5 -> 6.4.0
* gravity-lang (lang/gravity) : 0.7.5 -> 0.7.8
* gretl (math/gretl) : 2019.a_5 -> 2019.a_6
* gromacs (science/gromacs) : 2019.3_3 -> 2019.4
* groonga (textproc/groonga) : 9.0.7 -> 9.0.8
* gsequencer (audio/gsequencer) : 2.3.3 -> 2.3.8
* gsoap (devel/gsoap) : 2.8.92 -> 2.8.93
* gstreamer1-plugins-x265 (multimedia/gstreamer1-plugins-x265) : 1.14.4_3 -> 1.14.4_4
* harfbuzz-icu (print/harfbuzz-icu) : 2.6.2 -> 2.6.2_1
* hexyl (sysutils/hexyl) : 0.5.1_3 -> 0.6.0
* hs-pandoc-citeproc (textproc/hs-pandoc-citeproc) : 0.16.2_1 -> 0.16.2_2
* httpclient (www/httpclient) : 4.5.10 -> 4.5.10_1
* hu-freebsd-doc (misc/freebsd-doc-hu) : 53316 -> 53465
* ibus-typing-booster (textproc/ibus-typing-booster) : 2.6.6 -> 2.6.7
* icu (devel/icu) : 64.2 -> 65.1
* icu-le-hb (devel/icu-le-hb) : 1.0.3.3_12 -> 1.0.3.3_13
* icu-lx (devel/icu-lx) : 64.2 -> 65.1
* inlets (net/inlets) : 2.4.1 -> 2.5.0
* iridium-browser (www/iridium) : 2019.04.73_1 -> 2019.04.73_2
* istio (sysutils/istio) : 1.2.5 -> 1.3.1
* it-freebsd-doc (misc/freebsd-doc-it) : 53316 -> 53465
* ja-freebsd-doc (misc/freebsd-doc-ja) : 53316 -> 53465
* jakarta-commons-beanutils (java/jakarta-commons-beanutils) : 1.9.2 -> 1.9.2_1
* jakarta-commons-httpclient (java/jakarta-commons-httpclient) : 3.1_1 -> 3.1_2
* jenkins (devel/jenkins) : 2.198 -> 2.199
* jwt-cli (www/jwt-cli) : 2.5.0_1 -> 2.5.1
* kamailio (net/kamailio) : 5.2.4_1 -> 5.2.4_2
* kbibtex (databases/kbibtex) : 0.9_5 -> 0.9_6
* kdb (databases/kdb) : 3.2.0_1 -> 3.2.0_2
* kibana6 (textproc/kibana6) : 6.5.4_2 -> 6.8.3
* kiwix-lib (devel/kiwix-lib) : 5.1.0_1 -> 5.1.0_2
* ko-freebsd-doc (misc/freebsd-doc-ko) : 53316 -> 53465
* kodi-addon-inputstream.adaptive-devel (multimedia/kodi-addon-inputstream.adaptive-devel) : 2.5.0 -> 2.5.1
* kops (sysutils/kops) : 1.13.0 -> 1.14.0
* kubectl (sysutils/kubectl) : 1.16.0 -> 1.16.1
* leatherman (devel/leatherman) : 1.7.2 -> 1.7.3
* libbpg (graphics/libbpg) : 0.9.7_9 -> 0.9.7_10
* libcdr01 (graphics/libcdr01) : 0.1.5_4 -> 0.1.5_5
* libe-book (textproc/libe-book) : 0.1.3_14 -> 0.1.3_15
* libfolia (textproc/libfolia) : 1.15_4 -> 1.15_5
* libfreehand (graphics/libfreehand) : 0.1.2_14 -> 0.1.2_15
* libheif (graphics/libheif) : 1.3.2_4 -> 1.3.2_5
* libical (devel/libical) : 3.0.4_2 -> 3.0.4_3
* libkml (science/libkml) : 1.3.0_14 -> 1.3.0_15
* liblcf (games/liblcf) : 0.6.1 -> 0.6.1_1
* libmspub01 (print/libmspub01) : 0.1.4_12 -> 0.1.4_13
* libnormaliz (math/libnormaliz) : 3.8.0_1 -> 3.8.1
* libopenmpt (audio/libopenmpt) : 0.4.8 -> 0.4.9
* libosmesa (graphics/libosmesa) : 18.3.2_4 -> 18.3.2_5
* libosmo-abis (devel/libosmo-abis) : 0.6.0 -> 0.7.0
* libplacebo (graphics/libplacebo) : 1.18.0_2 -> 1.21.0
* libpsl (dns/libpsl) : 0.21.0 -> 0.21.0_1
* libqalculate (math/libqalculate) : 3.0.0_2 -> 3.0.0_3
* libqxp (textproc/libqxp) : 0.0.0_12 -> 0.0.0_13
* libredwg (cad/libredwg) : 0.8 -> 0.9
* libreoffice (editors/libreoffice) : 6.3.2_1 -> 6.3.2_3
* libressl-devel (security/libressl-devel) : 3.0.0 -> 3.0.1
* librsvg2-rust (graphics/librsvg2-rust) : 2.46.0_1 -> 2.46.1
* libva-intel-media-driver (multimedia/libva-intel-media-driver) : 19.3.p4_1 -> 19.3.0
* libvisio01 (textproc/libvisio01) : 0.1.6_14 -> 0.1.6_15
* libvterm (devel/libvterm) : git20161218 -> 0.1.1
* libxatracker (graphics/libxatracker) : 18.3.2 -> 18.3.2_1
* libzim (devel/libzim) : 5.0.0_1 -> 5.0.0_2
* libzmf (graphics/libzmf) : 0.0.2_17 -> 0.0.2_18
* linux-c6-devtools (devel/linux-c6-devtools) : 6.10_6 -> 6.10_7
* linux-c7-devtools (devel/linux-c7-devtools) : 7.7.1908 -> 7.7.1908_1
* lis (math/lis) : 2.0.19_1 -> 2.0.20
* logstash6 (sysutils/logstash6) : 6.5.4 -> 6.8.3
* ltfs (sysutils/ltfs) : 2.4.1.2 -> 2.4.1.2_1
* lzma (archivers/lzma) : 18.05 -> 19.00
* maim (graphics/maim) : 5.5.3_1 -> 5.5.3_2
* maltrail (security/maltrail) : 0.14 -> 0.15
* manifest (os/manifest) : 1570628606 -> 1571313289
* mariadb55-client (databases/mariadb55-client) : 5.5.65_1 -> 5.5.65_2
* mariadb55-server (databases/mariadb55-server) : 5.5.65_1 -> 5.5.65_2
* mercurial (devel/mercurial) : 5.1.1 -> 5.1.2
* mesa-dri (graphics/mesa-dri) : 18.3.2_6 -> 18.3.2_7
* mesa-libs (graphics/mesa-libs) : 18.3.2_1 -> 18.3.2_2
* mime4j (mail/mime4j) : 0.7.2 -> 0.7.2_1
* minio (www/minio) : 2019.08.29.00.25.01 -> 2019.10.02.21.19.38
* minio-client (www/minio-client) : 2019.08.29.00.40.57 -> 2019.10.02.19.41.02
* mkgmap (astro/mkgmap) : r4291 -> r4294
* mkp224o (security/mkp224o) : 1.3.0 -> 1.4.0
* mkvtoolnix (multimedia/mkvtoolnix) : 37.0.0 -> 38.0.0
* mn-freebsd-doc (misc/freebsd-doc-mn) : 53316 -> 53465
* mod_php74 (www/mod_php74) : 7.4.0.r1 -> 7.4.0.r3
* mothur (biology/mothur) : 1.42.3_1 -> 1.43.0
* mppp (math/mppp) : 0.16_1 -> 0.17
* mroonga (databases/mroonga) : 9.07 -> 9.08
* musicpd (audio/musicpd) : 0.21.15_1 -> 0.21.15_2
* mysql80-client (databases/mysql80-client) : 8.0.17 -> 8.0.17_1
* mysql80-server (databases/mysql80-server) : 8.0.17 -> 8.0.17_1
* nano (editors/nano) : 4.4 -> 4.5
* ncmpcpp (audio/ncmpcpp) : 0.8.2_11 -> 0.8.2_12
* neovim (editors/neovim) : 0.3.8 -> 0.4.2
* neovim-qt (editors/neovim-qt) : 0.2.12_1 -> 0.2.14
* newsboat (www/newsboat) : 2.17_1 -> 2.17.1
* nextcloud-calendar-php71 (www/nextcloud-calendar) : 1.7.0 -> 1.7.1
* nextcloud-calendar-php72 (www/nextcloud-calendar) : 1.7.0 -> 1.7.1
* nextcloud-calendar-php73 (www/nextcloud-calendar) : 1.7.0 -> 1.7.1
* nextcloud-contacts-php71 (www/nextcloud-contacts) : 3.1.3 -> 3.1.4
* nextcloud-contacts-php72 (www/nextcloud-contacts) : 3.1.3 -> 3.1.4
* nextcloud-contacts-php73 (www/nextcloud-contacts) : 3.1.3 -> 3.1.4
* nextcloud-notes-php71 (www/nextcloud-notes) : 3.0.2 -> 3.0.3
* nextcloud-notes-php72 (www/nextcloud-notes) : 3.0.2 -> 3.0.3
* nextcloud-notes-php73 (www/nextcloud-notes) : 3.0.2 -> 3.0.3
* nextcloud-php71 (www/nextcloud) : 16.0.4 -> 17.0.0
* nextcloud-php72 (www/nextcloud) : 16.0.4 -> 17.0.0
* nextcloud-php73 (www/nextcloud) : 16.0.4 -> 17.0.0
* nextcloud-tasks-php71 (www/nextcloud-tasks) : 0.11.1 -> 0.11.3
* nextcloud-tasks-php72 (www/nextcloud-tasks) : 0.11.1 -> 0.11.3
* nextcloud-tasks-php73 (www/nextcloud-tasks) : 0.11.1 -> 0.11.3
* nextcloud-twofactor_totp-php71 (security/nextcloud-twofactor_totp) : 3.0.1 -> 4.0.0
* nextcloud-twofactor_totp-php72 (security/nextcloud-twofactor_totp) : 3.0.1 -> 4.0.0
* nextcloud-twofactor_totp-php73 (security/nextcloud-twofactor_totp) : 3.0.1 -> 4.0.0
* nextcloud-twofactor_u2f-php71 (security/nextcloud-twofactor_u2f) : 3.0.1 -> 4.0.0
* nextcloud-twofactor_u2f-php72 (security/nextcloud-twofactor_u2f) : 3.0.1 -> 4.0.0
* nextcloud-twofactor_u2f-php73 (security/nextcloud-twofactor_u2f) : 3.0.1 -> 4.0.0
* nl-freebsd-doc (misc/freebsd-doc-nl) : 53316 -> 53465
* nnn (misc/nnn) : 2.6 -> 2.7
* node (www/node) : 12.10.0 -> 12.11.1
* node10 (www/node10) : 10.16.3 -> 10.16.3_1
* node6 (www/node6) : 6.17.1_1 -> 6.17.1_2
* node8 (www/node8) : 8.16.1 -> 8.16.1_1
* noson-app (audio/noson-app) : 3.15.0 -> 3.15.2
* nsq (net/nsq) : 1.1.0 -> 1.2.0
* nss (security/nss) : 3.46 -> 3.46.1
* nsysctl (sysutils/nsysctl) : 1.2 -> 1.2.1
* ntl (math/ntl) : 11.3.2_3 -> 11.4.0
* nuspell (textproc/nuspell) : 2.3.0_1 -> 2.3.0_2
* nzbhydra2 (news/nzbhydra2) : 2.6.2 -> 2.7.2
* objecthash (devel/objecthash) : 20160802_8 -> 20160802_9
* obs-studio (multimedia/obs-studio) : 24.0.0 -> 24.0.1
* ocserv (net/ocserv) : 0.12.4_1 -> 0.12.4_2
* octave-forge-dicom (math/octave-forge-dicom) : 0.2.2_3 -> 0.2.2_4
* opencascade (cad/opencascade) : 7.3.0_7 -> 7.4.0
* opencv (graphics/opencv) : 3.4.1_23 -> 3.4.1_24
* opencv-core (graphics/opencv-core) : 3.4.1_23 -> 3.4.1_24
* opencv-java (graphics/opencv-java) : 3.4.1_23 -> 3.4.1_24
* openfx-arena (graphics/openfx-arena) : 2.3.14_13 -> 2.3.14_14
* openjfx8-devel (java/openjfx8-devel) : 8.u202.b07_3 -> 8.u202.b07_4
* openldap-server (net/openldap24-server) : 2.4.48 -> 2.4.48_1
* openrct2 (games/openrct2) : 0.2.3_2 -> 0.2.3_3
* openttd (games/openttd) : 1.9.1_2 -> 1.9.1_3
* openvswitch (net/openvswitch) : 2.11.1_1 -> 2.12.0
* os-generic-buildkernel (os/buildkernel) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-buildkernel-debug (os/buildkernel-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-buildworld (os/buildworld) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-kernel (os/kernel) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-kernel-debug (os/kernel-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-kernel-debug-symbols (os/kernel-debug-symbols) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-kernel-symbols (os/kernel-symbols) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland (os/userland) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-base (os/userland-base) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-base-bootstrap (os/userland-base-bootstrap) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-bin (os/userland-bin) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-boot (os/userland-boot) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-conf (os/userland-conf) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-debug (os/userland-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-devtools (os/userland-devtools) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-docs (os/userland-docs) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-lib (os/userland-lib) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-lib32 (os/userland-lib32) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-lib32-development (os/userland-lib32-development) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-rescue (os/userland-rescue) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-sbin (os/userland-sbin) : 12.1.20191003115222 -> 12.1.20191015211820
* os-generic-userland-tests (os/userland-tests) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-buildkernel (os/buildkernel) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-buildkernel-debug (os/buildkernel-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-buildworld (os/buildworld) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-kernel (os/kernel) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-kernel-debug (os/kernel-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-kernel-debug-symbols (os/kernel-debug-symbols) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-kernel-symbols (os/kernel-symbols) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland (os/userland) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-base (os/userland-base) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-base-bootstrap (os/userland-base-bootstrap) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-bin (os/userland-bin) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-boot (os/userland-boot) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-conf (os/userland-conf) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-debug (os/userland-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-devtools (os/userland-devtools) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-docs (os/userland-docs) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-lib (os/userland-lib) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-lib32 (os/userland-lib32) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-lib32-development (os/userland-lib32-development) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-rescue (os/userland-rescue) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-sbin (os/userland-sbin) : 12.1.20191003115222 -> 12.1.20191015211820
* os-minimal-userland-tests (os/userland-tests) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-buildkernel (os/buildkernel) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-buildkernel-debug (os/buildkernel-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-buildworld (os/buildworld) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-kernel (os/kernel) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-kernel-debug (os/kernel-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-kernel-debug-symbols (os/kernel-debug-symbols) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-kernel-symbols (os/kernel-symbols) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland (os/userland) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-base (os/userland-base) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-base-bootstrap (os/userland-base-bootstrap) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-bin (os/userland-bin) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-boot (os/userland-boot) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-conf (os/userland-conf) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-debug (os/userland-debug) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-devtools (os/userland-devtools) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-docs (os/userland-docs) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-lib (os/userland-lib) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-lib32 (os/userland-lib32) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-lib32-development (os/userland-lib32-development) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-rescue (os/userland-rescue) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-sbin (os/userland-sbin) : 12.1.20191003115222 -> 12.1.20191015211820
* os-nozfs-userland-tests (os/userland-tests) : 12.1.20191003115222 -> 12.1.20191015211820
* osmo (deskutils/osmo) : 0.4.2_7 -> 0.4.2_8
* osquery (sysutils/osquery) : 3.3.2_4 -> 3.3.2_5
* p5-Cairo (graphics/p5-Cairo) : 1.106 -> 1.107
* p5-Net-FTPSSL (ftp/p5-Net-FTPSSL) : 0.41 -> 0.42
* p5-Net-OAuth2 (net/p5-Net-OAuth2) : 0.65 -> 0.66
* p5-Role-Tiny (devel/p5-Role-Tiny) : 2.000008 -> 2.001001
* p5-Sub-Quote (devel/p5-Sub-Quote) : 2.006003 -> 2.006006
* p5-Term-Choose-Util (devel/p5-Term-Choose-Util) : 0.101 -> 0.102
* p5-Test-HTTP-LocalServer (www/p5-Test-HTTP-LocalServer) : 0.68 -> 0.69
* p5-Test-Timer (devel/p5-Test-Timer) : 2.10 -> 2.11
* packr (devel/packr) : 2.6.0 -> 2.7.1
* parrot (lang/parrot) : 8.1.0_10 -> 8.1.0_11
* pdfbox (print/pdfbox) : 2.0.14 -> 2.0.14_1
* perl5-devel (lang/perl5-devel) : 5.31.4.270 -> 5.31.4.296
* pgbadger (databases/pgbadger) : 10.3 -> 11.1
* pgmetrics (databases/pgmetrics) : 1.7.0 -> 1.7.1
* phoronix-test-suite-php71 (benchmarks/phoronix-test-suite) : 9.0.0 -> 9.0.1
* phoronix-test-suite-php72 (benchmarks/phoronix-test-suite) : 9.0.0 -> 9.0.1
* phoronix-test-suite-php73 (benchmarks/phoronix-test-suite) : 9.0.0 -> 9.0.1
* phoronix-test-suite-php74 (benchmarks/phoronix-test-suite) : 9.0.0 -> 9.0.1
* php-mode.el-emacs26 (lang/php-mode.el) : 1.21.4_1 -> 1.22.0
* php-mode.el-emacs26_canna (lang/php-mode.el) : 1.21.4_1 -> 1.22.0
* php-mode.el-emacs26_nox (lang/php-mode.el) : 1.21.4_1 -> 1.22.0
* php71-intl (devel/php71-intl) : 7.1.32 -> 7.1.32_1
* php71-pear-PHP_CodeSniffer (devel/pear-PHP_CodeSniffer) : 3.4.2 -> 3.5.0
* php71-pear-horde-Horde_Text_Diff (textproc/pear-Horde_Text_Diff) : 2.2.0 -> 2.2.1
* php71-pecl-timezonedb (misc/pecl-timezonedb) : 2019.2 -> 2019.3
* php72-intl (devel/php72-intl) : 7.2.23 -> 7.2.23_1
* php72-pear-PHP_CodeSniffer (devel/pear-PHP_CodeSniffer) : 3.4.2 -> 3.5.0
* php72-pear-horde-Horde_Text_Diff (textproc/pear-Horde_Text_Diff) : 2.2.0 -> 2.2.1
* php72-pecl-timezonedb (misc/pecl-timezonedb) : 2019.2 -> 2019.3
* php73-intl (devel/php73-intl) : 7.3.10 -> 7.3.10_1
* php73-pear-PHP_CodeSniffer (devel/pear-PHP_CodeSniffer) : 3.4.2 -> 3.5.0
* php73-pear-horde-Horde_Text_Diff (textproc/pear-Horde_Text_Diff) : 2.2.0 -> 2.2.1
* php73-pecl-timezonedb (misc/pecl-timezonedb) : 2019.2 -> 2019.3
* php74 (lang/php74) : 7.4.0.r1 -> 7.4.0.r3
* php74-bcmath (math/php74-bcmath) : 7.4.0.r1 -> 7.4.0.r3
* php74-bz2 (archivers/php74-bz2) : 7.4.0.r1 -> 7.4.0.r3
* php74-calendar (misc/php74-calendar) : 7.4.0.r1 -> 7.4.0.r3
* php74-ctype (textproc/php74-ctype) : 7.4.0.r1 -> 7.4.0.r3
* php74-curl (ftp/php74-curl) : 7.4.0.r1 -> 7.4.0.r3
* php74-dba (databases/php74-dba) : 7.4.0.r1 -> 7.4.0.r3
* php74-dom (textproc/php74-dom) : 7.4.0.r1 -> 7.4.0.r3
* php74-enchant (textproc/php74-enchant) : 7.4.0.r1 -> 7.4.0.r3
* php74-exif (graphics/php74-exif) : 7.4.0.r1 -> 7.4.0.r3
* php74-ffi (devel/php74-ffi) : 7.4.0.r1 -> 7.4.0.r3
* php74-fileinfo (sysutils/php74-fileinfo) : 7.4.0.r1 -> 7.4.0.r3
* php74-filter (security/php74-filter) : 7.4.0.r1 -> 7.4.0.r3
* php74-ftp (ftp/php74-ftp) : 7.4.0.r1 -> 7.4.0.r3
* php74-gd (graphics/php74-gd) : 7.4.0.r1 -> 7.4.0.r3
* php74-gettext (devel/php74-gettext) : 7.4.0.r1 -> 7.4.0.r3
* php74-gmp (math/php74-gmp) : 7.4.0.r1 -> 7.4.0.r3
* php74-iconv (converters/php74-iconv) : 7.4.0.r1 -> 7.4.0.r3
* php74-imap (mail/php74-imap) : 7.4.0.r1 -> 7.4.0.r3
* php74-intl (devel/php74-intl) : 7.4.0.r1 -> 7.4.0.r3_1
* php74-json (devel/php74-json) : 7.4.0.r1 -> 7.4.0.r3
* php74-ldap (net/php74-ldap) : 7.4.0.r1 -> 7.4.0.r3
* php74-mbstring (converters/php74-mbstring) : 7.4.0.r1 -> 7.4.0.r3
* php74-mysqli (databases/php74-mysqli) : 7.4.0.r1 -> 7.4.0.r3
* php74-odbc (databases/php74-odbc) : 7.4.0.r1 -> 7.4.0.r3
* php74-opcache (www/php74-opcache) : 7.4.0.r1 -> 7.4.0.r3
* php74-openssl (security/php74-openssl) : 7.4.0.r1 -> 7.4.0.r3
* php74-pcntl (devel/php74-pcntl) : 7.4.0.r1 -> 7.4.0.r3
* php74-pdo (databases/php74-pdo) : 7.4.0.r1 -> 7.4.0.r3
* php74-pdo_dblib (databases/php74-pdo_dblib) : 7.4.0.r1 -> 7.4.0.r3
* php74-pdo_firebird (databases/php74-pdo_firebird) : 7.4.0.r1 -> 7.4.0.r3
* php74-pdo_mysql (databases/php74-pdo_mysql) : 7.4.0.r1 -> 7.4.0.r3
* php74-pdo_odbc (databases/php74-pdo_odbc) : 7.4.0.r1 -> 7.4.0.r3
* php74-pdo_pgsql (databases/php74-pdo_pgsql) : 7.4.0.r1 -> 7.4.0.r3
* php74-pdo_sqlite (databases/php74-pdo_sqlite) : 7.4.0.r1 -> 7.4.0.r3
* php74-pear-PHP_CodeSniffer (devel/pear-PHP_CodeSniffer) : 3.4.2 -> 3.5.0
* php74-pear-horde-Horde_Text_Diff (textproc/pear-Horde_Text_Diff) : 2.2.0 -> 2.2.1
* php74-pecl-timezonedb (misc/pecl-timezonedb) : 2019.2 -> 2019.3
* php74-pgsql (databases/php74-pgsql) : 7.4.0.r1 -> 7.4.0.r3
* php74-phar (archivers/php74-phar) : 7.4.0.r1 -> 7.4.0.r3
* php74-posix (sysutils/php74-posix) : 7.4.0.r1 -> 7.4.0.r3
* php74-pspell (textproc/php74-pspell) : 7.4.0.r1 -> 7.4.0.r3
* php74-readline (devel/php74-readline) : 7.4.0.r1 -> 7.4.0.r3
* php74-session (www/php74-session) : 7.4.0.r1 -> 7.4.0.r3
* php74-shmop (devel/php74-shmop) : 7.4.0.r1 -> 7.4.0.r3
* php74-simplexml (textproc/php74-simplexml) : 7.4.0.r1 -> 7.4.0.r3
* php74-snmp (net-mgmt/php74-snmp) : 7.4.0.r1 -> 7.4.0.r3
* php74-soap (net/php74-soap) : 7.4.0.r1 -> 7.4.0.r3
* php74-sockets (net/php74-sockets) : 7.4.0.r1 -> 7.4.0.r3
* php74-sodium (security/php74-sodium) : 7.4.0.r1 -> 7.4.0.r3
* php74-sqlite3 (databases/php74-sqlite3) : 7.4.0.r1 -> 7.4.0.r3
* php74-sysvmsg (devel/php74-sysvmsg) : 7.4.0.r1 -> 7.4.0.r3
* php74-sysvsem (devel/php74-sysvsem) : 7.4.0.r1 -> 7.4.0.r3
* php74-sysvshm (devel/php74-sysvshm) : 7.4.0.r1 -> 7.4.0.r3
* php74-tidy (www/php74-tidy) : 7.4.0.r1 -> 7.4.0.r3
* php74-tokenizer (devel/php74-tokenizer) : 7.4.0.r1 -> 7.4.0.r3
* php74-xml (textproc/php74-xml) : 7.4.0.r1 -> 7.4.0.r3
* php74-xmlreader (textproc/php74-xmlreader) : 7.4.0.r1 -> 7.4.0.r3
* php74-xmlrpc (net/php74-xmlrpc) : 7.4.0.r1 -> 7.4.0.r3
* php74-xmlwriter (textproc/php74-xmlwriter) : 7.4.0.r1 -> 7.4.0.r3
* php74-xsl (textproc/php74-xsl) : 7.4.0.r1 -> 7.4.0.r3
* php74-zip (archivers/php74-zip) : 7.4.0.r1 -> 7.4.0.r3
* php74-zlib (archivers/php74-zlib) : 7.4.0.r1 -> 7.4.0.r3
* phpmailer6 (mail/phpmailer6) : 6.0.7 -> 6.1.1
* phpunit8-php71 (devel/phpunit8) : 8.3.5 -> 8.4.0
* phpunit8-php72 (devel/phpunit8) : 8.3.5 -> 8.4.0
* phpunit8-php73 (devel/phpunit8) : 8.3.5 -> 8.4.0
* phpunit8-php74 (devel/phpunit8) : 8.3.5 -> 8.4.0
* pl-freebsd-doc (misc/freebsd-doc-pl) : 53316 -> 53465
* plex-ttf (x11-fonts/plex-ttf) : 2.0.0 -> 3.0.0
* plexmediaserver-plexpass (multimedia/plexmediaserver-plexpass) : 1.17.0.1841 -> 1.18.0.1846
* poedit (editors/poedit) : 1.8.4_27 -> 1.8.4_28
* polyphone (audio/polyphone) : 2.1.0 -> 2.1.1
* portfmt (ports-mgmt/portfmt) : g20191001 -> g20191003
* ports (os/ports) : 12.1.20191003115222 -> 12.1.20191015211820
* postfix (mail/postfix) : 3.4.7 -> 3.4.7_1
* postfix-current (mail/postfix-current) : 3.5.20190922 -> 3.5.20190922_1
* postfix-current-sasl (mail/postfix-current-sasl) : 3.5.20190922 -> 3.5.20190922_1
* postfix-ldap-sasl (mail/postfix-ldap-sasl) : 3.4.7 -> 3.4.7_1
* postfix-sasl (mail/postfix-sasl) : 3.4.7 -> 3.4.7_1
* postgresql10-server (databases/postgresql10-server) : 10.10 -> 10.10_1
* postgresql11-pg_repack (databases/pg_repack) : 1.4.4_1 -> 1.4.5
* postgresql11-server (databases/postgresql11-server) : 11.5_1 -> 11.5_2
* postgresql12-client (databases/postgresql12-client) : 12.r1 -> 12.0
* postgresql12-contrib (databases/postgresql12-contrib) : 12.r1 -> 12.0
* postgresql12-docs (databases/postgresql12-docs) : 12.r1 -> 12.0
* postgresql12-plperl (databases/postgresql12-plperl) : 12.r1 -> 12.0
* postgresql12-plpython (databases/postgresql12-plpython) : 12.r1 -> 12.0
* postgresql12-pltcl (databases/postgresql12-pltcl) : 12.r1 -> 12.0
* postgresql12-server (databases/postgresql12-server) : 12.r1 -> 12.0
* postgresql96-server (databases/postgresql96-server) : 9.6.15 -> 9.6.15_1
* ppsspp (emulators/ppsspp) : 1.9.2 -> 1.9.3
* ppsspp-qt5 (emulators/ppsspp-qt5) : 1.9.2 -> 1.9.3
* prestashop (finance/prestashop) : 1.7.6.1 -> 1.7.6.1_1
* proguard (java/proguard) : 6.1.1 -> 6.2.0
* prometheus (net-mgmt/prometheus2) : 2.12.0 -> 2.13.0
* protobuf-java (devel/protobuf-java) : 3.9.1 -> 3.10.0
* pt-freebsd-doc (misc/freebsd-doc-pt) : 53316 -> 53465
* puppet6 (sysutils/puppet6) : 6.9.0 -> 6.10.0
* puppetdb-terminus6 (databases/puppetdb-terminus6) : 6.6.0 -> 6.7.0
* puppetdb6 (databases/puppetdb6) : 6.6.0 -> 6.7.0
* puppetserver6 (sysutils/puppetserver6) : 6.6.0 -> 6.7.0
* py27-Flask (www/py-flask) : 1.0.2_1 -> 1.1.1
* py27-Lektor (www/py-lektor) : 3.1.3 -> 3.1.3_1
* py27-acme (security/py-acme) : 0.38.0 -> 0.39.0
* py27-ansible-runner (sysutils/py-ansible-runner) : 1.4.0 -> 1.4.1
* py27-asttokens (devel/py-asttokens) : 1.1.14 -> 1.1.15
* py27-azure-cli (sysutils/py-azure-cli) : 2.0.74 -> 2.0.74_1
* py27-botocore (devel/py-botocore) : 1.12.217 -> 1.12.245
* py27-certbot (security/py-certbot) : 0.38.0_1 -> 0.39.0
* py27-certbot-apache (security/py-certbot-apache) : 0.38.0 -> 0.39.0
* py27-certbot-dns-cloudflare (security/py-certbot-dns-cloudflare) : 0.38.0 -> 0.39.0
* py27-certbot-dns-cloudxns (security/py-certbot-dns-cloudxns) : 0.38.0 -> 0.39.0
* py27-certbot-dns-digitalocean (security/py-certbot-dns-digitalocean) : 0.38.0 -> 0.39.0
* py27-certbot-dns-dnsimple (security/py-certbot-dns-dnsimple) : 0.38.0 -> 0.39.0
* py27-certbot-dns-dnsmadeeasy (security/py-certbot-dns-dnsmadeeasy) : 0.38.0 -> 0.39.0
* py27-certbot-dns-gehirn (security/py-certbot-dns-gehirn) : 0.38.0 -> 0.39.0
* py27-certbot-dns-google (security/py-certbot-dns-google) : 0.38.0 -> 0.39.0
* py27-certbot-dns-linode (security/py-certbot-dns-linode) : 0.38.0 -> 0.39.0
* py27-certbot-dns-luadns (security/py-certbot-dns-luadns) : 0.38.0 -> 0.39.0
* py27-certbot-dns-nsone (security/py-certbot-dns-nsone) : 0.38.0 -> 0.39.0
* py27-certbot-dns-ovh (security/py-certbot-dns-ovh) : 0.38.0 -> 0.39.0
* py27-certbot-dns-rfc2136 (security/py-certbot-dns-rfc2136) : 0.38.0 -> 0.39.0
* py27-certbot-dns-route53 (security/py-certbot-dns-route53) : 0.38.0 -> 0.39.0
* py27-certbot-dns-sakuracloud (security/py-certbot-dns-sakuracloud) : 0.38.0 -> 0.39.0
* py27-certbot-nginx (security/py-certbot-nginx) : 0.38.0 -> 0.39.0
* py27-chainer (science/py-chainer) : 6.3.0 -> 6.4.0
* py27-chainer-chemistry (science/py-chainer-chemistry) : 0.5.0 -> 0.6.0
* py27-cheetah3 (devel/py-cheetah3) : 3.2.3 -> 3.2.4
* py27-cu2qu (x11-fonts/py-cu2qu) : 1.6.5 -> 1.6.5_2
* py27-dateparser (devel/py-dateparser) : 0.7.1 -> 0.7.2
* py27-defcon (x11-fonts/py-defcon) : 0.6.0 -> 0.6.0_2
* py27-django-cors-headers (www/py-django-cors-headers) : 3.1.0 -> 3.1.1
* py27-django-simple-captcha (www/py-django-simple-captcha) : 0.5.11 -> 0.5.12
* py27-dkimpy (mail/py-dkimpy) : 0.9.2 -> 0.9.4
* py27-elasticsearch (textproc/py-elasticsearch) : 7.0.4 -> 7.0.5
* py27-fastdtw (math/py-fastdtw) : 0.3.2_2 -> 0.3.4
* py27-flexget (www/py-flexget) : 2.21.22 -> 2.21.22_1
* py27-fontmake (x11-fonts/py-fontmake) : 1.8.0 -> 1.8.0_2
* py27-fonttools (print/py-fonttools) : 3.44.0_1 -> 3.44.0_2
* py27-game_sdl2 (devel/py-game_sdl2) : 7.3.2 -> 7.3.3
* py27-grpcio (devel/py-grpcio) : 1.24.0 -> 1.24.1
* py27-grpcio-tools (devel/py-grpcio-tools) : 1.24.0 -> 1.24.1
* py27-hcloud (sysutils/py-hcloud) : 1.6.0 -> 1.6.1
* py27-hypothesis (devel/py-hypothesis) : 4.37.0 -> 4.38.0
* py27-instabot (www/py-instabot) : 0.60.0 -> 0.61.0
* py27-mnemonic (security/py-mnemonic) : 0.18 -> 0.19
* py27-moviepy (multimedia/py-moviepy) : 1.0.0_1 -> 1.0.1
* py27-mypy-protobuf (devel/py-mypy-protobuf) : 1.15 -> 1.16
* py27-oci (devel/py-oci) : 2.5.1 -> 2.5.2
* py27-opencv (graphics/py-opencv) : 3.4.1_23 -> 3.4.1_24
* py27-path.py (devel/py-path.py) : 8.1.2 -> 11.5.2
* py27-pathspec (devel/py-pathspec) : 0.5.9 -> 0.6.0
* py27-pdftotext (textproc/py-pdftotext) : 2.1.1_8 -> 2.1.2
* py27-progressbar2 (misc/py-progressbar2) : 3.39.3 -> 3.47.0
* py27-psautohint (print/py-psautohint) : 1.9.1_1 -> 1.9.1_3
* py27-pyicu (devel/py-pyicu) : 2.3.1 -> 2.3.1_1
* py27-pyside2 (devel/pyside2) : 5.12.3 -> 5.13.1
* py27-pyside2-tools (devel/pyside2-tools) : 5.12.3 -> 5.13.1
* py27-python-djvulibre (graphics/py-djvulibre) : 0.8.4 -> 0.8.5
* py27-python-slugify (textproc/py-python-slugify) : 3.0.3 -> 3.0.4
* py27-rchitect (devel/py-rchitect) : 0.3.5 -> 0.3.10
* py27-ros-rosinstall_generator (devel/ros-rosinstall_generator) : 0.1.17 -> 0.1.18
* py27-schema (devel/py-schema) : 0.7.0 -> 0.7.1
* py27-shiboken2 (devel/shiboken2) : 5.12.3_1 -> 5.13.1
* py27-sounddevice (audio/py-sounddevice) : 0.3.13_1 -> 0.3.14
* py27-tqdm (misc/py-tqdm) : 4.35.0 -> 4.36.1
* py27-txtorcon (security/py-txtorcon) : 19.0.0 -> 19.1.0
* py27-ufo2ft (x11-fonts/py-ufo2ft) : 2.5.0 -> 2.5.0_2
* py27-unit (www/py-unit) : 1.11.0 -> 1.12.0
* py27-xdis (devel/py-xdis) : 4.0.3 -> 4.0.4
* py36-Flask (www/py-flask) : 1.0.2_1 -> 1.1.1
* py36-Lektor (www/py-lektor) : 3.1.3 -> 3.1.3_1
* py36-acme (security/py-acme) : 0.38.0 -> 0.39.0
* py36-aioredis (databases/py-aioredis) : 1.2.0 -> 1.3.0
* py36-ansible-runner (sysutils/py-ansible-runner) : 1.4.0 -> 1.4.1
* py36-asttokens (devel/py-asttokens) : 1.1.14 -> 1.1.15
* py36-azure-cli (sysutils/py-azure-cli) : 2.0.74 -> 2.0.74_1
* py36-botocore (devel/py-botocore) : 1.12.217 -> 1.12.245
* py36-certbot (security/py-certbot) : 0.38.0_1 -> 0.39.0
* py36-certbot-apache (security/py-certbot-apache) : 0.38.0 -> 0.39.0
* py36-certbot-dns-cloudflare (security/py-certbot-dns-cloudflare) : 0.38.0 -> 0.39.0
* py36-certbot-dns-cloudxns (security/py-certbot-dns-cloudxns) : 0.38.0 -> 0.39.0
* py36-certbot-dns-digitalocean (security/py-certbot-dns-digitalocean) : 0.38.0 -> 0.39.0
* py36-certbot-dns-dnsimple (security/py-certbot-dns-dnsimple) : 0.38.0 -> 0.39.0
* py36-certbot-dns-dnsmadeeasy (security/py-certbot-dns-dnsmadeeasy) : 0.38.0 -> 0.39.0
* py36-certbot-dns-gehirn (security/py-certbot-dns-gehirn) : 0.38.0 -> 0.39.0
* py36-certbot-dns-google (security/py-certbot-dns-google) : 0.38.0 -> 0.39.0
* py36-certbot-dns-linode (security/py-certbot-dns-linode) : 0.38.0 -> 0.39.0
* py36-certbot-dns-luadns (security/py-certbot-dns-luadns) : 0.38.0 -> 0.39.0
* py36-certbot-dns-nsone (security/py-certbot-dns-nsone) : 0.38.0 -> 0.39.0
* py36-certbot-dns-ovh (security/py-certbot-dns-ovh) : 0.38.0 -> 0.39.0
* py36-certbot-dns-rfc2136 (security/py-certbot-dns-rfc2136) : 0.38.0 -> 0.39.0
* py36-certbot-dns-route53 (security/py-certbot-dns-route53) : 0.38.0 -> 0.39.0
* py36-certbot-dns-sakuracloud (security/py-certbot-dns-sakuracloud) : 0.38.0 -> 0.39.0
* py36-certbot-nginx (security/py-certbot-nginx) : 0.38.0 -> 0.39.0
* py36-chainer (science/py-chainer) : 6.3.0 -> 6.4.0
* py36-chainer-chemistry (science/py-chainer-chemistry) : 0.5.0 -> 0.6.0
* py36-cheetah3 (devel/py-cheetah3) : 3.2.3 -> 3.2.4
* py36-ckcc-protocol (security/py-ckcc-protocol) : 0.7.9 -> 0.7.11
* py36-cu2qu (x11-fonts/py-cu2qu) : 1.6.5 -> 1.6.5_2
* py36-dateparser (devel/py-dateparser) : 0.7.1 -> 0.7.2
* py36-defcon (x11-fonts/py-defcon) : 0.6.0 -> 0.6.0_2
* py36-dj21-djangoql (www/py-dj21-djangoql) : 0.12.5 -> 0.13.0
* py36-django-cors-headers (www/py-django-cors-headers) : 3.1.0 -> 3.1.1
* py36-django-simple-captcha (www/py-django-simple-captcha) : 0.5.11 -> 0.5.12
* py36-dkimpy (mail/py-dkimpy) : 0.9.2 -> 0.9.4
* py36-elasticsearch (textproc/py-elasticsearch) : 7.0.4 -> 7.0.5
* py36-fastdtw (math/py-fastdtw) : 0.3.2_2 -> 0.3.4
* py36-flexget (www/py-flexget) : 2.21.22 -> 2.21.22_1
* py36-fontmake (x11-fonts/py-fontmake) : 1.8.0 -> 1.8.0_2
* py36-fonttools (print/py-fonttools) : 3.44.0_1 -> 3.44.0_2
* py36-game_sdl2 (devel/py-game_sdl2) : 7.3.2 -> 7.3.3
* py36-grpcio (devel/py-grpcio) : 1.24.0 -> 1.24.1
* py36-grpcio-tools (devel/py-grpcio-tools) : 1.24.0 -> 1.24.1
* py36-hcloud (sysutils/py-hcloud) : 1.6.0 -> 1.6.1
* py36-hypothesis (devel/py-hypothesis) : 4.37.0 -> 4.38.0
* py36-instabot (www/py-instabot) : 0.60.0 -> 0.61.0
* py36-matrix-synapse (net-im/py-matrix-synapse) : 1.2.1 -> 1.4.0
* py36-mnemonic (security/py-mnemonic) : 0.18 -> 0.19
* py36-moviepy (multimedia/py-moviepy) : 1.0.0_1 -> 1.0.1
* py36-mypy-protobuf (devel/py-mypy-protobuf) : 1.15 -> 1.16
* py36-oci (devel/py-oci) : 2.5.1 -> 2.5.2
* py36-path.py (devel/py-path.py) : 8.1.2 -> 11.5.2
* py36-pathspec (devel/py-pathspec) : 0.5.9 -> 0.6.0
* py36-pdftotext (textproc/py-pdftotext) : 2.1.1_8 -> 2.1.2
* py36-progressbar2 (misc/py-progressbar2) : 3.39.3 -> 3.47.0
* py36-psautohint (print/py-psautohint) : 1.9.1_1 -> 1.9.1_3
* py36-pyicu (devel/py-pyicu) : 2.3.1 -> 2.3.1_1
* py36-pyside2 (devel/pyside2) : 5.12.3 -> 5.13.1
* py36-pyside2-tools (devel/pyside2-tools) : 5.12.3 -> 5.13.1
* py36-python-djvulibre (graphics/py-djvulibre) : 0.8.4 -> 0.8.5
* py36-python-slugify (textproc/py-python-slugify) : 3.0.3 -> 3.0.4
* py36-rchitect (devel/py-rchitect) : 0.3.5 -> 0.3.10
* py36-ros-rosinstall_generator (devel/ros-rosinstall_generator) : 0.1.17 -> 0.1.18
* py36-rpy2 (math/py-rpy2) : 3.2.0 -> 3.2.0_1
* py36-schema (devel/py-schema) : 0.7.0 -> 0.7.1
* py36-shiboken2 (devel/shiboken2) : 5.12.3_1 -> 5.13.1
* py36-sounddevice (audio/py-sounddevice) : 0.3.13_1 -> 0.3.14
* py36-tqdm (misc/py-tqdm) : 4.35.0 -> 4.36.1
* py36-txtorcon (security/py-txtorcon) : 19.0.0 -> 19.1.0
* py36-ufo2ft (x11-fonts/py-ufo2ft) : 2.5.0 -> 2.5.0_2
* py36-unit (www/py-unit) : 1.11.0 -> 1.12.0
* py36-xdis (devel/py-xdis) : 4.0.3 -> 4.0.4
* qbittorrent (net-p2p/qbittorrent) : 4.1.7_1 -> 4.1.8
* qemu (emulators/qemu) : 3.1.1 -> 3.1.1.1
* qemu-utils (emulators/qemu-utils) : 3.1.1 -> 3.1.1.1
* qt5-core (devel/qt5-core) : 5.13.0 -> 5.13.0_1
* qt5-style-plugins (x11-themes/qt5-style-plugins) : 5.0.0.23_5 -> 5.0.0.23_6
* qt5-webengine (www/qt5-webengine) : 5.12.2_3 -> 5.12.2_4
* qt5-webkit (www/qt5-webkit) : 5.212.0.a3_2 -> 5.212.0.a3_4
* radian (devel/radian) : 0.4.0 -> 0.4.1
* radsecproxy (net/radsecproxy) : 1.8.0 -> 1.8.1
* raptor2 (textproc/raptor2) : 2.0.15_11 -> 2.0.15_12
* rav1e (multimedia/rav1e) : s20190928 -> s20191007
* renpy (games/renpy) : 7.3.2_1 -> 7.3.3
* rna-STAR (biology/star) : 2.7.0.f_1 -> 2.7.2.d
* robin-map (devel/robin-map) : 0.6.1 -> 0.6.2
* rpcs3 (emulators/rpcs3) : 0.0.7.8817 -> 0.0.7.8838
* rpm4 (archivers/rpm4) : 4.14.2.1_1 -> 4.15.0
* rspamd (mail/rspamd) : 1.9.4_2 -> 1.9.4_3
* rspamd-devel (mail/rspamd-devel) : 2.0.a1.20190719_1 -> 2.0.a1.20190719_2
* rsyslog (sysutils/rsyslog8) : 8.1908.0 -> 8.1910.0
* ru-freebsd-doc (misc/freebsd-doc-ru) : 53316 -> 53465
* ruby (lang/ruby26) : 2.6.4 -> 2.6.5
* ruby-build (devel/ruby-build) : 20190828 -> 20191004
* ruby24 (lang/ruby24) : 2.4.7 -> 2.4.9
* ruby25 (lang/ruby25) : 2.5.6 -> 2.5.7
* rubygem-aws-partitions (devel/rubygem-aws-partitions) : 1.219.0 -> 1.220.0
* rubygem-aws-sdk-core (devel/rubygem-aws-sdk-core) : 3.68.0 -> 3.68.1
* rubygem-aws-sdk-core2 (devel/rubygem-aws-sdk-core2) : 2.11.360 -> 2.11.361
* rubygem-aws-sdk-docdb (devel/rubygem-aws-sdk-docdb) : 1.10.0 -> 1.11.0
* rubygem-aws-sdk-dynamodb (devel/rubygem-aws-sdk-dynamodb) : 1.35.0 -> 1.36.0
* rubygem-aws-sdk-lightsail (devel/rubygem-aws-sdk-lightsail) : 1.24.0 -> 1.25.0
* rubygem-aws-sdk-resources2 (devel/rubygem-aws-sdk-resources2) : 2.11.360 -> 2.11.361
* rubygem-aws-sdk2 (devel/rubygem-aws-sdk2) : 2.11.360 -> 2.11.361
* rubygem-bolt (sysutils/rubygem-bolt) : 1.31.0 -> 1.32.0
* rubygem-charlock_holmes (textproc/rubygem-charlock_holmes) : 0.7.6_1 -> 0.7.6_2
* rubygem-ddtrace (devel/rubygem-ddtrace) : 0.27.0 -> 0.28.0
* rubygem-faraday (www/rubygem-faraday) : 0.15.4 -> 0.16.2
* rubygem-listen (devel/rubygem-listen) : 3.1.5_1 -> 3.2.0
* rubygem-oauth2 (net/rubygem-oauth2) : 1.4.1 -> 1.4.2
* rubygem-oj (devel/rubygem-oj) : 3.9.1 -> 3.9.2
* rubygem-parser (devel/rubygem-parser) : 2.6.4.1 -> 2.6.5.0
* rubygem-r10k (sysutils/rubygem-r10k) : 3.3.1 -> 3.3.2
* rubygem-rouge (textproc/rubygem-rouge) : 3.11.0 -> 3.11.1
* rubygem-selenium-webdriver (www/rubygem-selenium-webdriver) : 3.142.4_1 -> 3.142.5
* rubygem-xdg (devel/rubygem-xdg) : 3.0.2 -> 3.1.0
* runit-faster (sysutils/runit-faster) : 2.1.3.4 -> 2.1.3.4_1
* rust-nightly (lang/rust-nightly) : 1.40.0.20191001 -> 1.40.0.20191008
* samhain (security/samhain) : 4.3.2_1 -> 4.3.3
* samhain-client (security/samhain-client) : 4.3.2_1 -> 4.3.3
* samhain-server (security/samhain-server) : 4.3.2_1 -> 4.3.3
* scilab (math/scilab) : 5.5.2_21 -> 5.5.2_22
* scons (devel/scons) : 3.0.1 -> 3.1.1
* screen (sysutils/screen) : 4.6.2_3 -> 4.7.0_1
* screenFetch (sysutils/screenfetch) : 3.8.0.209 -> 3.9.0.2
* screenFetch-nox11 (sysutils/screenfetch-nox11) : 3.8.0.209 -> 3.9.0.2
* scribus-devel (print/scribus-devel) : 1.5.5_3 -> 1.5.5_4
* sendmail (mail/sendmail) : 8.15.2_18 -> 8.15.2_19
* sendmail-devel (mail/sendmail-devel) : 8.16.0.41 -> 8.16.0.41_1
* slop (x11/slop) : 7.4_5 -> 7.4_6
* smartmontools (sysutils/smartmontools) : 7.0_1 -> 7.0_2
* snakemake (misc/snakemake) : 5.6.0 -> 5.7.0
* solidity (lang/solidity) : 0.5.11 -> 0.5.12
* spidermonkey52 (lang/spidermonkey52) : 52.9.0_4 -> 52.9.0_5
* spotifyd (audio/spotifyd) : 0.2.17 -> 0.2.19
* sqlite3 (databases/sqlite3) : 3.29.0 -> 3.29.0_1
* src (os/src) : 12.1.20191003115222 -> 12.1.20191015211820
* subtitlecomposer (multimedia/subtitlecomposer) : 0.7.0_2 -> 0.7.0_3
* suricata5 (security/suricata5) : 5.0.0.b1_1 -> 5.0.0.r1
* svt-av1 (multimedia/svt-av1) : 0.7.0 -> 0.7.0.36
* swaks (mail/swaks) : 20170101.0 -> 20190914.0
* sway (x11-wm/sway) : 1.2_1 -> 1.2_3
* sword (misc/sword) : 1.8.1_7 -> 1.8.1_8
* sysctlinfo-kmod (sysutils/sysctlinfo-kmod) : 20190907 -> 20191005
* sysctlview (deskutils/sysctlview) : 1.5.1 -> 1.5.2
* tarantool (databases/tarantool) : 2.1.2_1 -> 2.1.2_2
* telegraf (net-mgmt/telegraf) : 1.12.1_1 -> 1.12.3
* telegram-desktop (net-im/telegram-desktop) : 1.8.4 -> 1.8.9
* tesseract (graphics/tesseract) : 4.1.0_2 -> 4.1.0_3
* tex-xetex (print/tex-xetex) : 0.99992_24 -> 0.99992_25
* texlive-base (print/texlive-base) : 20150521_41 -> 20150521_42
* thunderbird (mail/thunderbird) : 68.1.1_1 -> 68.1.1_2
* ticcutils (devel/ticcutils) : 0.20_7 -> 0.20_8
* tin (news/tin) : 2.4.2_5 -> 2.4.2_6
* tmv (math/tmv) : 0.75_5 -> 0.75_6
* tor-devel (security/tor-devel) : 0.4.2.1 -> 0.4.2.2
* tr-freebsd-doc (misc/freebsd-doc-tr) : 53316 -> 53465
* tracker (sysutils/tracker) : 2.0.4_4 -> 2.0.4_5
* tracker-miners (sysutils/tracker-miners) : 2.0.5_8 -> 2.0.5_9
* tvm (math/tvm) : 0.4.1440 -> 0.4.1614
* uTox (net-im/uTox) : 0.17.0_7 -> 0.17.1
* ucto (textproc/ucto) : 0.14.1_5 -> 0.14.1_6
* unar (archivers/unarchiver) : 1.10.1_13 -> 1.10.1_14
* unbound (dns/unbound) : 1.9.3 -> 1.9.4
* unit (www/unit) : 1.11.0 -> 1.12.0
* unit-perl5.30 (www/unit-perl) : 1.11.0 -> 1.12.0
* unit-php71 (www/unit-php) : 1.11.0 -> 1.12.0
* unit-php72 (www/unit-php) : 1.11.0 -> 1.12.0
* unit-php73 (www/unit-php) : 1.11.0 -> 1.12.0
* unit-php74 (www/unit-php) : 1.11.0 -> 1.12.0
* vagrant (sysutils/vagrant) : 2.2.5_1 -> 2.2.5_2
* varnish_exporter (www/varnish_exporter) : 1.4.1 -> 1.5.1
* visualboyadvance-m (emulators/visualboyadvance-m) : 2.0.0b2_9 -> 2.0.0b2_10
* vlc (multimedia/vlc) : 3.0.8_1 -> 3.0.8_3
* wayfire (x11-wm/wayfire) : 0.2_1 -> 0.3.0
* wazuh-agent (security/wazuh-agent) : 3.9.5 -> 3.10.2
* wcd (shells/wcd) : 6.0.2 -> 6.0.3
* webcamoid (multimedia/webcamoid) : 8.6.1_4 -> 8.7.0
* webkit2-gtk3 (www/webkit2-gtk3) : 2.24.4 -> 2.24.4_1
* wf-config (devel/wf-config) : 0.1.10_1 -> 0.3
* wf-shell (x11/wf-shell) : 0.1.13 -> 0.3
* widelands (games/widelands) : b20_2 -> b20_3
* wl-clipboard (x11/wl-clipboard) : 1.0.0.43 -> 2.0.0
* wlroots (x11-toolkits/wlroots) : 0.7.0 -> 0.8.1
* x265 (multimedia/x265) : 3.1.2_2 -> 3.2
* xanalyser (audio/xanalyser) : 1.32_2 -> 1.32_3
* xfce4-dict-plugin (textproc/xfce4-dict-plugin) : 0.8.2_1 -> 0.8.3
* xlockmore (x11/xlockmore) : 5.58_1 -> 5.59
* xml-security (security/xml-security) : 1.5.5 -> 1.5.5_1
* xpdf (graphics/xpdf) : 4.01_2 -> 4.02
* xpdf3 (graphics/xpdf3) : 3.04_10 -> 3.04_11
* xpdf4 (graphics/xpdf4) : 4.01_2 -> 4.02
* xpra (x11/xpra) : 2.5.1_3 -> 2.5.1_4
* xtrabackup (databases/xtrabackup) : 2.4.12_1 -> 2.4.15
* yabasic (lang/yabasic) : 2.84.1 -> 2.84.2
* yaz (net/yaz) : 5.27.1_2 -> 5.27.1_3
* youtube_dl (www/youtube_dl) : 2019.09.12.1 -> 2019.09.28
* zebra-server (net/zebra-server) : 2.0.55_11 -> 2.0.55_12
* zh-tin (chinese/tin) : 2.4.2_5 -> 2.4.2_6
* zh_cn-freebsd-doc (misc/freebsd-doc-zh_cn) : 53316 -> 53465
* zh_tw-freebsd-doc (misc/freebsd-doc-zh_tw) : 53316 -> 53465
* znc (irc/znc) : 1.7.5 -> 1.7.5_1
* znc-push (irc/znc-push) : 1.0.0.167_2 -> 1.0.0.167_3
* zorba (textproc/zorba) : 2.7.0_27 -> 2.7.0_28
