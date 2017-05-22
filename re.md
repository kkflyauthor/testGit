	//var_dump($a);
	function GetLisRequest($p_keyValue,$p_customerBarcode) {
		if(verifyCode($p_keyValue)){
			$opt = runPerHour($p_keyValue);
			if(is_string($opt)){