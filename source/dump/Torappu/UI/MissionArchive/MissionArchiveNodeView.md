# MissionArchiveNodeView

**Namespace:** `Torappu.UI.MissionArchive`


## Fields

- `String _nodeId`

- `UIAnimationLocation _selectAnimation`

- `Text _nodeTitleText`

- `Boolean m_hasInited`

- `AnimationWrapper m_animationWrapper`

- `Builder m_selectTweenBuilder`

- `UIAnimationTween m_selectTween`


## Properties

- `String nodeId`


## Methods

- `String get_nodeId()`

- `Void set_selectEvent(Action`1)`

- `Void OnSelectEvent()`

- `Void Render(MissionArchiveNodeViewModel)`

- `Tween PlaySelect()`

- `Void ResetSelect()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.MissionArchive
public class MissionArchiveNodeView : MonoBehaviour, IHotfixable
{
	private String _nodeId; // 0x18
	private UIAnimationLocation _selectAnimation; // 0x20
	private GameObject[] _lockedPanels; // 0x30
	private GameObject[] _notLockedPanels; // 0x38
	private GameObject[] _unlockedPanels; // 0x40
	private GameObject[] _notUnlockedPanels; // 0x48
	private GameObject[] _claimedPanels; // 0x50
	private Text _nodeTitleText; // 0x58
	private Boolean m_hasInited; // 0x60
	private AnimationWrapper m_animationWrapper; // 0x68
	private Builder m_selectTweenBuilder; // 0x70
	private UIAnimationTween m_selectTween; // 0x98
	private Action`1 <selectEvent>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_nodeId; // 0x0
	private static DelegateBridge __Hotfix0_get_selectEvent; // 0x8
	private static DelegateBridge __Hotfix0_set_selectEvent; // 0x10
	private static DelegateBridge __Hotfix0_OnSelectEvent; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_PlaySelect; // 0x28
	private static DelegateBridge __Hotfix0_ResetSelect; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String nodeId { get; }
	private Action`1 selectEvent { get; set; }

	// RVA: 0x272bc24 VA: 0x7594d43c24
	public String get_nodeId() { }
	// RVA: 0x272c174 VA: 0x7594d44174
	private Action`1 get_selectEvent() { }
	// RVA: 0x272c060 VA: 0x7594d44060
	public Void set_selectEvent(Action`1 value) { }
	// RVA: 0x272c1dc VA: 0x7594d441dc
	public Void OnSelectEvent() { }
	// RVA: 0x272bc8c VA: 0x7594d43c8c
	public Void Render(MissionArchiveNodeViewModel model) { }
	// RVA: 0x272bf0c VA: 0x7594d43f0c
	public Tween PlaySelect() { }
	// RVA: 0x272bfe0 VA: 0x7594d43fe0
	public Void ResetSelect() { }
	// RVA: 0x272c27c VA: 0x7594d4427c
	private Void _InitIfNot() { }
	// RVA: 0x272c390 VA: 0x7594d44390
	public Void .ctor() { }
}
```