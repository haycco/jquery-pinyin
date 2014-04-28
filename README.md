jQuery-Pinyin
=============

The jQuery plugin used to transfer for Pinyin with Chinese character

Installation
-------
    <script type="text/javascript" charset="utf-8" src="jquery.js"></script>
    <script type="text/javascript" charset="utf-8" src="jquery.pinyin.min.js"></script>

Usage
-----

    var pinyin = $.Pinyin({short:false, value:"�����"});
    result for it: NiHaoMa

    var pinyin = $.Pinyin({short:true, value:"�����"});
    result for it: NHM
