# RequestAssistChar

**Namespace:** `Torappu`


## Fields

- `Int32 charInstId`

- `Int32 S_skillIndex`

- `String S_currentEquip`

- `String S_currentTmpl`


## Methods

- `Boolean ShouldSerializeS_currentTmpl()`

- `Boolean ShouldSerializeS_skillIndex()`

- `Boolean ShouldSerializeS_currentEquip()`

- `Boolean ShouldSerializeS_tmpl()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RequestAssistChar : IJsonSerializeHandler
{
	public Int32 charInstId; // 0x10
	public Int32 S_skillIndex; // 0x14
	public String S_currentEquip; // 0x18
	public String S_currentTmpl; // 0x20
	public ListDict`2 S_tmpl; // 0x28


	// RVA: 0x352cbd4 VA: 0x7595b44bd4
	public Boolean ShouldSerializeS_currentTmpl() { }
	// RVA: 0x352cbe4 VA: 0x7595b44be4
	public Boolean ShouldSerializeS_skillIndex() { }
	// RVA: 0x352cbf4 VA: 0x7595b44bf4
	public Boolean ShouldSerializeS_currentEquip() { }
	// RVA: 0x352cc04 VA: 0x7595b44c04
	public Boolean ShouldSerializeS_tmpl() { }
	// RVA: 0x352cc14 VA: 0x7595b44c14
	public Void .ctor() { }
}
```