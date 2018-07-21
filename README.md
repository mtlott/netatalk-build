# RPM Builder for NetAtalk on Fedora 28 using Vagrant

Following the direction found at [Sourceforge Home Page](http://netatalk.sourceforge.net/wiki/index.php/Netatalk_3.1.11_SRPM_for_Fedora_and_CentOS).

# Building

The RPMs may be built with [Vagrant](#with-vagrant)

Whatever way you choose you will need to do a few basic things first.

```bash
git clone https://github.com/mtlott/netatalk-build      ## check out this code
cd netatalk-build                                       ## uhh... you should know
```

## With Vagrant

```bash
vagrant up                         ## provision and build the RPMs
```

## Result

Two RPMs will be copied to the `artifacts` folder:
1. `netatalk-3.1.11-1.3.fc29.src.rpm`      - The source spec rpm downloaded to do the build
2. `netatalk-3.1.11-1.3.fc28.x86_64.rpm`   - The resultant netatalk rpm for installation on the target system

# Running

1. Install the RPM(s) that you need
2. Follow the directions on the Netatlk Homepage to configure

# Further reading

See the [Netatalk Sourceforge](http://netatalk.sourceforge.net/wiki/index.php/Netatalk_3.1.11_SRPM_for_Fedora_and_CentOS). website.
