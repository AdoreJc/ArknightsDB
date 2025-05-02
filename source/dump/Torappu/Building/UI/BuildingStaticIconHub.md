# BuildingStaticIconHub

**Namespace:** `Torappu.Building.UI`


## Fields

- `Sprite _iconWorkshop`

- `Sprite _iconManufact`

- `Sprite _iconGold`


## Methods

- `Sprite GetIcon(IconType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingStaticIconHub : MonoBehaviour, IHotfixable
{
	private Sprite _iconWorkshop; // 0x18
	private Sprite _iconManufact; // 0x20
	private Sprite _iconGold; // 0x28
	private static DelegateBridge __Hotfix0_GetIcon; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3d43c3c VA: 0x759635bc3c
	public Sprite GetIcon(IconType type) { }
	// RVA: 0x3d43ce8 VA: 0x759635bce8
	public Void .ctor() { }
}
```