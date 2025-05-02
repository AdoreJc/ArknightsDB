# CarvingMainShopGoodSlotView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Color _notEnoughSelectTextColor`

- `Color _notEnoughNotSelectTextColor`

- `Color _enoughSelectTextColor`

- `Color _enoughNotSelectTextColor`

- `Text _priceTxt`

- `GameObject _priceBgEnough`

- `GameObject _priceBgNotEnough`

- `CanvasGroup _slotGroup`

- `Text _unlockCntTxt`

- `UIAnimationLocation _selectAnimLocation`

- `GameObject _emptyObj`

- `AnimationSwitchTween m_selectAnimSwitchTween`

- `FadeSwitchTween m_fadeSwitchTween`

- `Int32 m_buySeqNum`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(CarvingMainShopGoodSlotItemModel, Boolean)`

- `Void _InitIfNot()`

- `Void OnClickSelectItemBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainShopGoodSlotView : MonoBehaviour, IHotfixable
{
	private Color _notEnoughSelectTextColor; // 0x18
	private Color _notEnoughNotSelectTextColor; // 0x28
	private Color _enoughSelectTextColor; // 0x38
	private Color _enoughNotSelectTextColor; // 0x48
	private Text _priceTxt; // 0x58
	private GameObject _priceBgEnough; // 0x60
	private GameObject _priceBgNotEnough; // 0x68
	private CanvasGroup _slotGroup; // 0x70
	private Text _unlockCntTxt; // 0x78
	private UIAnimationLocation _selectAnimLocation; // 0x80
	private GameObject _emptyObj; // 0x90
	private AnimationSwitchTween m_selectAnimSwitchTween; // 0x98
	private FadeSwitchTween m_fadeSwitchTween; // 0xa0
	private Int32 m_buySeqNum; // 0xa8
	private Boolean m_isInited; // 0xac
	private UIPageFinder m_pageFinder; // 0xb0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClickSelectItemBtn; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2db7290 VA: 0x75953cf290
	public Void Render(CarvingMainShopGoodSlotItemModel model, Boolean isEnough) { }
	// RVA: 0x2db7580 VA: 0x75953cf580
	private Void _InitIfNot() { }
	// RVA: 0x2db76d8 VA: 0x75953cf6d8
	public Void OnClickSelectItemBtn() { }
	// RVA: 0x2db777c VA: 0x75953cf77c
	public Void .ctor() { }
}
```