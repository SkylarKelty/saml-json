JSON mod for SAML
=============

SAML Module for authing against a JSON list of users
Note: Probably shouldnt exactly be considered the most secure SAML mod ever.


Example Config:
```
	'json' => array(
		'json:auth',
		'mappings' => '/saml/config/userlist.json',
		'encryption' => 'md5' // plain, md5, sha1
	),
```
