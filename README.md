# gentoo


These settings were set by the catalyst build script that automatically
built this stage.
Please consult /usr/share/portage/config/make.conf.example for a more
detailed example.

COMMON_FLAGS="-march=skylake -O2 -pipe"

CFLAGS="${COMMON_FLAGS}"

CXXFLAGS="${COMMON_FLAGS}"

FCFLAGS="${COMMON_FLAGS}"

FFLAGS="${COMMON_FLAGS}"

MAKEOPTS="-j8 -l8"
PORTAGE_NICENESS="1"
EMERGE_DEFAULT_OPTS="--jobs=8 --load-average=8 --with-bdeps y --complete-graph y"
FEATURES="candy fixlafiles unmerge-orphans sandbox parallel-install"
ACCEPT_KEYWORDS="~amd64"
ACCEPT_LICENSE="*"
INPUT_DEVICES="libinput keyboard mouse synaptics"
USE="-wayland -kde -GNOME -python_targets_python2_7 python_targets_python3_7 dbus pulseaudio X"
VIDEO_CARDS="intel i915 i965 iris"
LLVM_TARGETS="X86"

NOTE: This stage was built with the bindist Use flag enabled

PORTDIR="/var/db/repos/gentoo"
DISTDIR="/var/cache/distfiles"
PKGDIR="/var/cache/binpkgs"

This sets the language of build output to English.
Please keep this setting intact when reporting bugs.

LC_MESSAGES=C


Kernel modules: i915
Kernel modules: processor_thermal_device
Kernel modules: intel_pch_thermal
Kernel modules: xhci_pci
Kernel modules: iwlwifi
Kernel modules: mei_me
Kernel modules: ahci
Kernel modules: snd_hda_intel, snd_soc_skl, snd_sof_pci
Kernel modules: i2c_i801
Kernel modules: snd_hda_intel
Kernel modules: nvme
Kernel modules: r8169
Kernel modules: rtsx_pci
