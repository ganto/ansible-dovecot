Changelog
=========

v0.2.0
------

*Unreleased*

- Replace ``dovecot_allow_<protocol>`` by ``dovecot_protocol_map`` which
  also offers to set custom ports for the individual protocols. [ganto]

- Add new variable ``dovecot_mail_plugins`` to separate protocol and plugin
  configuration. If you use Dovecot as LDA and want sieve filtering, you
  now have to add ``lda: [ 'sieve' ]`` to the plugin dict. [ganto]

v0.1.0
------

*Released: 2015-04-01*

- First release [ganto, drybjed]

