# UniEquipArchiveEquipTypeFilterView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `SimpleLayoutContent _content`

- `CanvasGroup _canvasFilterItemListView`

- `Action onTypeFilterBgClick`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `UniEquipArchiveModuleTypeFilterViewModel m_cachedModel`

- `FadeSwitchTween m_tweenFilterItemList`


## Methods

- `Void _InitIfNot()`

- `Void OnFilterViewBgClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEquipTypeFilterView : DataBinder`1
{
	private SimpleLayoutContent _content; // 0x20
	private CanvasGroup _canvasFilterItemListView; // 0x28
	public Action`1 onTypeItemClick; // 0x30
	public Action onTypeFilterBgClick; // 0x38
	private Boolean m_isInited; // 0x40
	private Adapter m_adapter; // 0x48
	private UniEquipArchiveModuleTypeFilterViewModel m_cachedModel; // 0x50
	private FadeSwitchTween m_tweenFilterItemList; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnFilterViewBgClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x22e3c2c VA: 0x75948fbc2c
	public override Void OnValueChanged(UniEquipArchiveModuleTypeFilterViewProperty property) { }
	// RVA: 0x22e3d1c VA: 0x75948fbd1c
	private Void _InitIfNot() { }
	// RVA: 0x22e3f3c VA: 0x75948fbf3c
	public Void OnFilterViewBgClick() { }
	// RVA: 0x22e3fc0 VA: 0x75948fbfc0
	public Void .ctor() { }
}
```