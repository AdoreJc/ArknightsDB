# RecruitBuildSlotGroupView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `SimpleLayoutContent _slotsLayout`

- `UIIntEvent _fastFinishEvent`

- `UIIntEvent _stopRecruitEvent`

- `UIIntEvent _startRecruitEvent`

- `UIIntEvent _buildTimeUpEvent`

- `UIIntEvent _finishBuildEvent`

- `UIIntEvent _buyBuildEvent`

- `SlotsAdapter m_slotsAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildSlotGroupView : DataBinder`1
{
	private SimpleLayoutContent _slotsLayout; // 0x20
	private UIIntEvent _fastFinishEvent; // 0x28
	private UIIntEvent _stopRecruitEvent; // 0x30
	private UIIntEvent _startRecruitEvent; // 0x38
	private UIIntEvent _buildTimeUpEvent; // 0x40
	private UIIntEvent _finishBuildEvent; // 0x48
	private UIIntEvent _buyBuildEvent; // 0x50
	private List`1 m_slotModelsCache; // 0x58
	private SlotsAdapter m_slotsAdapter; // 0x60
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2705960 VA: 0x7594d1d960
	private Void _InitIfNot() { }
	// RVA: 0x2705ab0 VA: 0x7594d1dab0
	public override Void OnValueChanged(BuildSlotGroupViewProperty property) { }
	// RVA: 0x2705b7c VA: 0x7594d1db7c
	public Void .ctor() { }
}
```