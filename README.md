�g/**
 * Compress data into a block (no archive format)
 */
// Modules
var path = require('path')
var fs = require('fs')2 8lz4 P..')
V � Input/Output fia i �File = process.argv[2] || 'test'Y o; + 3+ J �+ lz4.extension
?  � = fs.readH RSync(     )� �Allocate max,�size, __to be sliced__ accordingly after cp u  #� � = new Buffer(� �ncodeBound(� �
.length) )

console.log('��ing %s to %s...',� ,h  � ��startTimU�Date.now(�z �is synchronous� anative0� !ed- 0SizN YC � � @�javascriptQ  J S�../lib/binL4').0 ]  P aTiming� Ydelta� & -� d

if (K � �> 0) {
	�  �� qfs.stat�Ox.size
	�@
		'�Hb � %d bytesi � %dms (%dMb/s)'
	,	y   C j  � 	 � > 0 ? Math.r8a 100 *K� A/ ( 4 � * (1 << 20) ) *) P0 ) /	 � : 0
	)
	4# ==.�5(0,�� �)
} else7'X�could not� 'e R�
}

fs.write^l�   �, output )
