# StarWorldCoreLib3
>A simple data processing module<br>
>Version: 1.9.2

Example Code
```python
import StarWorldCoreLib as sw
rstr = sw.rstring("HelloWorld")
print(sw.string(rstr.reverse()))
#Output "dlroWolleH"
print(sw.string(rstr.upset()))
#Output "HelloWorld" scrambled text
#As edWrolHlol
```

StarWorldCoreLib.rstring's introduce
> Usage：rstring("Some Texts") -> rstring<br>
> Action：<br>
>>reverse() -> rstring: used to reverse the rstring content<br>
>>upset() -> rstring: used to disrupt rstring content<br>
>>replace(rstring("Text to replace"),rstring("Replaced text")) -> rstring: used to replace the contents of rstring<br>
>>split(rstring("Split text")) -> list: used to divide rstring text into lists according to parameters<br>

StarWorldCoreLib.rclipboard's introduce
> Usage：rclipboard() -> rclipboard<br>
> Action：<br>
>> read() -> rstring: Read rstring type of pasteboard
>> write(rstring("Content written to the pasteboard")) -> rstring: write content to pasteboard


StarWorldCoreLib.string's introduce
> Usage：string(rstring("An rstring content")) -> str<br>
> introduce：Convert rstring content to string content

Please study more by yourself.
