# ActivityFirstMicroMapView

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `ActivityFirstMicroMapObj _obj`

- `Transform _objContainer`

- `Transform _dropItemContainer`

- `Text _detailInfo`

- `Single _itemCardScaleFactor`

- `UIStringEvent _stringEvent`

- `UIItemCard m_itemObj`

- `Boolean m_initFlag`

- `ActivityFirstUtil m_cacheLoader`


## Methods

- `Void _InitIfNot(List`1)`

- `Void OnSelect(String, DefaultZoneData)`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstMicroMapView : DataBinder`1, IHotfixable
{
	private ActivityFirstMicroMapObj _obj; // 0x20
	private Transform _objContainer; // 0x28
	private Transform _dropItemContainer; // 0x30
	private Text _detailInfo; // 0x38
	private Single _itemCardScaleFactor; // 0x40
	private UIStringEvent _stringEvent; // 0x48
	private UIItemCard m_itemObj; // 0x50
	private Boolean m_initFlag; // 0x58
	private List`1 m_itemList; // 0x60
	private List`1 m_objList; // 0x68
	private ActivityFirstUtil m_cacheLoader; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnSelect; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3490f8c VA: 0x7595aa8f8c
	private Void _InitIfNot(List`1 zoneList) { }
	// RVA: 0x34911e8 VA: 0x7595aa91e8
	public Void OnSelect(String zoneId, DefaultZoneData zoneData) { }
	// RVA: 0x34915fc VA: 0x7595aa95fc
	public override Void OnValueChanged(ActivityFirstMapProperty property) { }
	// RVA: 0x349180c VA: 0x7595aa980c
	private Void _OnItemCardClicked(Int32 position) { }
	// RVA: 0x3491938 VA: 0x7595aa9938
	public Void .ctor() { }
}
```