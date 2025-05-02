# TuningHomeInvestGroupView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningHomeMajorInvestView _majorView`

- `TuningHomeHiddenInvestView _hiddenView`

- `SimpleLayoutContent _normalContent`

- `GameObject _panelRemainTime`

- `Text _textRemainTime`

- `Boolean m_hasInited`

- `Int32 m_cacheEntryAnimSequence`

- `NormalAdapter m_adapter`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeInvestGroupView : DataBinder`1, IHotfixable
{
	private TuningHomeMajorInvestView _majorView; // 0x20
	private TuningHomeHiddenInvestView _hiddenView; // 0x28
	private SimpleLayoutContent _normalContent; // 0x30
	private GameObject _panelRemainTime; // 0x38
	private Text _textRemainTime; // 0x40
	private Boolean m_hasInited; // 0x48
	private List`1 m_cacheNormalInvestModel; // 0x50
	private Int32 m_cacheEntryAnimSequence; // 0x58
	private NormalAdapter m_adapter; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2326818 VA: 0x759493e818
	public override Void OnValueChanged(TuningHomeProperty property) { }
	// RVA: 0x2326940 VA: 0x759493e940
	private Void _InitIfNot() { }
	// RVA: 0x2326ed4 VA: 0x759493eed4
	public Void .ctor() { }
}
```