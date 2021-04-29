# Apple pay verification extension based on yansongda/pay package

### Installation package
```bash
composer require luoyy/pay-ext
```

### Quick Sample Usage
```php
/**
 * DEMO
 */
use Yansongda\Pay\Pay;

if (!empty($verify = Pay::apple((new Applepay)->config('apple'))->verify($this->receipt_data))) {

}
// more.....
```
### Update log
* `2021.04.29`：Initialize the warehouse
