
## Information

Define array

```bash
 $arrayValues=array("B\$u\$i\$ld", "\$t\$\$h\$e", "N\$e\$x\$t", "E\$\$ra", "\$\$o\$f\$", "S\$\$of\$t\$wa\$r\$e", "De\$\$ve\$l\$op\$me\$n\$t");  
```

Trim Array value Replace $ and \  

```bash
  $trimmedArray = str_replace(array('$','\"'), '', $arrayValues);
```

//	Convert Array to Upercase and then change it to string. 

```bash
  $convertedArray=implode(" ",array_map('strtoupper', $trimmedArray));
```

Print $convertedArray to see output 

```bash
  print_r($convertedArray);

//	Output
//	BUILD THE NEXT ERA OF SOFTWARE DEVELOPMENT
```

