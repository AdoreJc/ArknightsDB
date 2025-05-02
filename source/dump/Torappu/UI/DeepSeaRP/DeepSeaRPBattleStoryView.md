# DeepSeaRPBattleStoryView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `RectTransform _leftPanel`

- `RectTransform _rightPanel`

- `RectTransform _centerIcon`

- `CanvasGroup _selfCanvas`

- `CanvasGroup _leftCanvas`

- `CanvasGroup _rightCanvas`

- `CanvasGroup _leftTextCanvas`

- `CanvasGroup _rightTextCanvas`

- `Boolean m_isInited`

- `StorySwitchTween m_switchTween`


## Methods

- `Void OnEnter()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPBattleStoryView : DataBinder`1, IHotfixable
{
	private DeepSeaRPBattleStoryViewObject[] _btnPanelGroup; // 0x20
	private RectTransform _leftPanel; // 0x28
	private RectTransform _rightPanel; // 0x30
	private RectTransform _centerIcon; // 0x38
	private CanvasGroup _selfCanvas; // 0x40
	private CanvasGroup _leftCanvas; // 0x48
	private CanvasGroup _rightCanvas; // 0x50
	private CanvasGroup _leftTextCanvas; // 0x58
	private CanvasGroup _rightTextCanvas; // 0x60
	private Boolean m_isInited; // 0x68
	private StorySwitchTween m_switchTween; // 0x70
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29beda8 VA: 0x7594fd6da8
	public Void OnEnter() { }
	// RVA: 0x29c14dc VA: 0x7594fd94dc
	public override Void OnValueChanged(DeepSeaRPBattleNodeDetailProperty property) { }
	// RVA: 0x29c140c VA: 0x7594fd940c
	private Void _InitIfNot() { }
	// RVA: 0x29c18a8 VA: 0x7594fd98a8
	public Void .ctor() { }
}
```