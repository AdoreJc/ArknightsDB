# HandBookJumpParam

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Boolean isHandBookPage`

- `Boolean isJump`

- `String charId`

- `Boolean <isBattle>k__BackingField`

- `Boolean <isAVG>k__BackingField`


## Properties

- `Boolean isBattle`

- `Boolean isAVG`


## Methods

- `Boolean get_isBattle()`

- `Void set_isBattle(Boolean)`

- `Boolean get_isAVG()`

- `Void set_isAVG(Boolean)`

- `Boolean IsFromHandbook()`

- `Boolean IsEmpty()`

- `Int32 GetCharInstId()`

- `Void SetParamBundle(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookJumpParam : ICharInfoHomeInitParam
{
	public Boolean isHandBookPage; // 0x10
	public Boolean isJump; // 0x11
	public String charId; // 0x18
	public List`1 charList; // 0x20
	private Boolean <isBattle>k__BackingField; // 0x28
	private Boolean <isAVG>k__BackingField; // 0x29

	public Boolean isBattle { get; set; }
	public Boolean isAVG { get; set; }

	// RVA: 0x2e9b170 VA: 0x75954b3170
	public Boolean get_isBattle() { }
	// RVA: 0x2e9b178 VA: 0x75954b3178
	private Void set_isBattle(Boolean value) { }
	// RVA: 0x2e9b184 VA: 0x75954b3184
	public Boolean get_isAVG() { }
	// RVA: 0x2e9b18c VA: 0x75954b318c
	private Void set_isAVG(Boolean value) { }
	// RVA: 0x2e9b198 VA: 0x75954b3198
	public Boolean IsFromHandbook() { }
	// RVA: 0x2e9b1a0 VA: 0x75954b31a0
	public Boolean IsEmpty() { }
	// RVA: 0x2e9b1b8 VA: 0x75954b31b8
	public Int32 GetCharInstId() { }
	// RVA: 0x2e9b224 VA: 0x75954b3224
	public List`1 GetCharList() { }
	// RVA: 0x2e99af8 VA: 0x75954b1af8
	public Void SetParamBundle(DataBundle bundle) { }
	// RVA: 0x2e99af0 VA: 0x75954b1af0
	public Void .ctor() { }
}
```