# HandBookTeamEditor

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `String powerId`

- `leftrightType m_iconType`

- `HandBookTeamView teamView`

- `Transform teamDestination`

- `Transform teamImage`


## Properties

- `Int32 iconType`


## Methods

- `Int32 get_iconType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookTeamEditor : MonoBehaviour
{
	public String powerId; // 0x18
	private leftrightType m_iconType; // 0x20
	public HandBookTeamView teamView; // 0x28
	public Transform teamDestination; // 0x30
	public Transform teamImage; // 0x38

	public Int32 iconType { get; }

	// RVA: 0x2eb6788 VA: 0x75954ce788
	public Int32 get_iconType() { }
	// RVA: 0x2eb6790 VA: 0x75954ce790
	public Void .ctor() { }
}
```