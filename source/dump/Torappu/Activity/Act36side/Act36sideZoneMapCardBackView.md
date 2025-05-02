# Act36sideZoneMapCardBackView

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `Image _imgBack`

- `RectTransform _floatPanel`

- `UIAnimationLocation _scaleSampleAnim`

- `Int32 m_pageIndex`


## Properties

- `Image imgBack`


## Methods

- `Image get_imgBack()`

- `Void _SampleAnim(Single)`

- `Void Render(Int32)`

- `Void UpdateFocusPage(Single)`

- `Void OnCardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideZoneMapCardBackView : MonoBehaviour, IHotfixable
{
	private const Single PAGE_INDEX_MAX; // 0x0
	private const Single PAGE_INDEX_MIN; // 0x0
	private const Single SAMPLE_FACTOR; // 0x0
	private Image _imgBack; // 0x18
	private RectTransform _floatPanel; // 0x20
	private UIAnimationLocation _scaleSampleAnim; // 0x28
	public Action`1 onCardClick; // 0x38
	private Int32 m_pageIndex; // 0x40
	private static DelegateBridge __Hotfix0_get_imgBack; // 0x0
	private static DelegateBridge __Hotfix0__SampleAnim; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_UpdateFocusPage; // 0x18
	private static DelegateBridge __Hotfix0_OnCardClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Image imgBack { get; }

	// RVA: 0x324941c VA: 0x759586141c
	public Image get_imgBack() { }
	// RVA: 0x3249484 VA: 0x7595861484
	private Void _SampleAnim(Single sampleVal) { }
	// RVA: 0x3249524 VA: 0x7595861524
	public Void Render(Int32 pageIndex) { }
	// RVA: 0x32495a0 VA: 0x75958615a0
	public Void UpdateFocusPage(Single pageIndex) { }
	// RVA: 0x32496a8 VA: 0x75958616a8
	public Void OnCardClick() { }
	// RVA: 0x3249730 VA: 0x7595861730
	public Void .ctor() { }
}
```