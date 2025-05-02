# ActMultiV3SquadEffectItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _selectPartGO`

- `GameObject _emptyPartGO`

- `GameObject _normalPartGO`

- `GameObject _equipPartGO`

- `GameObject _selfLabelPartGO`

- `GameObject _partnerLabelPartGO`

- `GameObject _lackKeyLockPartGO`

- `GameObject _unlockablePartGO`

- `Text _textName`

- `Image _imgEffectIcon`

- `UIAtlasImage _imgThemeIcon`

- `UIAnimationLocation _animUnlock`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `String m_cacheThemeColor`

- `AnimationSwitchTween m_unlockTween`

- `ActMultiV3SquadEffectModel m_effectModel`

- `Param m_param`


## Methods

- `Void set_onClick(Action`2)`

- `Void Render(ActMultiV3SquadEffectModel, ActMultiV3SquadEffectSelectModel)`

- `Void Render(ActMultiV3SquadEffectModel, Param)`

- `Void _InitIfNot()`

- `Void _RenderLockPart(ActMultiV3SquadEffectModel, Param)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadEffectItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectPartGO; // 0x18
	private GameObject _emptyPartGO; // 0x20
	private GameObject _normalPartGO; // 0x28
	private GameObject _equipPartGO; // 0x30
	private GameObject _selfLabelPartGO; // 0x38
	private GameObject _partnerLabelPartGO; // 0x40
	private GameObject _lackKeyLockPartGO; // 0x48
	private GameObject _unlockablePartGO; // 0x50
	private Text _textName; // 0x58
	private Image _imgEffectIcon; // 0x60
	private UIAtlasImage _imgThemeIcon; // 0x68
	private UIAnimationLocation _animUnlock; // 0x70
	private Boolean m_hasInited; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private String m_cacheThemeColor; // 0x98
	private AnimationSwitchTween m_unlockTween; // 0xa0
	private ActMultiV3SquadEffectModel m_effectModel; // 0xa8
	private Param m_param; // 0xb0
	private Action`2 <onClick>k__BackingField; // 0xb8
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix1_Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__RenderLockPart; // 0x28
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`2 onClick { get; set; }

	// RVA: 0x313752c VA: 0x759574f52c
	private Action`2 get_onClick() { }
	// RVA: 0x3137594 VA: 0x759574f594
	public Void set_onClick(Action`2 value) { }
	// RVA: 0x3137618 VA: 0x759574f618
	public Void Render(ActMultiV3SquadEffectModel effectModel, ActMultiV3SquadEffectSelectModel selectModel) { }
	// RVA: 0x31379e0 VA: 0x759574f9e0
	public Void Render(ActMultiV3SquadEffectModel effectModel, Param param) { }
	// RVA: 0x3137c38 VA: 0x759574fc38
	private Void _InitIfNot() { }
	// RVA: 0x3137d44 VA: 0x759574fd44
	private Void _RenderLockPart(ActMultiV3SquadEffectModel effectModel, Param param) { }
	// RVA: 0x3137f8c VA: 0x759574ff8c
	public Void EventOnItemClick() { }
	// RVA: 0x313802c VA: 0x759575002c
	public Void .ctor() { }
}
```