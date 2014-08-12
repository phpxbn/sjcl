```javascript

<?php

namespace Video\Model;

class World {
	
	public $mystr;
	
	public function getMystr(){
	
	}
	
	public function setMystr($mystr) {
		$this->mystr = $mystr;
	}

	public function __construct($str){
		$this->mystr=$str;
	}
	
	public function hello() {
		echo 'Hello world!';
	}
		
	
}

?>

```
