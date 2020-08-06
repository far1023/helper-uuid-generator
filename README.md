# helper-uuid-generator
Codeigniter 3 helper for generating uuid

# How to
Simple first put `uuid_helper.php` file to application\helpers. You can easily add this helper to your autoload :
```
// application\config\autoload.php
$autoload['helper'] = array('uuid');
```
or by loading helper :
```
$this->load->helper('uuid');
```
execution :
```
$uuid = uuid_gen(); // string(36)

```
