# RL01CurrentDifficultyView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `GameObject _hardModeTrackPointGo`

- `Text _textHardModeHint`

- `UIAnimationLocation _switchAnim`

- `AnimationSwitchTween m_currentSwitch`


## Methods

- `Void <>xLuaBaseProxy_SetVisible(Boolean)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class RL01CurrentDifficultyView : RoguelikeTopicCurrentDifficultyBaseView
{
	private GameObject _hardModeTrackPointGo; // 0x40
	private Text _textHardModeHint; // 0x48
	private UIAnimationLocation _switchAnim; // 0x50
	private AnimationSwitchTween m_currentSwitch; // 0x60
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_SetVisible; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26c6b24 VA: 0x7594cdeb24
	protected override Void OnRender(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26c6c2c VA: 0x7594cdec2c
	protected override Void SetVisible(Boolean v) { }
	// RVA: 0x26c6cb8 VA: 0x7594cdecb8
	protected override Void OnInit() { }
	// RVA: 0x26c6dcc VA: 0x7594cdedcc
	public Void .ctor() { }
	// RVA: 0x26c6e3c VA: 0x7594cdee3c
	private Void <>xLuaBaseProxy_SetVisible(Boolean P0) { }
	// RVA: 0x26c6e48 VA: 0x7594cdee48
	private Void <>xLuaBaseProxy_OnInit() { }
}
```