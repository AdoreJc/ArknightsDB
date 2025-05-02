# SiracusaCharSelectRewardItemView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Transform _itemCardContainer`

- `Single _scalePercent`

- `GameObject _alreadyGetPart`

- `CanvasGroup _canvas`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(SiracusaCharSelectTaskRingRewardInfo, Boolean, Boolean)`

- `Void _OnItemClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectRewardItemView : MonoBehaviour, IHotfixable
{
	private Transform _itemCardContainer; // 0x18
	private Single _scalePercent; // 0x20
	private GameObject _alreadyGetPart; // 0x28
	private CanvasGroup _canvas; // 0x30
	private UIItemCard m_itemCard; // 0x38
	private Boolean m_isInited; // 0x40
	private const Single GOT_ALPHA; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23ee590 VA: 0x7594a06590
	private Void _InitIfNot() { }
	// RVA: 0x23ee7cc VA: 0x7594a067cc
	public Void Render(SiracusaCharSelectTaskRingRewardInfo info, Boolean clickable, Boolean needShowHasGetTag) { }
	// RVA: 0x23ee8e4 VA: 0x7594a068e4
	private Void _OnItemClicked(Int32 index) { }
	// RVA: 0x23ee9ec VA: 0x7594a069ec
	public Void .ctor() { }
}
```