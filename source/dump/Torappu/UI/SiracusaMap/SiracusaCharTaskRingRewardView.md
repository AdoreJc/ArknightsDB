# SiracusaCharTaskRingRewardView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _textCurrent`

- `Text _textMax`

- `Text _textRingDesc`

- `RectTransform _itemRoot`

- `SimpleLayoutContent _placeList`

- `Single _itemScale`

- `GameObject _rewardItemGo`

- `GameObject _btnTakeRewardGo`

- `GameObject _btnCompleteTaskGo`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIItemCard m_itemCard`

- `SiracusaCharTaskRingModel m_ringModel`

- `SiracusaCharTaskRingRewardState m_closure`


## Methods

- `Void SetClosure(SiracusaCharTaskRingRewardState)`

- `Void _RenderRewardView(Boolean)`

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__17_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharTaskRingRewardView : DataBinder`1
{
	private Text _textCurrent; // 0x20
	private Text _textMax; // 0x28
	private Text _textRingDesc; // 0x30
	private RectTransform _itemRoot; // 0x38
	private SimpleLayoutContent _placeList; // 0x40
	private Single _itemScale; // 0x48
	private GameObject _rewardItemGo; // 0x50
	private GameObject _btnTakeRewardGo; // 0x58
	private GameObject _btnCompleteTaskGo; // 0x60
	private Boolean m_hasInited; // 0x68
	private Adapter m_adapter; // 0x70
	private UIItemCard m_itemCard; // 0x78
	private SiracusaCharTaskRingModel m_ringModel; // 0x80
	private SiracusaCharTaskRingRewardState m_closure; // 0x88
	private static DelegateBridge __Hotfix0_SetClosure; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__RenderRewardView; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x23eb5f0 VA: 0x7594a035f0
	public Void SetClosure(SiracusaCharTaskRingRewardState closure) { }
	// RVA: 0x23ec150 VA: 0x7594a04150
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23ec570 VA: 0x7594a04570
	private Void _RenderRewardView(Boolean isRetro) { }
	// RVA: 0x23ec314 VA: 0x7594a04314
	private Void _InitIfNot() { }
	// RVA: 0x23ec744 VA: 0x7594a04744
	public Void .ctor() { }
	// RVA: 0x23ec7dc VA: 0x7594a047dc
	private Void <_InitIfNot>b__17_0(Int32 index) { }
}
```