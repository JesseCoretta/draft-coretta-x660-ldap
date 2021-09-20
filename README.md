# draft-coretta-x660-ldap

Schema files and LDIF examples pertaining to [`draft-coretta-x660-ldap`](https://datatracker.ietf.org/doc/draft-coretta-x660-ldap/), of which I am the author.

This draft describes a means for storing any OID in existence, along with OID registration details, within an LDAP directory information tree. It can tolerate the storage of (virtually) the entire OID spectrum, or merely a subset of OIDs. This specification offers two logical models: 2D and 3D.

Current document version is `07`.

__!! THIS IS A WORK IN PROGRESS !!__

# What is in this repo?

  * Two logically-identical schema files are provided; one is formatted for use by 389DS (Netscape Directory), while the other is formatted for use by OpenLDAP.
  * A variety of LDIF files are made available to individuals attempting to test this specification.

# Why does this repo exist?

  * Allow for peer review discussions in the form of Issues
  * Track and organize pending changes via Issues
  * Provide helpful information and media outside of the scope of a typical internet draft

# What has changed since last update?

  * Positional attribute types
  * Security considerations
  * Allow client auto-configuration through DUA parameter advertisement
