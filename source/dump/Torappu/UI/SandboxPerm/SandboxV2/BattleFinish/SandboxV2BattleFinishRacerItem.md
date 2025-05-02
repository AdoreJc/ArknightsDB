# SandboxV2BattleFinishRacerItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2.BattleFinish`


## Fields

- `Text _textName`

- `Image _imgRacer`

- `GameObject _rankEmptyGo`

- `GameObject _rankNormalGo`

- `GameObject _otherRacerGo`

- `GameObject _myRacerGo`

- `Color _colorOtherRacerName`

- `Color _colorMyRacerName`


## Methods

- `Void Render(SandboxV2RacerInfoModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2.BattleFinish
public class SandboxV2BattleFinishRacerItem : MonoBehaviour, IHotfixable
{
	private Text _textName; // 0x18
	private Image _imgRacer; // 0x20
	private GameObject _rankEmptyGo; // 0x28
	private GameObject _rankNormalGo; // 0x30
	private GameObject _otherRacerGo; // 0x38
	private GameObject _myRacerGo; // 0x40
	private Color _colorOtherRacerName; // 0x48
	private Color _colorMyRacerName; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2625e68 VA: 0x7594c3de68
	public Void Render(SandboxV2RacerInfoModel racerModel, Boolean isMe) { }
	// RVA: 0x2626170 VA: 0x7594c3e170
	public Void .ctor() { }
}
```