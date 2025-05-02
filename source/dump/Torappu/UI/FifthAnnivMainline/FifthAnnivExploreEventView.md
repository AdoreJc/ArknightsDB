# FifthAnnivExploreEventView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `SimpleLayoutContent _planList`

- `Text _textDesc`

- `UIAnimationLocation _animEnter`

- `Boolean m_hasInited`

- `PlanListAdapter m_planListAdapter`


## Methods

- `Void _InitIfNot()`

- `UIAnimationLocation <>xLuaBaseProxy_GetEnterAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreEventView : FifthAnnivExploreDetailViewBase
{
	private SimpleLayoutContent _planList; // 0x38
	private Text _textDesc; // 0x40
	private UIAnimationLocation _animEnter; // 0x48
	private Boolean m_hasInited; // 0x58
	private PlanListAdapter m_planListAdapter; // 0x60
	private static DelegateBridge __Hotfix0_get_status; // 0x0
	private static DelegateBridge __Hotfix0_GetEnterAnim; // 0x8
	private static DelegateBridge __Hotfix0_OnDataUpdate; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override DecisionStatus status { get; }

	// RVA: 0x291355c VA: 0x7594f2b55c
	protected override DecisionStatus get_status() { }
	// RVA: 0x29135c4 VA: 0x7594f2b5c4
	protected override UIAnimationLocation GetEnterAnim() { }
	// RVA: 0x2913628 VA: 0x7594f2b628
	protected override Void OnDataUpdate() { }
	// RVA: 0x29136f4 VA: 0x7594f2b6f4
	private Void _InitIfNot() { }
	// RVA: 0x2913858 VA: 0x7594f2b858
	public Void .ctor() { }
	// RVA: 0x29138c4 VA: 0x7594f2b8c4
	private UIAnimationLocation <>xLuaBaseProxy_GetEnterAnim() { }
}
```