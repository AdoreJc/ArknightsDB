# SandboxV2LogisticsCharBuffInfoView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _textCharName`

- `GameObject _panelTagValid`

- `GameObject _panelTagInvalid`

- `SandboxV2LogisticsCharBeanView _charBeanView`

- `SandboxV2LogisticsComplexBuffItemView _buffItemView`

- `CanvasGroup _canvasGroup`

- `Boolean m_isInited`

- `FadeSwitchTween m_fadeSwitchTween`


## Methods

- `Void _InitIfNot(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsCharBuffInfoView : DataBinder`1
{
	private Text _textCharName; // 0x20
	private GameObject _panelTagValid; // 0x28
	private GameObject _panelTagInvalid; // 0x30
	private SandboxV2LogisticsCharBeanView _charBeanView; // 0x38
	private SandboxV2LogisticsComplexBuffItemView _buffItemView; // 0x40
	private CanvasGroup _canvasGroup; // 0x48
	private Boolean m_isInited; // 0x50
	private FadeSwitchTween m_fadeSwitchTween; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25db654 VA: 0x7594bf3654
	public override Void OnValueChanged(SandboxV2LogisticsHomeProperty property) { }
	// RVA: 0x25db874 VA: 0x7594bf3874
	private Void _InitIfNot(Boolean isShow) { }
	// RVA: 0x25dbeec VA: 0x7594bf3eec
	public Void .ctor() { }
}
```