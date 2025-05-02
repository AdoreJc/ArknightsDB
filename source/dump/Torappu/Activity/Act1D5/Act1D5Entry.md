# Act1D5Entry

**Namespace:** `Torappu.Activity.Act1D5`


## Fields

- `Transform _itemContainer`

- `Text _openTime`

- `ScrollRect _scrollRect`

- `Text _apItemTime`


## Methods

- `IEnumerator _refreshVertial(DefaultCheckInData)`

- `Void _ApplyTimeInfo(Int64, Int64)`

- `Void <>xLuaBaseProxy_OnEnter(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1D5
public class Act1D5Entry : ActivityCommonCheckinEntry, IHotfixable
{
	private List`1 _checkinItemList; // 0x68
	private Transform _itemContainer; // 0x70
	private Text _openTime; // 0x78
	private ScrollRect _scrollRect; // 0x80
	private Text _apItemTime; // 0x88
	private List`1 m_itemList; // 0x90
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__refreshVertial; // 0x8
	private static DelegateBridge __Hotfix0__ApplyTimeInfo; // 0x10
	private static DelegateBridge __Hotfix0_RefreshInfo; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x33e1f54 VA: 0x75959f9f54
	public override Void OnEnter(String activityId) { }
	// RVA: 0x33e2b9c VA: 0x75959fab9c
	private IEnumerator _refreshVertial(DefaultCheckInData data) { }
	// RVA: 0x33e283c VA: 0x75959fa83c
	private Void _ApplyTimeInfo(Int64 startTime, Int64 endTime) { }
	// RVA: 0x33e2c94 VA: 0x75959fac94
	protected override Void RefreshInfo() { }
	// RVA: 0x33e306c VA: 0x75959fb06c
	public Void .ctor() { }
	// RVA: 0x33e3130 VA: 0x75959fb130
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
}
```