# CrisisShopViewHolder

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `CrisisLongTermShopView _longTermView`

- `CrisisSeasonShopView _seasonView`

- `UIAtlasImage _shopTitle`

- `ScrollRect _scrollRect`

- `CanvasGroup _canvasGroup`

- `CrisisShopEvent clickEvent`

- `GameObject _crisisV1Title`

- `GameObject _crisisV2Title`

- `UIPageFinder m_finder`


## Properties

- `ScrollRect scrollRect`

- `CanvasGroup canvasGroup`


## Methods

- `ScrollRect get_scrollRect()`

- `CanvasGroup get_canvasGroup()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopViewHolder : DataBinder`1
{
	private CrisisLongTermShopView _longTermView; // 0x20
	private CrisisSeasonShopView _seasonView; // 0x28
	private UIAtlasImage _shopTitle; // 0x30
	private ScrollRect _scrollRect; // 0x38
	private CanvasGroup _canvasGroup; // 0x40
	public CrisisShopEvent clickEvent; // 0x48
	private GameObject _crisisV1Title; // 0x50
	private GameObject _crisisV2Title; // 0x58
	private UIPageFinder m_finder; // 0x60
	private static DelegateBridge __Hotfix0_get_scrollRect; // 0x0
	private static DelegateBridge __Hotfix0_get_canvasGroup; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public ScrollRect scrollRect { get; }
	public CanvasGroup canvasGroup { get; }

	// RVA: 0x2c3b288 VA: 0x7595253288
	public ScrollRect get_scrollRect() { }
	// RVA: 0x2c3b2f0 VA: 0x75952532f0
	public CanvasGroup get_canvasGroup() { }
	// RVA: 0x2c3b358 VA: 0x7595253358
	public override Void OnValueChanged(CrisisShopInfoProperty property) { }
	// RVA: 0x2c3b5cc VA: 0x75952535cc
	public Void .ctor() { }
}
```