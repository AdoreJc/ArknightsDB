# NameCardV2EquipmentCollectionInfoItemView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Text _txtTitle`

- `Text _txtCurCount`

- `Text _txtTotalCount`

- `UIAnimationLocation _switchAnim`

- `UIColorGraphic _needChangeStyleText`

- `Boolean m_hasInited`

- `UniEquipArchiveCollectionInfoType m_cachedType`

- `AnimationSwitchTween m_switchTween`

- `Boolean m_showTotal`


## Properties

- `UIColorGraphic needChangeStyleText`

- `Boolean showTotal`


## Methods

- `UIColorGraphic get_needChangeStyleText()`

- `Boolean get_showTotal()`

- `Void Render(NameCardV2EquipmentCollectionInfoItemViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2EquipmentCollectionInfoItemView : MonoBehaviour, IHotfixable
{
	private Text _txtTitle; // 0x18
	private Text _txtCurCount; // 0x20
	private Text _txtTotalCount; // 0x28
	private UIAnimationLocation _switchAnim; // 0x30
	private UIColorGraphic _needChangeStyleText; // 0x40
	private Boolean m_hasInited; // 0x48
	private UniEquipArchiveCollectionInfoType m_cachedType; // 0x4c
	private AnimationSwitchTween m_switchTween; // 0x50
	private Boolean m_showTotal; // 0x58
	private static DelegateBridge __Hotfix0_get_needChangeStyleText; // 0x0
	private static DelegateBridge __Hotfix0_get_showTotal; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public UIColorGraphic needChangeStyleText { get; }
	public Boolean showTotal { get; }

	// RVA: 0x28e3ed0 VA: 0x7594efbed0
	public UIColorGraphic get_needChangeStyleText() { }
	// RVA: 0x28d7b64 VA: 0x7594eefb64
	public Boolean get_showTotal() { }
	// RVA: 0x28e3f38 VA: 0x7594efbf38
	public Void Render(NameCardV2EquipmentCollectionInfoItemViewModel itemViewModel) { }
	// RVA: 0x28e40f0 VA: 0x7594efc0f0
	private Void _InitIfNot() { }
	// RVA: 0x28e41e0 VA: 0x7594efc1e0
	public Void .ctor() { }
}
```