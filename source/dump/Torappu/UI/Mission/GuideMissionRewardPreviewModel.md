# GuideMissionRewardPreviewModel

**Namespace:** `Torappu.UI.Mission`


## Methods

- `Void LoadData()`

- `String GetToDoGroupId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class GuideMissionRewardPreviewModel : IHotfixable
{
	private List`1 m_groupList; // 0x10
	private static DelegateBridge __Hotfix0_get_groupList; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_GetToDoGroupId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public List`1 groupList { get; }

	// RVA: 0x2732edc VA: 0x7594d4aedc
	public List`1 get_groupList() { }
	// RVA: 0x273368c VA: 0x7594d4b68c
	public Void LoadData() { }
	// RVA: 0x27331f0 VA: 0x7594d4b1f0
	public String GetToDoGroupId() { }
	// RVA: 0x2733e74 VA: 0x7594d4be74
	public Void .ctor() { }
}
```