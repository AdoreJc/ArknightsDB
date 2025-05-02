# BattleFinishMetaDisplayView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `UIFullScreenImage _blurBackground`

- `Text _txtStageCode`

- `Text _txtStageName`

- `Text _txtWord`

- `UIAnimationLocation _animationLocation`

- `Tween m_animTween`


## Methods

- `Void Render(BattleInfoViewModel)`

- `Void _PlayAnimWithSignal(String)`

- `Void _StopBattleFinishBGM()`

- `Void EventOnCloseBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishMetaDisplayView : MonoBehaviour, IHotfixable
{
	private UIFullScreenImage _blurBackground; // 0x18
	private Text _txtStageCode; // 0x20
	private Text _txtStageName; // 0x28
	private Text _txtWord; // 0x30
	private UIAnimationLocation _animationLocation; // 0x38
	private Tween m_animTween; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayAnimWithSignal; // 0x8
	private static DelegateBridge __Hotfix0__StopBattleFinishBGM; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCloseBtnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2e908d0 VA: 0x75954a88d0
	public Void Render(BattleInfoViewModel viewModel) { }
	// RVA: 0x2e93874 VA: 0x75954ab874
	private Void _PlayAnimWithSignal(String signal) { }
	// RVA: 0x2e93998 VA: 0x75954ab998
	private Void _StopBattleFinishBGM() { }
	// RVA: 0x2e93a64 VA: 0x75954aba64
	public Void EventOnCloseBtnClick() { }
	// RVA: 0x2e93ac8 VA: 0x75954abac8
	public Void .ctor() { }
}
```