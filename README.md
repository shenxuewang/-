# -
  var patt1=new RegExp(/^1\d{9}2$/);
		document.write(patt1.test("18812011232")); 
		document.write('<br>');
		var patt2=new RegExp(/\b([a-zA-Z]+)\b\s+\1\b/);
		document.write(patt2.test("foo foo bar"));
