# TuningProductConfirmView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductCircleView _circleView`

- `Color _circleColor`

- `Text _productTypeName`

- `Text _orcheName`

- `Text _formDesc`

- `Text _formDescFrontBracket`

- `Text _formDescBehindBracket`

- `GameObject _formObj`

- `GameObject _orcheObj`

- `GameObject _isNewProductTypeObj`

- `Transform _cardHolder`

- `TuningCommonCard _commonCardPrefab`

- `Single _cardScaler`

- `UIAtlasImage _tintImg`

- `UIStateFinder m_stateFinder`

- `Int32 m_cachedEnterSequenceNum`

- `TuningCommonCard m_commonCard`


## Methods

- `Void _RenderCircle(TuningProductConfirmViewModel)`

- `Void _RenderDesc(TuningProductConfirmViewModel)`

- `Void _RenderEye(Act29SideProductType)`

- `Void _ResetEye()`

- `Void OnClickBackgroundBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductConfirmView : DataBinder`1
{
	private TuningProductCircleView _circleView; // 0x20
	private Color _circleColor; // 0x28
	private List`1 _orcheIdToFormEffectViewList; // 0x38
	private Text _productTypeName; // 0x40
	private Text _orcheName; // 0x48
	private Text _formDesc; // 0x50
	private Text _formDescFrontBracket; // 0x58
	private Text _formDescBehindBracket; // 0x60
	private GameObject _formObj; // 0x68
	private GameObject _orcheObj; // 0x70
	private GameObject _isNewProductTypeObj; // 0x78
	private List`1 _productEyeToViewList; // 0x80
	private Transform _cardHolder; // 0x88
	private TuningCommonCard _commonCardPrefab; // 0x90
	private Single _cardScaler; // 0x98
	private UIAtlasImage _tintImg; // 0xa0
	private UIStateFinder m_stateFinder; // 0xa8
	private Int32 m_cachedEnterSequenceNum; // 0xb8
	private TuningCommonCard m_commonCard; // 0xc0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderCircle; // 0x8
	private static DelegateBridge __Hotfix0__RenderDesc; // 0x10
	private static DelegateBridge __Hotfix0__RenderEye; // 0x18
	private static DelegateBridge __Hotfix0__ResetEye; // 0x20
	private static DelegateBridge __Hotfix0_OnClickBackgroundBtn; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2345f4c VA: 0x759495df4c
	public override Void OnValueChanged(TuningProductConfirmProperty property) { }
	// RVA: 0x2346320 VA: 0x759495e320
	private Void _RenderCircle(TuningProductConfirmViewModel model) { }
	// RVA: 0x23464a0 VA: 0x759495e4a0
	private Void _RenderDesc(TuningProductConfirmViewModel model) { }
	// RVA: 0x2346760 VA: 0x759495e760
	private Void _RenderEye(Act29SideProductType productType) { }
	// RVA: 0x23461ec VA: 0x759495e1ec
	private Void _ResetEye() { }
	// RVA: 0x2346d90 VA: 0x759495ed90
	public Void OnClickBackgroundBtn() { }
	// RVA: 0x2346e34 VA: 0x759495ee34
	public Void .ctor() { }
}
```