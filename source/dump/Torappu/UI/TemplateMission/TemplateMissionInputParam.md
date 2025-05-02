# TemplateMissionInputParam

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `String displayId`

- `TemplateMissionLayoutType layoutType`

- `TemplateMissionDisplaySource source`

- `TemplateMissionCoinViewModel coinViewModel`

- `ITemplateMissionViewModelPlugin plugin`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionInputParam : IHotfixable
{
	public String displayId; // 0x10
	public List`1 missionGroupList; // 0x18
	public TemplateMissionLayoutType layoutType; // 0x20
	public TemplateMissionDisplaySource source; // 0x24
	public TemplateMissionCoinViewModel coinViewModel; // 0x28
	public ITemplateMissionViewModelPlugin plugin; // 0x30
	public Dictionary`2 missionDataBundleDict; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x236d148 VA: 0x7594985148
	public Void .ctor() { }
}
```