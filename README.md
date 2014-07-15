HybridAuth-Kakao
=====
A HybridAuth Provider for Kakao Service

Usage
-----

1. Drop Kakao.php to HybridAuth provider directory.
2. Set config.php as follows:

<code>
    "providers" => array ( 
      "Kakao" => array (
        "enabled" => true,
        "keys"    => array ( "id" => "YOUR-KAKAO-APP-KEY", "secret" => "^_^" ),
      ),
</code>

Links
-----
* [HybridAuth](http://hybridauth.sourceforge.net/)
* [Kakao Developers](https://developers.kakao.com/)
* [Kakao Buttons](https://developers.kakao.com/buttons)

License
-----

MIT.