Bir C programının program structure'ını gördük, bu nedenle C programlama dilinin diğer temel syntax'ını anlamak kolay olacaktır.

# C dilindeki Tokenler
Bir C programı çeşitli token'lerden oluşur ve 

Bir C programı çeşitli tokenlerden oluşur ve bir belirteç ya bir keyword(anahtar sözcük), bir identifier(tanımlayıcı), bir constant(sabit), 
bir  string literal (dize değişmezi) veya bir symbol(semboldür). Örneğin, aşağıdaki C ifadesi beş belirteçten oluşur.

```
printf("Hello, World! \n");
```

```
printf
(
   "Hello, World! \n"
)
;
```

## 1- Semicolons 
Bir C programında noktalı virgül ifade sonlandırıcıdır.Her ifade bir noktalı virgül ile tamamlanmalıdır.Mantıksal varlığın sonunu ifade eder.
```
printf("Hello, World! \n");
return 0;
```

## 2- Comments 
Yorumlar, C programında kodları açıklayıcı cümlelerden ve notlardan oluşur.Compiler tarafından okunmaz. 
```
/* This is a helloworld.c program */
```

## 3- Identifier
Bir C programında identifier, bir variable(değişkeni), fonksiyonu veya kullanıcı tamınlı ifadeyi tanımlamak için kullanılan addır. 
A'dan Z'ye, a'dan z'ye bir harfle veya bir alt çizgi '_' ile başlar ve ardından sıfır veya daha fazla harf, alt çizgi ve rakam (0 - 9) gelir.
```
MmC    _A   a_   a   b   meyve   Node
CS     PC   lessons  _function_a a_b_c_123
```

## 4- Keywords
Aşağıdaki liste, C'deki ayrılmış sözcükleri göstermektedir. Bu ayrılmış sözcükler, sabitler veya değişkenler veya başka herhangi bir tanımlayıcı ad olarak kullanılamaz.
<table style="text-align:center;" class="table table-bordered">
<tr>
<td style="width:25%">auto</td>
<td style="width:25%">else</td>
<td style="width:25%">long</td>
<td style="width:25%">switch</td>
</tr>
<tr>
<td>break</td>
<td>enum</td>
<td>register</td>
<td>typedef</td>
</tr>
<tr>
<td>case</td>
<td>extern</td>
<td>return</td>
<td>union</td>
</tr>
<tr>
<td>char</td>
<td>float</td>
<td>short</td>
<td>unsigned</td>
</tr>
<tr>
<td>const</td>
<td>for</td>
<td>signed</td>
<td>void</td>
</tr>
<tr>
<td>continue</td>
<td>goto</td>
<td>sizeof</td>
<td>volatile</td>
</tr>
<tr>
<td>default</td>
<td>if</td>
<td>static</td>
<td>while</td>
</tr>
<tr>
<td>do</td>
<td>int</td>
<td>struct</td>
<td>_Packed</td>
</tr>
<tr>
<td>double</td>
<td></td>
<td></td>
<td></td>
</tr>
</table>













