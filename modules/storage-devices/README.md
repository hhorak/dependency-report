# storage-devices
This is a dependency report for the storage-devices module.

An initial [modulemd file](storage-devices.yaml) has been generated. It is experimental and probably unusable at this point.
## Dependencies
These are modules identified as dependencies.
### Runtime
This list might not be complete. There might be other packages in the *Binary RPM packages (all arches combined)* section that needs to be split to different modules.
* [platform](../platform)
* [platform-placeholder](../platform-placeholder)
### Build
This list might not be complete.
Please see the **missing RPM build dependencies ([source](all/buildtime-source-packages-short.txt) or [binary](all/buildtime-binary-packages-short.txt)) lists** for more information.
* [bootstrap](../bootstrap)
## Binary RPM packages
These are RPM dependencies of the [storage-devices top-level package set](storage-devices.csv). They should be either:
* split into other modules and be used as modular dependencies
* included in this storage-devices module
### Packages
| |aarch64 |armv7hl |i686 |ppc64 |ppc64le |s390x |x86_64 |
|---|---|---|---|---|---|---|---|
| `at` | X | X | X | X | X | X | X |
| `avahi-libs` | X | X | X | X | X | X | X |
| `boost-iostreams` | X | X | X | X | X | X | - |
| `boost-program-options` | X | X | X | X | X | X | X |
| `boost-random` | X | X | X | X | X | X | - |
| `boost-regex` | X | X | X | X | X | X | X |
| `boost-system` | X | X | X | X | X | X | - |
| `boost-thread` | X | X | X | X | X | X | - |
| `ceph` | X | X | X | X | X | X | X |
| `ceph-base` | X | X | X | X | X | X | X |
| `ceph-common` | X | X | X | X | X | X | X |
| `ceph-mds` | X | X | X | X | X | X | X |
| `ceph-mon` | X | X | X | X | X | X | X |
| `ceph-osd` | X | X | X | X | X | X | X |
| `ceph-selinux` | X | X | X | X | X | X | X |
| `cronie` | X | X | X | X | X | X | X |
| `cronie-noanacron` | X | X | X | X | X | X | X |
| `crontabs` | X | X | X | X | X | X | X |
| `cryptsetup` | X | X | X | X | X | X | X |
| `cups-client` | X | X | X | X | X | X | X |
| `cups-libs` | X | X | X | X | X | X | X |
| `curl-minimal` | X | X | X | X | X | X | X |
| `cyrus-sasl` | X | X | X | X | X | X | X |
| `ed` | X | X | X | X | X | X | X |
| `fcgi` | X | X | X | X | X | X | X |
| `gettext` | - | X | - | - | - | X | - |
| `gettext-libs` | - | X | - | - | - | X | - |
| `gperftools-libs` | X | X | X | X | X | - | X |
| `groff-base` | X | X | X | X | X | - | X |
| `hdparm` | X | X | X | X | X | X | X |
| `hesiod` | X | X | X | X | X | X | X |
| `leveldb` | X | X | X | X | X | X | X |
| `libcephfs1` | X | X | X | X | X | X | X |
| `libcroco` | - | X | - | - | - | X | - |
| `libpipeline` | X | X | X | X | X | X | X |
| `librados2` | X | X | X | X | X | X | - |
| `libradosstriper1` | X | X | X | X | X | X | X |
| `librbd1` | X | X | X | X | X | X | X |
| `librgw2` | X | X | X | X | X | X | X |
| `libunwind` | X | X | X | - | - | - | X |
| `lttng-ust` | X | X | X | X | X | X | - |
| `mailx` | X | X | X | X | X | X | X |
| `man-db` | X | X | X | X | X | X | X |
| `ncurses-compat-libs` | X | X | X | X | X | X | X |
| `procmail` | X | X | X | X | X | X | X |
| `python2-asn1crypto` | X | X | X | X | X | X | X |
| `python2-babel` | X | X | X | X | X | X | X |
| `python2-cffi` | X | X | X | X | X | X | X |
| `python2-click` | X | X | X | X | X | X | X |
| `python2-cryptography` | X | X | X | X | X | X | X |
| `python2-flask` | X | X | X | X | X | X | X |
| `python2-idna` | X | X | X | X | X | X | X |
| `python2-itsdangerous` | X | X | X | X | X | X | X |
| `python2-jinja2` | X | X | X | X | X | X | X |
| `python2-markupsafe` | X | X | X | X | X | X | X |
| `python2-ply` | X | X | X | X | X | X | X |
| `python2-pycparser` | X | X | X | X | X | X | X |
| `python2-pyOpenSSL` | X | X | X | X | X | X | X |
| `python2-pysocks` | X | X | X | X | X | X | X |
| `python2-requests` | X | X | X | X | X | X | X |
| `python2-six` | X | X | X | X | X | X | X |
| `python2-urllib3` | X | X | X | X | X | X | X |
| `python-backports` | X | X | X | X | X | X | X |
| `python-backports-ssl_match_hostname` | X | X | X | X | X | X | X |
| `python-cephfs` | X | X | X | X | X | X | X |
| `python-chardet` | X | X | X | X | X | X | X |
| `python-enum34` | X | X | X | X | X | X | X |
| `python-ipaddress` | X | X | X | X | X | X | X |
| `python-rados` | X | X | X | X | X | X | X |
| `python-rbd` | X | X | X | X | X | X | X |
| `python-werkzeug` | X | X | X | X | X | X | X |
| `pytz` | X | X | X | X | X | X | X |
| `redhat-lsb-core` | X | X | X | X | X | X | X |
| `redhat-lsb-submod-security` | X | X | X | X | X | X | X |
| `sendmail` | X | X | X | X | X | X | X |
| `spax` | X | X | X | X | X | X | X |
| `util-linux-user` | X | X | X | X | X | X | X |
| `which` | - | X | - | - | - | X | - |
