# GroceryHomeLaunchPanelGoodGroupModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Status status`

- `String unlockDesc`

- `String groupGoodNameDesc`

- `String startTimeDesc`

- `Int64 startTs`

- `String groupId`

- `String m_bindStageId`

- `String m_bindStageCode`


## Methods

- `Void LoadData(Act27SideGoodLaunchData, Dictionary`2)`

- `Void RefreshPlayeyData(PlayerAct27SideActivity, Int64, Int64)`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryHomeLaunchPanelGoodGroupModel : IHotfixable, IComparable
{
	private const String START_TIME_FORMAT; // 0x0
	public List`1 goodModelList; // 0x10
	public Status status; // 0x18
	public String unlockDesc; // 0x20
	public String groupGoodNameDesc; // 0x28
	public String startTimeDesc; // 0x30
	public Int64 startTs; // 0x38
	public String groupId; // 0x40
	private String m_bindStageId; // 0x48
	private String m_bindStageCode; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayeyData; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2864bcc VA: 0x7594e7cbcc
	public Void LoadData(Act27SideGoodLaunchData launchData, Dictionary`2 goodMap) { }
	// RVA: 0x2865054 VA: 0x7594e7d054
	public Void RefreshPlayeyData(PlayerAct27SideActivity playerData, Int64 curTs, Int64 endTs) { }
	// RVA: 0x2865670 VA: 0x7594e7d670
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2864b08 VA: 0x7594e7cb08
	public Void .ctor() { }
}
```