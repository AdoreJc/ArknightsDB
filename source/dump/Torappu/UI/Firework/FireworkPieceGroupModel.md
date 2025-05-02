# FireworkPieceGroupModel

**Namespace:** `Torappu.UI.Firework`


## Fields

- `String platePieceId`

- `Int32 platePieceSortId`

- `Int32 platePieceCount`

- `FireworkDirectionType directionType`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPieceGroupModel : IHotfixable
{
	public String platePieceId; // 0x10
	public Int32 platePieceSortId; // 0x18
	public Int32 platePieceCount; // 0x1c
	public List`1 plateSlotDataList; // 0x20
	public FireworkDirectionType directionType; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x28ed708 VA: 0x7594f05708
	public Void LoadData() { }
	// RVA: 0x28ed868 VA: 0x7594f05868
	public Void .ctor() { }
}
```