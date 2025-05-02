# CharacterLvlupItemCardViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `UIItemViewModel itemViewModel`

- `Mode mode`

- `Boolean needDescOnly`


## Properties

- `Int32 gainExp`


## Methods

- `Int32 get_gainExp()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupItemCardViewModel : IHotfixable
{
	public UIItemViewModel itemViewModel; // 0x10
	public Mode mode; // 0x18
	public Boolean needDescOnly; // 0x1c
	private static DelegateBridge __Hotfix0_get_gainExp; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Int32 gainExp { get; }

	// RVA: 0x2d5f4cc VA: 0x75953774cc
	public Int32 get_gainExp() { }
	// RVA: 0x2d5f35c VA: 0x759537735c
	public Void .ctor() { }
}
```