Codeblock:

	function rtrim(str, ch)
	{
	    for (i = str.length - 1; i >= 0; i--)
	    { // One newline after

	        if (ch != str.charAt(i))
	        { // Two newlines after


	            str = str.substring(0, i + 1);
	            break;
	        }
	        // Three newlines after



	        // And two lines with some spaces inside
	        
	    
	    }
	    return str;
	}