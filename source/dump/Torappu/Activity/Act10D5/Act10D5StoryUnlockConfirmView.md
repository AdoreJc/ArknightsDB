# Act10D5StoryUnlockConfirmView

**Namespace:** `Torappu.Activity.Act10D5`


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

- `Void Initialize()`

- `Void _Init()`

- `Void RenderLockedPart(Int32, String, ItemType, String, Action)`

- `Void OnClick()`

- `Void ClosePage()`

- `Void OnDisable()`

- `Void _RenderBackImage()`

- `Void _RenderLockedPart(Int32, String, ItemType, String, Action)`

- `IEnumerator ShowCoroutine()`

- `IEnumerator HideCoroutine()`

- `Void <_Init>b__18_0(Int32)`

- `Void <_Init>b__18_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5StoryUnlockConfirmView : MonoBehaviour, IHotfixable
{
	private UIFullScreenImage _fullScreenImage; // 0x18
	private GameObject _unlockPart; // 0x20
	private GameObject _container; // 0x28
	private CanvasGroup _rootView; // 0x30
	private RectTransform _backBtn; // 0x38
	private Text _soldText; // 0x40
	private UIBlurFloatPanel _backImage; // 0x48
	private Transform _itemContainer1; // 0x50
	private Transform _itemContainer2; // 0x58
	private Single _itemScale; // 0x60
	private Boolean m_isInited; // 0x64
	private Action m_onClick; // 0x68
	private UIItemCard m_costItem; // 0x70
	private UIItemCard m_targetItem; // 0x78
	private UIItemViewModel m_costModel; // 0x80
	private UIItemViewModel m_targetModel; // 0x88
	private UIBlocker m_blocker; // 0x90
	protected const Single FADE_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_Initialize; // 0x0
	private static DelegateBridge __Hotfix0__Init; // 0x8
	private static DelegateBridge __Hotfix0_RenderLockedPart; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_ClosePage; // 0x20
	private static DelegateBridge __Hotfix0_OnDisable; // 0x28
	private static DelegateBridge __Hotfix0__RenderBackImage; // 0x30
	private static DelegateBridge __Hotfix0__RenderLockedPart; // 0x38
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x40
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x3487ff0 VA: 0x7595a9fff0
	public Void Initialize() { }
	// RVA: 0x34880fc VA: 0x7595aa00fc
	private Void _Init() { }
	// RVA: 0x3488400 VA: 0x7595aa0400
	public Void RenderLockedPart(Int32 count, String itemId, ItemType itemType, String iconId, Action onClick) { }
	// RVA: 0x348875c VA: 0x7595aa075c
	public Void OnClick() { }
	// RVA: 0x34887e8 VA: 0x7595aa07e8
	public Void ClosePage() { }
	// RVA: 0x348890c VA: 0x7595aa090c
	private Void OnDisable() { }
	// RVA: 0x34889a0 VA: 0x7595aa09a0
	private Void _RenderBackImage() { }
	// RVA: 0x34884c8 VA: 0x7595aa04c8
	private Void _RenderLockedPart(Int32 count, String itemId, ItemType itemType, String iconId, Action onClick) { }
	// RVA: 0x3488acc VA: 0x7595aa0acc
	private IEnumerator ShowCoroutine() { }
	// RVA: 0x3488860 VA: 0x7595aa0860
	private IEnumerator HideCoroutine() { }
	// RVA: 0x3488bc8 VA: 0x7595aa0bc8
	public Void .ctor() { }
	// RVA: 0x3488ce0 VA: 0x7595aa0ce0
	private Void <_Init>b__18_0(Int32 _) { }
	// RVA: 0x3488d18 VA: 0x7595aa0d18
	private Void <_Init>b__18_1(Int32 _) { }
}
```