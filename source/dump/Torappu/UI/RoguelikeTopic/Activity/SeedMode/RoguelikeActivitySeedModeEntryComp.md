# RoguelikeActivitySeedModeEntryComp

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `GameObject _newTrack`

- `GameObject _lockPanel`

- `GameObject _disablePanel`

- `GameObject _enablePanel`

- `UIAnimationLocation _enableAnim`

- `Text _timeDesc`

- `RoguelikeActivityEntrySeedModeEntryCompModel m_cachedModel`

- `Tween m_enableTween`


## Methods

- `Void _PlayEnableTween()`

- `Void _StopEnableTween()`

- `Void OnClickOpenSeedMode()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivitySeedModeEntryComp : RoguelikeTopicActivityEntryComp`1
{
	private GameObject _newTrack; // 0x20
	private GameObject _lockPanel; // 0x28
	private GameObject _disablePanel; // 0x30
	private GameObject _enablePanel; // 0x38
	private UIAnimationLocation _enableAnim; // 0x40
	private Text _timeDesc; // 0x50
	private RoguelikeActivityEntrySeedModeEntryCompModel m_cachedModel; // 0x58
	private Tween m_enableTween; // 0x60
	private static DelegateBridge __Hotfix0__Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayEnableTween; // 0x8
	private static DelegateBridge __Hotfix0__StopEnableTween; // 0x10
	private static DelegateBridge __Hotfix0_OnClickOpenSeedMode; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26de0f0 VA: 0x7594cf60f0
	protected override Void _Render(RoguelikeActivityEntrySeedModeEntryCompModel actEntryCompModel) { }
	// RVA: 0x26de228 VA: 0x7594cf6228
	private Void _PlayEnableTween() { }
	// RVA: 0x26de350 VA: 0x7594cf6350
	private Void _StopEnableTween() { }
	// RVA: 0x26de3e0 VA: 0x7594cf63e0
	public Void OnClickOpenSeedMode() { }
	// RVA: 0x26de4ec VA: 0x7594cf64ec
	public Void .ctor() { }
}
```