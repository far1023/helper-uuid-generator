# helper-uuid-generator
Codeigniter 3 helper for generating uuid

# How to
You can easily add this helper to your autoload :
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
