# StringTranslate
 Example 2 from the PHP manual, will show 'hello all, I said hi'. Local $aTrans[3][2] = [['h', '-'], ['hello', 'hi'], ['hi', 'hello']] MsgBox(0, '_StringTranslate with 2 arguments', _StringTranslate('hi all, I said hello.', $aTrans))  ; Example 3 from the PHP manual, will show '1001 ba01' Local $sDiff = _StringTranslate('baab', 'ab', '01') &amp; @CRLF Local $aTrans2[1][2] = [['ab', '01']] $sDiff &amp;= _StringTranslate('baab', $aTrans2) MsgBox(0, '_StringTranslate behavior comparison', $sDiff)  #cs
