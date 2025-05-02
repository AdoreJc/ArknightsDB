# SandboxV2BattleFinishRacingRankItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2.BattleFinish`


## Fields

- `Text _textPosEmpty`

- `Text _textPos`

- `Text _textName`

- `Text _textType`

- `Text _textTime`

- `GameObject _otherPartGo`

- `GameObject _selfPartGo`

- `Color _colorOther`

- `Color _colorSelf`

- `Color _colorSelfPos`


## Methods

- `Void Render(SandboxV2RacerInfoModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2.BattleFinish
public class SandboxV2BattleFinishRacingRankItem : MonoBehaviour, IHotfixable
{
	private Text _textPosEmpty; // 0x18
	private Text _textPos; // 0x20
	private Text _textName; // 0x28
	private Text _textType; // 0x30
	private Text _textTime; // 0x38
	private GameObject _otherPartGo; // 0x40
	private GameObject _selfPartGo; // 0x48
	private Color _colorOther; // 0x50
	private Color _colorSelf; // 0x60
	private Color _colorSelfPos; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x26261e0 VA: 0x7594c3e1e0
	public Void Render(SandboxV2RacerInfoModel racerModel, Boolean isSelf) { }
	// RVA: 0x26266a8 VA: 0x7594c3e6a8
	public Void .ctor() { }
}
```