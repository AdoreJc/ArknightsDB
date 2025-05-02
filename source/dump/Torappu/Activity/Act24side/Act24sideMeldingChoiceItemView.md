# Act24sideMeldingChoiceItemView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Transform _container`

- `Act24sideMeldingItemView _itemViewPrefab`

- `Text _txtPrice`

- `Text _txtHasCount`

- `Text _txtUseCount`

- `CanvasGroup _canvasUseDec`

- `GameObject _objLine`

- `UILongPressButtonEx _btnAdd`

- `UILongPressButtonEx _btnMinus`

- `String m_cachedItemId`

- `Act24sideMeldingItemView m_itemView`

- `UIStateFinder m_finder`

- `FadeSwitchTween m_tweenCanUseDesc`

- `Boolean m_hasInited`


## Methods

- `Void Render(Act24sideMeldingChoiceItemViewModel)`

- `Void _InitIfNot()`

- `Void _EventOnMinusBtnClick()`

- `Void _EventOnAddBtnClick()`

- `Boolean _EventOnMinusBtnLongPress()`

- `Boolean _EventOnAddBtnLongPress()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingChoiceItemView : MonoBehaviour, IHotfixable
{
	private Transform _container; // 0x18
	private Act24sideMeldingItemView _itemViewPrefab; // 0x20
	private Text _txtPrice; // 0x28
	private Text _txtHasCount; // 0x30
	private Text _txtUseCount; // 0x38
	private CanvasGroup _canvasUseDec; // 0x40
	private GameObject _objLine; // 0x48
	private UILongPressButtonEx _btnAdd; // 0x50
	private UILongPressButtonEx _btnMinus; // 0x58
	private String m_cachedItemId; // 0x60
	private Act24sideMeldingItemView m_itemView; // 0x68
	private UIStateFinder m_finder; // 0x70
	private FadeSwitchTween m_tweenCanUseDesc; // 0x80
	private Boolean m_hasInited; // 0x88
	private static readonly Color COL_HAS_COUNT_ZERO; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__EventOnMinusBtnClick; // 0x20
	private static DelegateBridge __Hotfix0__EventOnAddBtnClick; // 0x28
	private static DelegateBridge __Hotfix0__EventOnMinusBtnLongPress; // 0x30
	private static DelegateBridge __Hotfix0__EventOnAddBtnLongPress; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x32a0684 VA: 0x75958b8684
	public Void Render(Act24sideMeldingChoiceItemViewModel viewModel) { }
	// RVA: 0x32a09e4 VA: 0x75958b89e4
	private Void _InitIfNot() { }
	// RVA: 0x32a0de4 VA: 0x75958b8de4
	private Void _EventOnMinusBtnClick() { }
	// RVA: 0x32a0f0c VA: 0x75958b8f0c
	private Void _EventOnAddBtnClick() { }
	// RVA: 0x32a1034 VA: 0x75958b9034
	private Boolean _EventOnMinusBtnLongPress() { }
	// RVA: 0x32a1168 VA: 0x75958b9168
	private Boolean _EventOnAddBtnLongPress() { }
	// RVA: 0x32a129c VA: 0x75958b929c
	public Void .ctor() { }
	// RVA: 0x32a131c VA: 0x75958b931c
	private static Void .cctor() { }
}
```