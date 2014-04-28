jQuery-Pinyin
=============

The jQuery plugin used to transform Pinyin with Chinese character

Installation
-------
    <script type="text/javascript" charset="utf-8" src="jquery.js"></script>
    <script type="text/javascript" charset="utf-8" src="jquery.pinyin.js"></script>

Usage
-----

    var pinyin = $.Pinyin({short:false, value:"你好吗"});
    result for it: NiHaoMa

    var pinyin = $.Pinyin({short:true, value:"你好吗"});
    result for it: NHM
