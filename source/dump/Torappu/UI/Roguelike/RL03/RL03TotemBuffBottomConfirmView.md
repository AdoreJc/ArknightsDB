# RL03TotemBuffBottomConfirmView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `GameObject _panelInvalid`

- `GameObject _panelValid`

- `Text _txtWaitTips`

- `GameObject _panelBgNormal`

- `GameObject _panelBgBoss`

- `Graphic _graphicConfirmFog`

- `Color _colorNoResonance`

- `Color _colorRed`

- `Color _colorBlue`

- `Color _colorGreen`

- `Color _colorBoss`


## Methods

- `Void Render(RL03TotemBuffBottomViewModel)`

- `Color _GetConfirmBgColor(Boolean, Boolean, RL03TotemBuffBottomViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffBottomConfirmView : MonoBehaviour, IHotfixable
{
	private GameObject _panelInvalid; // 0x18
	private GameObject _panelValid; // 0x20
	private Text _txtWaitTips; // 0x28
	private GameObject _panelBgNormal; // 0x30
	private GameObject _panelBgBoss; // 0x38
	private Graphic _graphicConfirmFog; // 0x40
	private Color _colorNoResonance; // 0x48
	private Color _colorRed; // 0x58
	private Color _colorBlue; // 0x68
	private Color _colorGreen; // 0x78
	private Color _colorBoss; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetConfirmBgColor; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ba5b8c VA: 0x75951bdb8c
	public Void Render(RL03TotemBuffBottomViewModel viewModel) { }
	// RVA: 0x2ba5ff0 VA: 0x75951bdff0
	private Color _GetConfirmBgColor(Boolean isResonance, Boolean isBoss, RL03TotemBuffBottomViewModel viewModel) { }
	// RVA: 0x2ba60ec VA: 0x75951be0ec
	public Void .ctor() { }
}
```