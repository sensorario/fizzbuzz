fizzbuzz
========

  function fizzBuzz($n) {
      $s='';
      foreach([3=>'Fi',5=>'Ma',7=>'Bu']as$k=>$v)
        if($n%$k==0)
          $s.=$v.'zz';
      return $s==''?$n:$s;
  }
