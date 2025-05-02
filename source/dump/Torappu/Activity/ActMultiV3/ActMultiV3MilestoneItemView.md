# ActMultiV3MilestoneItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _availStatusGO`

- `GameObject _notAvailStatusGO`

- `GameObject _lockedStatusGO`

- `GameObject _objMaskFinished`

- `Text _lockedTimeRemainText`

- `GameObject _rewardContainer`

- `UIStateFinder m_finder`


## Methods

- `Void EventOnClick()`

- `Void <>xLuaBaseProxy_OnRender()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MilestoneItemView : TemplateActivityCommonMileStoneItemView
{
	private GameObject _availStatusGO; // 0x78
	private GameObject _notAvailStatusGO; // 0x80
	private GameObject _lockedStatusGO; // 0x88
	private Text[] _textLevelNumList; // 0x90
	private GameObject _objMaskFinished; // 0x98
	private Text _lockedTimeRemainText; // 0xa0
	private GameObject _rewardContainer; // 0xa8
	private UIStateFinder m_finder; // 0xb0
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30f3074 VA: 0x759570b074
	protected override Void OnRender() { }
	// RVA: 0x30f3344 VA: 0x759570b344
	public Void EventOnClick() { }
	// RVA: 0x30f3460 VA: 0x759570b460
	public Void .ctor() { }
	// RVA: 0x30f34d0 VA: 0x759570b4d0
	private Void <>xLuaBaseProxy_OnRender() { }
}
```