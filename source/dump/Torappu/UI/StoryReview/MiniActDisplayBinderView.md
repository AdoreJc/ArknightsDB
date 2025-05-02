# MiniActDisplayBinderView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Scrollbar _slidingDisk`

- `UIAnimationLocation _animLocation`

- `Single _focusScrollDuration`

- `Boolean m_isPlayAnim`

- `MiniActDisplayProperty m_property`

- `Tween m_scrollTween`

- `LoopScrollRect m_reviewScrollRect`

- `LoopScrollRect m_trialScrollRect`

- `GridLayoutGroup m_itemGridLayout`


## Methods

- `Void PlaySwitchAnim(Boolean, Action)`

- `Void RecordScrollPos()`

- `Void ScrollToTrialItem(Int32, Int32)`

- `Void InitParam(LoopScrollRect, LoopScrollRect, GridLayoutGroup)`

- `Single CalculatePositionForItem(Int32, Int32)`

- `Tween _ScrollToPos(LoopScrollRect, Single, Single)`

- `Void OnScrollVal(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActDisplayBinderView : DataBinder`1
{
	private Scrollbar _slidingDisk; // 0x20
	private UIAnimationLocation _animLocation; // 0x28
	private Single _focusScrollDuration; // 0x38
	private const Single SCROLL_INTERVAL; // 0x0
	private Boolean m_isPlayAnim; // 0x3c
	private MiniActDisplayProperty m_property; // 0x40
	private Tween m_scrollTween; // 0x48
	private LoopScrollRect m_reviewScrollRect; // 0x50
	private LoopScrollRect m_trialScrollRect; // 0x58
	private GridLayoutGroup m_itemGridLayout; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_PlaySwitchAnim; // 0x8
	private static DelegateBridge __Hotfix0_RecordScrollPos; // 0x10
	private static DelegateBridge __Hotfix0_ScrollToTrialItem; // 0x18
	private static DelegateBridge __Hotfix0_InitParam; // 0x20
	private static DelegateBridge __Hotfix0_CalculatePositionForItem; // 0x28
	private static DelegateBridge __Hotfix0__ScrollToPos; // 0x30
	private static DelegateBridge __Hotfix0_OnScrollVal; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x27472d4 VA: 0x7594d5f2d4
	public override Void OnValueChanged(MiniActDisplayProperty property) { }
	// RVA: 0x27476e0 VA: 0x7594d5f6e0
	public Void PlaySwitchAnim(Boolean showTrial, Action onCompleteCallBack) { }
	// RVA: 0x27479c4 VA: 0x7594d5f9c4
	public Void RecordScrollPos() { }
	// RVA: 0x2747ab4 VA: 0x7594d5fab4
	public Void ScrollToTrialItem(Int32 index, Int32 count) { }
	// RVA: 0x2747c60 VA: 0x7594d5fc60
	public Void InitParam(LoopScrollRect reviewScrollRect, LoopScrollRect trialScrollRect, GridLayoutGroup itemGridLayout) { }
	// RVA: 0x2747d20 VA: 0x7594d5fd20
	public Single CalculatePositionForItem(Int32 index, Int32 count) { }
	// RVA: 0x27474bc VA: 0x7594d5f4bc
	private Tween _ScrollToPos(LoopScrollRect scrollRect, Single normalizedPos, Single duration) { }
	// RVA: 0x2747ea8 VA: 0x7594d5fea8
	public Void OnScrollVal(Vector2 normalizedPos) { }
	// RVA: 0x2747f3c VA: 0x7594d5ff3c
	public Void .ctor() { }
}
```