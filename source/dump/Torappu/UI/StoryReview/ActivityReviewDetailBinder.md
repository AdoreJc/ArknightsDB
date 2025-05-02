# ActivityReviewDetailBinder

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `GameObject _lockedPanel`

- `Text _lockedContent`

- `GameObject _maskContainer`

- `ActivityReviewDetailAdapter _activityReviewAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `String _GenLockedContent(Boolean)`

- `Void SetCallbacks(Action`1, Action`1, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class ActivityReviewDetailBinder : DataBinder`1, IHotfixable
{
	private GameObject _lockedPanel; // 0x20
	private Text _lockedContent; // 0x28
	private GameObject _maskContainer; // 0x30
	private ActivityReviewDetailAdapter _activityReviewAdapter; // 0x38
	private Boolean m_isInited; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__GenLockedContent; // 0x10
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x275c1d8 VA: 0x7594d741d8
	private Void _InitIfNot() { }
	// RVA: 0x275c274 VA: 0x7594d74274
	public override Void OnValueChanged(ActivityReviewDetailProperty property) { }
	// RVA: 0x275c62c VA: 0x7594d7462c
	private String _GenLockedContent(Boolean outOfTime) { }
	// RVA: 0x275c6e0 VA: 0x7594d746e0
	public Void SetCallbacks(Action`1 onReviewStoryClicked, Action`1 onUnlockStoryClicked, Action`1 onStoryRead) { }
	// RVA: 0x275c7b8 VA: 0x7594d747b8
	public Void .ctor() { }
}
```