# StoryReviewUnlockFloatController

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `UIFullScreenImage _fullScreenImage`

- `GameObject _unlockPart`

- `GameObject _container`

- `CanvasGroup _rootView`

- `RectTransform _backBtn`

- `Text _soldText`

- `UIBlurFloatPanel _backImage`

- `Transform _itemContainer1`

- `Transform _itemContainer2`

- `Single _itemScale`

- `Boolean m_isInited`

- `Action m_onClick`

- `UIItemCard m_costItem`

- `UIItemCard m_targetItem`

- `UIItemViewModel m_costModel`

- `UIItemViewModel m_targetModel`

- `UIBlocker m_blocker`


## Methods

- `Void OnDisable()`

- `Void _Init()`

- `Void OnClick()`

- `Void ClosePage()`

- `Void _RenderBackImage()`

- `Void _RenderLockedPart(Int32, String, ItemType, String, Action)`

- `IEnumerator ShowCoroutine()`

- `IEnumerator HideCoroutine()`

- `Void <_Init>b__19_0(Int32)`

- `Void <_Init>b__19_1(Int32)`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewUnlockFloatController : PageSingleComponent, IHotfixable
{
	private UIFullScreenImage _fullScreenImage; // 0x20
	private GameObject _unlockPart; // 0x28
	private GameObject _container; // 0x30
	private CanvasGroup _rootView; // 0x38
	private RectTransform _backBtn; // 0x40
	private Text _soldText; // 0x48
	private UIBlurFloatPanel _backImage; // 0x50
	private Transform _itemContainer1; // 0x58
	private Transform _itemContainer2; // 0x60
	private Single _itemScale; // 0x68
	private Boolean m_isInited; // 0x6c
	private Action m_onClick; // 0x70
	private UIItemCard m_costItem; // 0x78
	private UIItemCard m_targetItem; // 0x80
	private UIItemViewModel m_costModel; // 0x88
	private UIItemViewModel m_targetModel; // 0x90
	private UIBlocker m_blocker; // 0x98
	protected const Single FADE_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnDisable; // 0x8
	private static DelegateBridge __Hotfix0__Init; // 0x10
	private static DelegateBridge __Hotfix0__Inst; // 0x18
	private static DelegateBridge __Hotfix0_RenderLockedPart; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge __Hotfix0_ClosePage; // 0x30
	private static DelegateBridge __Hotfix0__RenderBackImage; // 0x38
	private static DelegateBridge __Hotfix0__RenderLockedPart; // 0x40
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x48
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2760728 VA: 0x7594d78728
	protected override Void OnCreate() { }
	// RVA: 0x2760b28 VA: 0x7594d78b28
	private Void OnDisable() { }
	// RVA: 0x2760838 VA: 0x7594d78838
	private Void _Init() { }
	// RVA: 0x2760bbc VA: 0x7594d78bbc
	private static StoryReviewUnlockFloatController _Inst(Interface pageInterface) { }
	// RVA: 0x2760cdc VA: 0x7594d78cdc
	public static Void RenderLockedPart(Interface pageInterface, Int32 count, String itemId, ItemType itemType, String iconId, Action onClick) { }
	// RVA: 0x27610a0 VA: 0x7594d790a0
	public Void OnClick() { }
	// RVA: 0x276112c VA: 0x7594d7912c
	public Void ClosePage() { }
	// RVA: 0x2761250 VA: 0x7594d79250
	private Void _RenderBackImage() { }
	// RVA: 0x2760e0c VA: 0x7594d78e0c
	private Void _RenderLockedPart(Int32 count, String itemId, ItemType itemType, String iconId, Action onClick) { }
	// RVA: 0x276137c VA: 0x7594d7937c
	private IEnumerator ShowCoroutine() { }
	// RVA: 0x27611a4 VA: 0x7594d791a4
	private IEnumerator HideCoroutine() { }
	// RVA: 0x2761478 VA: 0x7594d79478
	public Void .ctor() { }
	// RVA: 0x2761590 VA: 0x7594d79590
	private Void <_Init>b__19_0(Int32 _) { }
	// RVA: 0x27615c8 VA: 0x7594d795c8
	private Void <_Init>b__19_1(Int32 _) { }
	// RVA: 0x2761600 VA: 0x7594d79600
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```