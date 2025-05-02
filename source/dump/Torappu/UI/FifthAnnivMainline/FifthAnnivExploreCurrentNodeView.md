# FifthAnnivExploreCurrentNodeView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `UIAnimationLocation _enterAnimLocation`

- `UIAnimationLocation _loopAnimLocation`

- `UIAnimationLocation _outAnimLocation`

- `Single _delayFirstNodeShow`

- `Single _delayShow`

- `FifthAnnivNodeType m_nodeType`

- `Boolean m_isShown`

- `Tween m_tween`


## Methods

- `Tween _PlayEnterAnim(Single, Action)`

- `Tween _PlayLoopAnim()`

- `Tween _PlayOutAnim()`

- `Void <Render>b__8_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreCurrentNodeView : FifthAnnivExploreAbstractNodeView
{
	private UIAnimationLocation _enterAnimLocation; // 0x18
	private UIAnimationLocation _loopAnimLocation; // 0x28
	private UIAnimationLocation _outAnimLocation; // 0x38
	private Single _delayFirstNodeShow; // 0x48
	private Single _delayShow; // 0x4c
	private FifthAnnivNodeType m_nodeType; // 0x50
	private Boolean m_isShown; // 0x54
	private Tween m_tween; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x8
	private static DelegateBridge __Hotfix0__PlayLoopAnim; // 0x10
	private static DelegateBridge __Hotfix0__PlayOutAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x29255a4 VA: 0x7594f3d5a4
	public override Void Render(FifthAnnivExploreMapNodeViewModel nodeViewModel, Int32 currentIndexInRoute) { }
	// RVA: 0x29257f4 VA: 0x7594f3d7f4
	private Tween _PlayEnterAnim(Single delay, Action onEnterCompleted) { }
	// RVA: 0x2925a80 VA: 0x7594f3da80
	private Tween _PlayLoopAnim() { }
	// RVA: 0x2925730 VA: 0x7594f3d730
	private Tween _PlayOutAnim() { }
	// RVA: 0x2925b70 VA: 0x7594f3db70
	public Void .ctor() { }
	// RVA: 0x2925be4 VA: 0x7594f3dbe4
	private Void <Render>b__8_0() { }
}
```