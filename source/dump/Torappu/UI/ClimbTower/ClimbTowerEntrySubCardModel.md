# ClimbTowerEntrySubCardModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String id`

- `String name`

- `String desc`

- `Boolean isUsed`

- `Int32 sortId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntrySubCardModel : IHotfixable
{
	public String id; // 0x10
	public String name; // 0x18
	public String desc; // 0x20
	public Boolean isUsed; // 0x28
	public Int32 sortId; // 0x2c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2cd6b60 VA: 0x75952eeb60
	public static ClimbTowerEntrySubCardModel LoadData(String subCardId) { }
	// RVA: 0x2cd6ec0 VA: 0x75952eeec0
	public Void .ctor() { }
}
```