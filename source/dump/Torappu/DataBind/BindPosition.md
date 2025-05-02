# BindPosition

**Namespace:** `Torappu.DataBind`


## Fields

- `Boolean isDynamic`

- `GameObject bindGameObject`

- `MonoBehaviour bindComponent`

- `String bindFieldName`

- `Int32 bindListIndex`

- `Boolean isBindList`


## Methods

- `Boolean IsEmpty()`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataBind
public class BindPosition
{
	public Boolean isDynamic; // 0x10
	public GameObject bindGameObject; // 0x18
	public MonoBehaviour bindComponent; // 0x20
	public String bindFieldName; // 0x28
	public Int32 bindListIndex; // 0x30
	private Boolean isBindList; // 0x34


	// RVA: 0x356dda4 VA: 0x7595b85da4
	public Boolean IsEmpty() { }
	// RVA: 0x356de64 VA: 0x7595b85e64
	public Void Clear() { }
	// RVA: 0x356dee0 VA: 0x7595b85ee0
	public override String ToString() { }
	// RVA: 0x356e1a4 VA: 0x7595b861a4
	public Void .ctor() { }
}
```