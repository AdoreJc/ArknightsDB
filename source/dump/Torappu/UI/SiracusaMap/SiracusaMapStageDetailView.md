# SiracusaMapStageDetailView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `GameObject _objContentPart`

- `GameObject _objEmptyPart`

- `UIAtlasImage _imgEntryIcon`

- `UIAtlasObject _atlas`

- `Text _txtEntryName1`

- `Text _txtEntryName2`

- `SiracusaMapStageDetailListAdapter _listAdapter`

- `CanvasGroup _canvas`

- `Boolean m_isInited`

- `String m_cachedEntryId`

- `FadeSwitchTween m_fadeTween`

- `Boolean m_rendered`

- `SiracusaMapController <closure>k__BackingField`

- `Action <eventOnDetailItemUnselect>k__BackingField`


## Properties

- `SiracusaMapController closure`

- `Action eventOnDetailItemUnselect`


## Methods

- `SiracusaMapController get_closure()`

- `Void set_closure(SiracusaMapController)`

- `Void set_eventOnDetailItemSelect(Action`1)`

- `Action get_eventOnDetailItemUnselect()`

- `Void set_eventOnDetailItemUnselect(Action)`

- `Void _InitIfNot()`

- `Void _OnDetailItemSelect(String)`

- `Void _Render(SiracusaMapNavigationDetailViewModel)`

- `Void OnDetailItemUnselect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapStageDetailView : DataBinder`1
{
	private GameObject _objContentPart; // 0x20
	private GameObject _objEmptyPart; // 0x28
	private UIAtlasImage _imgEntryIcon; // 0x30
	private UIAtlasObject _atlas; // 0x38
	private Text _txtEntryName1; // 0x40
	private Text _txtEntryName2; // 0x48
	private SiracusaMapStageDetailListAdapter _listAdapter; // 0x50
	private CanvasGroup _canvas; // 0x58
	private Boolean m_isInited; // 0x60
	private String m_cachedEntryId; // 0x68
	private FadeSwitchTween m_fadeTween; // 0x70
	private Boolean m_rendered; // 0x78
	private SiracusaMapController <closure>k__BackingField; // 0x80
	private Action`1 <eventOnDetailItemSelect>k__BackingField; // 0x88
	private Action <eventOnDetailItemUnselect>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_closure; // 0x0
	private static DelegateBridge __Hotfix0_set_closure; // 0x8
	private static DelegateBridge __Hotfix0_get_eventOnDetailItemSelect; // 0x10
	private static DelegateBridge __Hotfix0_set_eventOnDetailItemSelect; // 0x18
	private static DelegateBridge __Hotfix0_get_eventOnDetailItemUnselect; // 0x20
	private static DelegateBridge __Hotfix0_set_eventOnDetailItemUnselect; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnDetailItemSelect; // 0x38
	private static DelegateBridge __Hotfix0__Render; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x48
	private static DelegateBridge __Hotfix0_OnDetailItemUnselect; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public SiracusaMapController closure { get; set; }
	public Action`1 eventOnDetailItemSelect { get; set; }
	public Action eventOnDetailItemUnselect { get; set; }

	// RVA: 0x23e2e20 VA: 0x75949fae20
	public SiracusaMapController get_closure() { }
	// RVA: 0x23e2e88 VA: 0x75949fae88
	public Void set_closure(SiracusaMapController value) { }
	// RVA: 0x23e2f0c VA: 0x75949faf0c
	public Action`1 get_eventOnDetailItemSelect() { }
	// RVA: 0x23e2f74 VA: 0x75949faf74
	public Void set_eventOnDetailItemSelect(Action`1 value) { }
	// RVA: 0x23e2ff8 VA: 0x75949faff8
	public Action get_eventOnDetailItemUnselect() { }
	// RVA: 0x23e3060 VA: 0x75949fb060
	public Void set_eventOnDetailItemUnselect(Action value) { }
	// RVA: 0x23e30e4 VA: 0x75949fb0e4
	private Void _InitIfNot() { }
	// RVA: 0x23e3258 VA: 0x75949fb258
	private Void _OnDetailItemSelect(String key) { }
	// RVA: 0x23e3310 VA: 0x75949fb310
	private Void _Render(SiracusaMapNavigationDetailViewModel viewModel) { }
	// RVA: 0x23e3598 VA: 0x75949fb598
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23e3650 VA: 0x75949fb650
	public Void OnDetailItemUnselect() { }
	// RVA: 0x23e36f4 VA: 0x75949fb6f4
	public Void .ctor() { }
}
```