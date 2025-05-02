# BuildingFloatManufactInfoView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `GameObject _panelItems`

- `GameObject _panelEmpty`

- `Text _textCount`

- `Text _textLimit`

- `Text _textManufState`

- `Text _textItemName`

- `RectTransform _itemCardContainer`

- `Single _itemScale`

- `Text _textTime`

- `FillProgressBar _progress`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `CountDownTask m_outputCountDown`

- `CountDownTask m_totalRemainCountDown`

- `ManufactInfoViewModel m_manufactInfo`

- `UIItemViewModel m_itemModel`


## Methods

- `Void _Init()`

- `Void _UpdateActiveContent()`

- `Void _UpdateAutoLayouts()`

- `Void _OnTimeTick(TickValue)`

- `Void _UpdateManufactInfo()`

- `Void Start()`

- `Void Update()`

- `Void <_UpdateManufactInfo>b__22_0(Boolean, ManufactSnapshot)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatManufactInfoView : DataBinder`1
{
	private GameObject _panelItems; // 0x20
	private GameObject _panelEmpty; // 0x28
	private Text _textCount; // 0x30
	private Text _textLimit; // 0x38
	private Text _textManufState; // 0x40
	private Text _textItemName; // 0x48
	private RectTransform _itemCardContainer; // 0x50
	private Single _itemScale; // 0x58
	private Text _textTime; // 0x60
	private FillProgressBar _progress; // 0x68
	private RectTransform[] _autoLayouts; // 0x70
	private Boolean m_isInited; // 0x78
	private UIItemCard m_itemCard; // 0x80
	private CountDownTask m_outputCountDown; // 0x88
	private CountDownTask m_totalRemainCountDown; // 0x90
	private ManufactInfoViewModel m_manufactInfo; // 0x98
	private UIItemViewModel m_itemModel; // 0xa0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Init; // 0x8
	private static DelegateBridge __Hotfix0__UpdateActiveContent; // 0x10
	private static DelegateBridge __Hotfix0__UpdateAutoLayouts; // 0x18
	private static DelegateBridge __Hotfix0__OnTimeTick; // 0x20
	private static DelegateBridge __Hotfix0__UpdateManufactInfo; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_Update; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3e2c890 VA: 0x7596444890
	public override Void OnValueChanged(FloatManufactViewProperty property) { }
	// RVA: 0x3e2c9b4 VA: 0x75964449b4
	private Void _Init() { }
	// RVA: 0x3e2cb3c VA: 0x7596444b3c
	private Void _UpdateActiveContent() { }
	// RVA: 0x3e2cfa8 VA: 0x7596444fa8
	private Void _UpdateAutoLayouts() { }
	// RVA: 0x3e2d0a8 VA: 0x75964450a8
	private Void _OnTimeTick(TickValue tick) { }
	// RVA: 0x3e2cc24 VA: 0x7596444c24
	private Void _UpdateManufactInfo() { }
	// RVA: 0x3e2d224 VA: 0x7596445224
	private Void Start() { }
	// RVA: 0x3e2d28c VA: 0x759644528c
	private Void Update() { }
	// RVA: 0x3e2d318 VA: 0x7596445318
	public Void .ctor() { }
	// RVA: 0x3e2d3e8 VA: 0x75964453e8
	private Void <_UpdateManufactInfo>b__22_0(Boolean shouldCountDown, ManufactSnapshot snapshotParam) { }
}
```