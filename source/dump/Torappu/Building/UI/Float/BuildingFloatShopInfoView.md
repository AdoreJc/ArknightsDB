# BuildingFloatShopInfoView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Text _textOutput`

- `Text _textOutputLimit`

- `FillProgressBar _progress`

- `RectTransform _outputLine`

- `ShopInfoViewModel m_viewModel`


## Methods

- `Void Start()`

- `Void Update()`

- `Void _UpdateContent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatShopInfoView : DataBinder`1
{
	private BuildingFloatShopInfoStockView[] _stockViews; // 0x20
	private Text _textOutput; // 0x28
	private Text _textOutputLimit; // 0x30
	private FillProgressBar _progress; // 0x38
	private RectTransform _outputLine; // 0x40
	private CountDownTask[] m_countDowns; // 0x48
	private ShopInfoViewModel m_viewModel; // 0x50
	private ShopStockSnapshot[] m_snapshots; // 0x58
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3e2e708 VA: 0x7596446708
	private Void Start() { }
	// RVA: 0x3e2e79c VA: 0x759644679c
	private Void Update() { }
	// RVA: 0x3e2e86c VA: 0x759644686c
	public override Void OnValueChanged(FloatShopInfoViewProperty property) { }
	// RVA: 0x3e2e9ec VA: 0x75964469ec
	private Void _UpdateContent() { }
	// RVA: 0x3e2eda0 VA: 0x7596446da0
	public Void .ctor() { }
}
```