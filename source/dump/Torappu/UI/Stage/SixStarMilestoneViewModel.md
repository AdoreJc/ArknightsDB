# SixStarMilestoneViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String groupId`

- `Int32 currPoint`

- `Boolean canClaimAll`


## Methods

- `Void LoadData(String)`

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarMilestoneViewModel : IHotfixable
{
	public String groupId; // 0x10
	public Int32 currPoint; // 0x18
	public List`1 itemList; // 0x20
	public Boolean canClaimAll; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2f49fe4 VA: 0x7595561fe4
	public Void LoadData(String groupId) { }
	// RVA: 0x2f4a8c4 VA: 0x75955628c4
	public Void RefreshPlayerData() { }
	// RVA: 0x2f4b488 VA: 0x7595563488
	public Void .ctor() { }
}
```