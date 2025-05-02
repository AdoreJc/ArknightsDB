# RuneBattleFinishHolder

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Image _battleStageBg`

- `Image _battleStageLogo`

- `Text _battleStageTitle`

- `Text _battleStageDesc`

- `Text _runeValue`

- `Text _healthValue`

- `BattleFinishRuneGridAdapter _runeAdapter`

- `BattleFinishCardPlaceHolder _cellFriendTrans`

- `BattleFinishCard _cellObj`

- `Transform _illustTrans`

- `Animator _anim`

- `UICharacterIllust m_illust`


## Methods

- `Void Render(RuneBattleFinishStateBean)`

- `Void PlayAnim()`

- `Void RenderIllust(CharUISkinStruct)`

- `IEnumerator _UpdateIllust()`

- `Void _PlayCharThreeStarVoice(VoiceQuery)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class RuneBattleFinishHolder : MonoBehaviour, IHotfixable
{
	private Image _battleStageBg; // 0x18
	private Image _battleStageLogo; // 0x20
	private Text _battleStageTitle; // 0x28
	private Text _battleStageDesc; // 0x30
	private Text _runeValue; // 0x38
	private Text _healthValue; // 0x40
	private BattleFinishRuneGridAdapter _runeAdapter; // 0x48
	private List`1 _cellTransList; // 0x50
	private BattleFinishCardPlaceHolder _cellFriendTrans; // 0x58
	private BattleFinishCard _cellObj; // 0x60
	private Transform _illustTrans; // 0x68
	private Animator _anim; // 0x70
	private UICharacterIllust m_illust; // 0x78
	private const Int32 MAXFRAME; // 0x0
	private const String START_ANIM_KEY; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0_RenderIllust; // 0x10
	private static DelegateBridge __Hotfix0__UpdateIllust; // 0x18
	private static DelegateBridge __Hotfix0__PlayCharThreeStarVoice; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31c6e38 VA: 0x75957dee38
	public Void Render(RuneBattleFinishStateBean stateBean) { }
	// RVA: 0x31c7ab4 VA: 0x75957dfab4
	public Void PlayAnim() { }
	// RVA: 0x31c78d0 VA: 0x75957df8d0
	public Void RenderIllust(CharUISkinStruct randomIllust) { }
	// RVA: 0x31c96dc VA: 0x75957e16dc
	private IEnumerator _UpdateIllust() { }
	// RVA: 0x31c9788 VA: 0x75957e1788
	private Void _PlayCharThreeStarVoice(VoiceQuery voiceQuery) { }
	// RVA: 0x31c9900 VA: 0x75957e1900
	public Void .ctor() { }
}
```