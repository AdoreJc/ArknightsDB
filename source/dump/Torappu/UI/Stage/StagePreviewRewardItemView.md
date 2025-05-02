# StagePreviewRewardItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Transform _itemCardContainer`

- `Single _scalePercent`

- `GameObject _alwaysPart`

- `GameObject _almostPart`

- `GameObject _sometimePart`

- `GameObject _usualPart`

- `GameObject _oftenPart`

- `GameObject _alreadyGetPart`

- `GameObject _threeStarGetPart`

- `GameObject _overridePart`

- `Text _overrideDropTagText`

- `Transform _timelyDropContainer`

- `GameObject m_timelyDropItem`

- `String m_cacheDropId`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnItemClicked(Int32)`

- `Void Render(StageRewardDetailViewModel, Boolean, Boolean, String, String)`

- `Void _RenderTimelyDrop(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewRewardItemView : MonoBehaviour, IHotfixable
{
	private Transform _itemCardContainer; // 0x18
	private Single _scalePercent; // 0x20
	private GameObject _alwaysPart; // 0x28
	private GameObject _almostPart; // 0x30
	private GameObject _sometimePart; // 0x38
	private GameObject _usualPart; // 0x40
	private GameObject _oftenPart; // 0x48
	private GameObject _alreadyGetPart; // 0x50
	private GameObject _threeStarGetPart; // 0x58
	private GameObject _overridePart; // 0x60
	private Text _overrideDropTagText; // 0x68
	private Transform _timelyDropContainer; // 0x70
	private GameObject m_timelyDropItem; // 0x78
	private String m_cacheDropId; // 0x80
	private UIItemCard m_itemCard; // 0x88
	private Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderTimelyDrop; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f9e990 VA: 0x75955b6990
	private Void _InitIfNot() { }
	// RVA: 0x2f9ebcc VA: 0x75955b6bcc
	private Void _OnItemClicked(Int32 index) { }
	// RVA: 0x2f9ecd4 VA: 0x75955b6cd4
	public Void Render(StageRewardDetailViewModel viewModel, Boolean getFlag, Boolean completeFlag, String timelyDropId, String overrideDropId) { }
	// RVA: 0x2f9ef78 VA: 0x75955b6f78
	private Void _RenderTimelyDrop(String timelyDropId) { }
	// RVA: 0x2f9f1b4 VA: 0x75955b71b4
	public Void .ctor() { }
}
```